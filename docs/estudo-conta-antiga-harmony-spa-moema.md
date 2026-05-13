# Estudo: Conta Antiga Renove (HARMONY SPA MOEMA LTDA — 528-120-7337)

> **Fonte:** Google Ads MCP SP3 · Período: últimos 30 dias · Data: 2026-05-12
> **Objetivo:** Mapear tudo que funciona na conta legada para replicar e melhorar na conta nova (646-948-2801) das 3 unidades (Tatuapé, Moema, Paulista).

---

## 1. Visão Macro da Conta (LAST_30_DAYS)

| Métrica | Valor |
|---|---:|
| Impressões | 120.658 |
| Cliques | 2.277 |
| Custo total | R$ 2.828,91 |
| Conversões | 187 |
| CTR médio | 1,89% |
| CPC médio | R$ 1,24 |
| **CPL médio** | **R$ 15,13** |

**Diagnóstico:** CPL muito saudável para o nicho tricologia em SP. Benchmark de referência para a conta nova.

---

## 2. Performance por Campanha

| Campanha | Status | Lance | Budget/dia | Imp | Cliques | Custo | Conv | CPL |
|---|---|---|---:|---:|---:|---:|---:|---:|
| **1- TRICOLOGISTA \| TATUAPÉ** | ✅ ON | MAX_CONV | R$ 50 | 43.458 | 765 | R$ 1.303 | **104** | **R$ 12,53** |
| **2- AVALIAÇÃO \| TATUAPÉ** | ✅ ON | MAX_CONV | R$ 40 | 35.795 | 612 | R$ 794 | **45** | **R$ 17,65** |
| **3- TERAPEUTA CAPILAR \| TATUAPÉ** | ✅ ON | MANUAL_CPC | R$ 69 | 26.974 | 591 | R$ 544 | 23 | R$ 23,65 |
| 2- AVALIAÇÃO \| MOEMA | ✅ ON | MANUAL_CPC | R$ 30 | 7.721 | 167 | R$ 96 | 8 | R$ 12,09 |
| 1- TRICOLOGISTA \| MOEMA | ✅ ON | MANUAL_CPC | R$ 30 | 6.600 | 137 | R$ 83 | 7 | R$ 11,91 |
| 3- TERAPEUTA CAPILAR \| MOEMA | ✅ ON | MANUAL_CPC | R$ 50 | 110 | 5 | R$ 7 | 0 | — |

### Insights críticos
- **TATUAPÉ traz 92% das conversões** (172 de 187). Conta madura, dados de conversão fartos → MAXIMIZE_CONVERSIONS funciona.
- **Campanhas com `MAXIMIZE_CONVERSIONS` têm os 2 melhores volumes** (TRICOLOGISTA e AVALIAÇÃO Tatuapé). Confirma: quando há histórico de conversão, smart bidding bate manual.
- **MOEMA é um espelho subexplorado** — CPL R$11,91 e R$12,09 (melhor que Tatuapé!), mas com orçamento curto (R$30/dia) e ainda no manual.
- **TERAPEUTA CAPILAR Moema (R$50/dia)** virtualmente sem impressões — problema de lance/match/geo, NÃO replicar como está.

### Padrão estrutural ganhador (replicar)
3 campanhas por unidade, cada uma focada num intent diferente:
1. **TRICOLOGISTA** (marca/profissional) — maior volume, maior intent
2. **AVALIAÇÃO** (informacional → consulta) — funil de descoberta
3. **TERAPEUTA CAPILAR** (alternativa profissional) — captura quem pesquisa por termos não-médicos

---

## 3. Keywords Campeãs (por volume de conversão e CPL)

### Top 10 — Aprovadas e replicáveis

