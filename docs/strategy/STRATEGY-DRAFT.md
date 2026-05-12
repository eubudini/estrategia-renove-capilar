# Estratégia de Mídia Paga — Renove Capilar (Draft v0.1)

> Owner: @paidmedia-orqx (Apex) · Status: Draft · Última atualização: 2026-05-11
> Pendências bloqueantes: ver `docs/PENDING.md`

## 1. Premissas

| Item | Valor |
|---|---|
| Vertical | Tricologia capilar (saúde do couro cabeludo) |
| Profissional | Keila Alves (tricologista · método "Raiz Saudável") |
| Oferta de entrada | Avaliação tricológica · R$ 100 |
| Ticket médio pós-avaliação | **[TBD]** |
| Unidades | Tatuapé (ZL) · Moema (ZS) · Paulista (Centro/Jardins) |
| Orçamento total | R$ 4.000/mês |
| Conta Google Ads | 646-948-2801 (MCC SP3) |
| Conta Meta Ads | **[TBD: BM novo ou SP3]** |
| Tracking | Stack novo isolado (GA4 + GTM + Pixel) · **não usar** GA4 das outras unidades |

## 2. Distribuição de verba por unidade

| Unidade | Google | Meta | Total/mês | Total/dia | Estratégia |
|---|---:|---:|---:|---:|---|
| Tatuapé | — | R$ 500 | R$ 500 | ~R$ 17 | BOFU + ENG (operação enxuta, já performando) |
| Moema | R$ 500 | R$ 1.250 | R$ 1.750 | ~R$ 58 | Search + TOFU + BOFU + ENG (funil compacto) |
| Paulista | R$ 500 | R$ 1.250 | R$ 1.750 | ~R$ 58 | Search + TOFU + BOFU + ENG (funil compacto) |
| **Total** | **R$ 1.000** | **R$ 3.000** | **R$ 4.000** | **R$ 133** | — |

## 3. Por que essa arquitetura

### Tatuapé enxuta
R$ 17/dia não comporta funil completo sem diluir aprendizado. Como a operação já tem boa entrega segundo o cliente, foco em **direct response (BOFU)** + ENG para alimentar a base orgânica e o pixel. Sem TOFU/MOFU dedicados.

### Moema/Paulista funil compacto
R$ 41/dia no Meta + R$ 17/dia no Google. Funil em 3 camadas: TOFU (descoberta), BOFU (conversão direta + retarget dentro do BOFU), ENG (seguidores). MOFU não vira campanha separada — o retargeting roda como conjunto dentro da BOFU para evitar fragmentação de orçamento.

### Google Search nas duas Sul/Centro
Tricologia tem volume de busca **alto e qualificado** em SP. R$ 500/mês cobre 3 ad groups (Tricologia geral · Queda capilar · Couro cabeludo) com Maximizar Conversões. Tatuapé não recebe Search porque a Zona Leste tem volume menor para essas kws — preferimos concentrar em ZS e Centro/Jardins.

## 4. Métricas-alvo (hipóteses)

| Métrica | Tatuapé | Moema | Paulista |
|---|---:|---:|---:|
| CPL alvo (Meta) | R$ 25-40 | R$ 30-50 | R$ 30-50 |
| CPL alvo (Google) | — | R$ 40-70 | R$ 40-70 |
| Leads/mês esperados | 12-20 | 35-55 | 35-55 |
| Show-up avaliação | **[TBD: confirmar com cliente]** | — | — |

> **Validar:** comparar com benchmark `Allegra` (memory: conta 7279584158 referência odonto SP, CPL Institucional R$35) — pode ser útil mesmo sendo odonto, perfil socioeconômico do público overlaps.

## 5. Audiências (Meta)

### Genérico (todas as unidades)
- **Idade:** 28–55 (TOFU/BOFU) · 25–55 (ENG)
- **Gênero:** F + M (não excluir homens — alopecia masculina é grande mercado)
- **Idioma:** Português (BR)

### Interesses base
- Cuidado capilar · Cabelo · Tratamento capilar
- Queda capilar · Antiqueda · Calvície
- Dermatologia · Tricologia
- Bem-estar · Autoestima · Beleza