| Keyword | Match | Conv | Custo | CPL | QS | Conjunto |
|---|---|---:|---:|---:|---:|---|
| **especialista em couro cabeludo** | PHRASE | **14** | R$ 107,76 | **R$ 7,70** | 4 | Tricologista |
| **tricologista** | EXACT | **11** | R$ 110,64 | **R$ 10,06** | 5 | Tricologista |
| **consulta cabelo** | PHRASE | 9 | R$ 90,63 | R$ 10,07 | 0⚠️ | Avaliação |
| **tricologia capilar** | PHRASE | 7 | R$ 124,49 | R$ 17,78 | 4 | Avaliação |
| **tricologista** | PHRASE | 4 | R$ 113,94 | R$ 28,48 | 5 | Tricologista |
| **médico do cabelo** | PHRASE | 3 | R$ 39,27 | R$ 13,09 | 2 | Tricologista |
| **tricologista perto de mim** | EXACT | 3 | R$ 25,42 | R$ 8,47 | 5 | Tricologista |
| **tricologista zona leste** | EXACT | **3** | R$ 14,63 | **R$ 4,87** ⭐ | 7 | Tricologista |
| **tricologista tatuape** | EXACT | 2 | R$ 23,11 | R$ 11,55 | 7 | Tricologista |
| **tricologista sp** | PHRASE | 2 | R$ 6,39 | R$ 3,20 | 5 | Tricologista |

⭐ Padrão de ouro: **EXACT + termo + bairro/zona** = QS 7-8 + CPL ~R$5
⚠️ Keywords com QS 0 frequentes — landing page precisa ajuste

### Padrão de keywords por intent (replicar nas 3 unidades)

**Ad Group "TRICOLOGISTA" (16 keywords):**
- `tricologista` [EXACT, PHRASE]
- `tricologista perto de mim` [EXACT, PHRASE]
- `tricologista {BAIRRO}` [EXACT] — ex: tricologista moema, tricologista pinheiros
- `tricologista {ZONA}` [EXACT] — ex: tricologista zona sul
- `tricologista sp` / `tricologista são paulo` [EXACT, PHRASE]
- `dermatologista tricologista` [EXACT, PHRASE]
- `especialista em couro cabeludo` [PHRASE]
- `médico do cabelo` [EXACT, PHRASE]
- `medico que cuida do cabelo` [EXACT]
- `consulta tricologia` [EXACT, PHRASE]
- `tricologia capilar perto de mim` [EXACT]
- `tratamento capilar {ZONA}` [PHRASE]

**Ad Group "AVALIAÇÃO" (8 keywords):**
- `tricologia capilar` [PHRASE]
- `consulta cabelo` [EXACT, PHRASE]
- `tricoscopia capilar` [PHRASE]
- `diagnóstico capilar` [EXACT, PHRASE]
- `avaliação capilar` [EXACT, PHRASE]

**Ad Group "TERAPEUTA CAPILAR" (8 keywords, mas é o pior performer):**
- `terapeuta capilar` [EXACT, PHRASE]
- `terapia capilar` [EXACT, PHRASE]
- `spa capilar` / `spa de cabelo` [PHRASE]
- `microagulhamento capilar` [PHRASE]
- `terapias capilares` [PHRASE]

> **Recomendação:** Para a conta nova, **manter as 3 campanhas mas reduzir o budget da "TERAPEUTA CAPILAR"** ou pausar até validar conversão. Direcionar peso para TRICOLOGISTA + AVALIAÇÃO.

---

## 4. Termos de Pesquisa que Convertem (oportunidades de novas keywords)

Termos que vieram de match phrase/broad e converteram bem — **transformar em EXACT** na conta nova:

| Termo (search) | Conv | CTR | Custo |
|---|---:|---:|---:|
| `tricologista` | 8 | 3,17% | R$ 85 |
| `tricologista tatuape` | 2 | 13,21% | R$ 23 |
| `tricologista perto de mim` | 3 | 4,76% | R$ 18 |
| `dermatologista tricologista` | 3 | 8,33% | R$ 19 |
| `tricologista zona leste` | 3 | 11,43% | R$ 14 |
| `tricologista são paulo` | 2 | 12,5% | R$ 14 |
| `clinica capilar sp` | 2 | 100% | R$ 3,64 |
| `clínica p r c` | 2 | 22% | R$ 7,62 |
| `dermatologista especializado em queda de cabelo` | 1 | 100% | R$ 7,98 |
| `medico especialista em cabelo` | 1 | 30% | R$ 7,40 |
| `tricologista dr consulta` | 1+2 | 14% | R$ 13 |
| `nome do medico que cuida do couro cabeludo` | 1 | 100% | R$ 2,90 |
| `tricologia capilar` | 1 | 6,82% | R$ 12 |
| `especialista em queda de cabelo feminino` | 1 | 16% | R$ 3,85 |