### Custom Audiences (criar no Pixel)
- CA01 — Video 75% (90d)
- CA02 — Engajamento IG/FB (90d)
- CA03 — LP visitantes (30d / 90d)
- CA04 — Lead Form aberto sem submit (90d)
- CA05 — Leads convertidos (180d) → **excluir** em todos os conjuntos
- CA06 — Pacientes Renove (upload manual mensal) → **excluir**

### Lookalikes (após 200+ leads)
- LAL 1% Leads convertidos
- LAL 1–3% Pacientes Renove
- LAL 1% Engajados IG

## 6. Criativo (orientação para captação)

> **Bloqueia:** material visual da Keila. Idealmente 20-30 vídeos curtos (15-60s) por unidade ao longo do trimestre.

### Pilares de conteúdo
1. **Educativo** — "como identificar queda", "diferença entre queda x quebra", "papel do couro cabeludo"
2. **Método Raiz Saudável** — diferencial (não trata só o fio, trata a origem)
3. **Antes/Depois reais** — com autorização escrita (LGPD)
4. **Depoimentos** — paciente fala em vídeo
5. **Bastidores** — avaliação tricológica acontecendo, equipamentos
6. **Mitos e verdades** — quebra de objeções (xampu milagroso, minoxidil sozinho etc.)

### Tom de voz
- Especialista acolhedora (Keila como autoridade)
- Sem promessas absolutas
- Linguagem acessível (evitar jargão dermato)

## 7. Tracking & Mensuração

### Stack novo isolado (recomendado)
- **GA4** propriedade nova `Renove Capilar — SP3`
- **GTM** container novo (plantar no site/LP nova)
- **Pixel Meta** novo (no BM definido)
- **Conversões Google Ads** vinculadas ao GA4 + tag direta no GTM (dupla camada)

### Eventos a configurar
| Evento | Onde | Importância |
|---|---|---|
| `view_content` | LP load | Auxiliar |
| `lead_form_open` | Click no botão | Auxiliar |
| `lead_form_submit` | Submit do form | **Primária** |
| `whatsapp_click` | Click WPP | **Primária** |
| `scheduling_completed` | Confirmação no calendário | **Macro** (se houver) |

### Atribuição
- Janela: 7d click · 1d view
- Modelo: data-driven (default GA4/Meta)
- UTMs: **não usar** no Google Ads (regra SP3) · usar no Meta com convenção `utm_source=meta|utm_medium=cpc|utm_campaign={camp_id}`

## 8. Sequência de ativação (operacional)

1. ✅ Estrutura HTML criada (este projeto)
2. ⏳ **Cliente entrega:** endereço/WPP Paulista · ticket médio · jornada do lead · material visual · URL LP nova
3. ⏳ **SP3 cria:** BM Meta (se novo) · IG @renovecapilarpaulista · GTM/Pixel/GA4 isolados
4. ⏳ **SP3 valida:** RSAs via skill `rsa-excelente` antes de subir Google (3 ad groups Moema + 3 ad groups Paulista)
5. ⏳ **SP3 sobe pausado:** todas as campanhas no painel para revisão do cliente
6. ⏳ **Go live:** ativar campanhas após aprovação
7. ⏳ **Dia 7/15/30:** otimizações de bid, kill de adset com CPL > 2x meta, escalonamento dos que entregam

## 9. Próximos refinamentos (após dados pendentes)

- [ ] Validar/ajustar Tier 1 de cada unidade com base no endereço real + perfil socioeconômico
- [ ] Refinar CPL alvo após confirmar ticket médio e LTV
- [ ] Definir frequência de retargeting (recomendado: cap 3x/7d para BOFU)
- [ ] Calibrar bidding Google (mudar para tCPA após 30 leads/ad group)
- [ ] Definir cadência de criativo (recomendado: 4 vídeos novos/unidade/mês para combater fadiga)
- [ ] Definir comunicação cross-unidade (cliente pode procurar Tatuapé mas converter em Moema?)