> **Padrão:** Termos com **bairro/zona/cidade** convertem com CTR alto (10-100%). Sempre adicionar variações geo.

---

## 5. RSAs — Estrutura dos Anúncios Vencedores

### Ad Group "1- TRICOLOGISTA" (104 conversões)

**Headlines (15):**
1. Keila Alves *(brand)*
2. Tricologista em São Paulo
3. Terapeuta Capilar
4. Agende Sua Consulta *(CTA)*
5. `{KeyWord:Tricologista em São Paulo}` *(DKI dinâmico)*
6. Tricologista em SP
7. Especialista em Cabelo
8. Tricologista no Tatuapé *(geo)*
9. Terapia Capilar Tatuapé *(geo)*
10. Tratamento Queda Capilar
11. Clínica Capilar Tatuapé *(geo)*
12. Adeus Queda de Cabelo *(emoção)*
13. Tratamento Couro Cabeludo
14. Problemas no Couro Cabeludo? *(pergunta)*
15. Tratamento Capilar Feminino *(persona)*

**Descriptions (4):**
1. Especialista em doenças do couro cabeludo (tricologia)
2. Terapia capilar com base científica e resultados naturais. Agende uma avaliação
3. Especialista em saúde do couro cabeludo. Atendimento individual.
4. Tratamentos personalizados para queda, caspa e inflamações. Agende já.

### Padrão ganhador (template para conta nova)
- **H1:** Nome marca/profissional
- **H2:** Termo principal + cidade
- **H3:** Termo secundário (Terapeuta Capilar)
- **H4:** CTA "Agende Sua Consulta"
- **H5:** **DKI** `{KeyWord:Default}` ← inserir DKI sempre
- **H6-8:** Variações geo (SP, Bairro, Zona)
- **H9-10:** Tratamento + problema
- **H11:** Clínica + bairro
- **H12:** Headline emocional ("Adeus...")
- **H13-14:** Sintoma/pergunta
- **H15:** Persona (Feminino)
- **D1:** Definição técnica (autoridade)
- **D2:** Diferencial científico + CTA
- **D3:** Especialização + formato (individual)
- **D4:** Lista de problemas + CTA forte

### ⚠️ Adaptações obrigatórias para conta nova
- Trocar "Keila Alves" pelo nome da nova marca/profissional Renove
- Trocar "Tatuapé/Zona Leste" pelo bairro de cada unidade (Moema/Paulista/Tatuapé)
- Manter o DKI `{KeyWord:Default}` — alavanca natural de Ad Strength

---

## 6. Assets (Sitelinks, Callouts, Snippets) — Replicar 1:1

### Sitelinks (5, todos com âncora # — single page)
| Texto | Desc 1 | Desc 2 | URL |
|---|---|---|---|
| Tratamentos | Procedimento e tratamentos | para problemas no couro cabeludo | `/#tratamentos` |
| Contato | Atendimento no Tatuapé | Agende sua avaliação | `/#contato` |
| Depoimentos | Feedbacks e avaliações | Veja o que dizem | `/#depoimentos` |
| Resultados | Veja nossos resultados | Trate de uma vez por todas | `/#resultados` |
| Instagram | Saiba mais sobre os tratamentos | Entre em contato | `/#instagram` |

### Callouts (13 — replicar mantendo a lógica)
1. Tricologista Certificada *(autoridade)*
2. Análise com Tecnologia *(diferencial)*
3. Saúde do Couro Cabeludo *(benefício)*
4. Terapia Capilar Tatuapé *(geo)*
5. Zona Leste SP *(geo)*
6. Fácil Acesso *(conveniência)*
7. Próximo ao Metrô *(conveniência)*
8. Combate a Queda Capilar *(problema)*
9. Tratamento para Alopecia *(problema)*
10. Recupere Seus Cabelos *(emoção)*
11. Adeus Coceira e Caspa *(problema)*
12. Controle da Dermatite *(problema)*
13. Foco na Causa do Problema *(diferencial)*

### Snippets Estruturados (1 grupo)
**Header:** Serviços
**Values:** Tratamento para queda · Controle da Dermatite · Tratamento Alopecia · Coceiras e caspas

> **Para a conta nova:** trocar geo callouts (4, 5, 7) pelos pontos de referência de cada bairro (Moema/Paulista/Tatuapé). Manter o resto idêntico.

---

## 7. Negativas — Biblioteca de Ouro (96+ termos)

A conta tem uma **biblioteca de negativos densa** que economiza muito dinheiro. Categorias:

### 7.1 Concorrentes diretos (BROAD)
`mariotto`, `murta`, `gusmão`, `gusmao`, `vicari`, `donati`, `vinci`, `tatiele`, `tharik`, `azambuja`

### 7.2 Médicos/tricologistas concorrentes (EXACT)
- `dr joao tricologista`
- `dr luciano tricologista`
- `dra priscila barreto tricologista`
- `dra tatiele katzer`
- `dra vanina gegdyszman`
- `rafael neves tricologista`
- `livia vicari`

### 7.3 Avaliações sobre concorrentes
- `avaliações sobre instituto mariotto murta`

### 7.4 Cidades fora da área (BROAD)
`atibaia`, `guarulhos`, `osasco`, `suzano`, `alphaville`, `bauru`, `brasilia`, `cotia`, `jundiai`, `lapa`, `limeira`, `mogi`, `santos`, `sorocaba`

### 7.5 Termos informacionais (EXACT) — ⭐ super importante
- `o que é tricologia` / `o que é tricologia capilar`
- `o que é tricologista` / `o que é tricologista capilar`
- `o que faz um tricologista` / `o que uma tricologista faz`
- `qual a função do tricologista`
- `quem pode ser tricologista`
- `tricologia o que é`
- `tricologista o que é`
- `tricologista cuida de que`

### 7.6 Curiosos sem intenção comercial (BROAD)
`gratis`, `gratuito`, `grátis`, `graça`, `popular`, `barato`, `remedio`, `remédio`, `receita`, `passo` (de "passo a passo")

### 7.7 Convênios (BROAD)
`unimed`, `amil`, `prevent`

### 7.8 Não-relacionado (BROAD)
`cilio`, `cilios`, `cílios`, `keranat`, `loreal`, `minoxidil`, `shampoo`, `vitamina`, `vitaminas`, `chá`, `cha`, `chja`

### 7.9 Nomes próprios soltos (BROAD)
`andre`, `aline`, `gabriel`, `eduardo`, `fabia`, `flavia`, `isadora`, `joao`, `livia`, `luciano`, `maria`, `rafael`, `valeria`, `bel`, `dina`, `leila`

> **Ação:** **Copiar 100% essa biblioteca para a conta nova ANTES de subir as campanhas.** Vai economizar 200-400 reais já na primeira semana só evitando informacional + concorrente.

---

## 8. Plano de Adaptação para a Conta Nova (646-948-2801)

### Fase 1 — Setup base (dia 1)
1. Importar **toda a biblioteca de 96+ negativos** para listas compartilhadas
2. Criar **3 campanhas por unidade ativa**:
   - Tatuapé (Meta-only R$500 segundo memory — confirmar se Google entra)
   - Moema (Google + Meta R$1.750)
   - Paulista (Google + Meta R$1.750)
3. Estrutura por campanha:
   - `[RENOVE] [SEARCH] [MAX.CONV] TRICOLOGISTA | {BAIRRO}` — R$50/dia
   - `[RENOVE] [SEARCH] [MAX.CONV] AVALIAÇÃO | {BAIRRO}` — R$40/dia
   - `[RENOVE] [SEARCH] [MANUAL_CPC] TERAPEUTA CAPILAR | {BAIRRO}` — R$25/dia (teste)

### Fase 2 — Keywords (dia 1)
- Replicar lista do ad group TRICOLOGISTA (16 KWs) adaptando bairro
- Replicar lista do ad group AVALIAÇÃO (8 KWs)
- TERAPEUTA CAPILAR: começar **só com EXACT** (5 KWs) por causa do CPL ruim histórico

### Fase 3 — Anúncios (dia 1)
- 3 RSAs por ad group, seguindo template de 15 headlines + 4 descriptions
- DKI obrigatório em H5
- Adaptar nome de marca/profissional + bairro
- Validar Ad Strength **EXCELENTE** antes de publicar (regra firme da memory)

### Fase 4 — Assets (dia 1)
- 5 sitelinks no nível da campanha, padrão Tratamentos/Contato/Depoimentos/Resultados/Instagram
- 13 callouts (10 universais + 3 por bairro)
- 1 snippet estruturado "Serviços"

### Fase 5 — Configurações (dia 1) ⚠️
- Localização: **raio 5-7km do consultório** + segmento "presença ou interesse"
- **Parceiros de pesquisa OFF**
- **Rede de Display OFF** (a memory já reforça isso)
- Sem UTMs na URL final (regra firme)
- Anúncios odonto: nunca "Especialista" → mas aqui é tricologia, "Especialista em Cabelo" é OK

### Fase 6 — Validação pós-publicação (dia 2-7)
- Search Terms diariamente nos primeiros 7 dias
- Adicionar negativos novos conforme surgirem termos irrelevantes
- Após 14 dias com ≥15 conversões/campanha → migrar TRICOLOGISTA e AVALIAÇÃO para MAXIMIZE_CONVERSIONS

### Fase 7 — Melhorias sobre a conta antiga
| Problema na antiga | Solução na nova |
|---|---|
| Várias KWs com QS 0 (sem URL match) | Criar landing page por intent (tricologista / avaliação / terapeuta) |
| MOEMA subexplorada (CPL menor que Tatuapé) | Subir budget Moema desde o início (R$50, não R$30) |
| TERAPEUTA CAPILAR R$23 CPL em Tatuapé | Começar conservador, broad-match only-exact |
| Sitelinks com âncora # (single page) | Páginas dedicadas se possível → melhora QS |
| Sem segmentação demográfica visível | Aplicar bid modifier +20% para mulheres 30-55 |
| Manual CPC no Moema | Já começar com MAX_CONV se importar conversões |

---

## 9. Métricas-Meta para Conta Nova (primeiros 30 dias)

| KPI | Conta Antiga | Meta Conta Nova |
|---|---:|---:|
| CPL geral | R$ 15,13 | **≤ R$ 12,00** |
| Conv/mês | 187 | 200+ (3 unidades vs 2) |
| CTR | 1,89% | ≥ 2,5% |
| QS médio | ~4 | ≥ 6 |

---

## 10. Checklist Pré-Subida (resumo executivo)

- [ ] Importar 96 negativos como lista compartilhada
- [ ] Criar 9 campanhas (3 por unidade × 3 unidades) ou 6 (sem Tatuapé Google se for Meta-only)
- [ ] Adicionar 24+ keywords por unidade (Tricologista + Avaliação + Terapeuta)
- [ ] Subir 3 RSAs por ad group com DKI e Ad Strength **EXCELENTE**
- [ ] Configurar 5 sitelinks + 13 callouts + 1 snippet por campanha
- [ ] Desativar Display + Parceiros de Pesquisa (manual no painel — MCP não suporta)
- [ ] Setar localização raio 5-7km + "presença ou interesse"
- [ ] Definir meta de conversão (Leads) em todas as campanhas via API
- [ ] Validar Ad Strength antes de ativar (regra rsa-excelente)
- [ ] URL limpa sem UTMs

---

*Fonte: HARMONY SPA MOEMA LTDA (5281207337) · Estudo gerado em 2026-05-12 via MCP google-ads-sp3*
