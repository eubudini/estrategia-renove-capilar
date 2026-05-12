# Pendências — Renove Capilar

> Lista priorizada das informações que o João Vitor precisa coletar com a cliente antes de subir as campanhas. Ordenada por impacto no go-live.

## 🔴 Bloqueante (impede subir campanha)

### 1. Paulista — endereço completo
**Por que bloqueia:** sem endereço, não dá pra configurar geo-targeting do Google nem definir Tier 1 final da Meta.
**Pergunta pra cliente:** "Qual o endereço completo da unidade Paulista? (rua, número, andar/sala, bairro, CEP)"

### 2. Paulista — WhatsApp dedicado
**Por que bloqueia:** lead form do Meta + extensão de chamada no Google precisam de número.
**Pergunta:** "Qual WhatsApp da unidade Paulista?"

### 3. Paulista — Instagram
**Por que bloqueia:** Meta exige página IG/FB vinculada para rodar anúncio.
**Decisão necessária:** criar `@renovecapilarpaulista` (recomendado) ou rodar Paulista usando `@renovecapilar` matriz?

### 4. BM Meta
**Por que bloqueia:** sem definir BM, não cria Pixel nem sobe anúncio.
**Decisão:** criar BM novo dedicado Renove ou usar BM SP3 existente?

### 5. URL da LP nova
**Por que bloqueia:** sem URL, não tem onde direcionar tráfego nem plantar GTM/Pixel/GA4.
**Pergunta:** "A LP nova está em qual URL? Tem subpáginas por unidade (`/tatuape`, `/moema`, `/paulista`)?"

### 6. Acesso ao site/LP pra plantar GTM
**Por que bloqueia:** sem GTM, não tem evento de conversão = Google/Meta otimizam pra cliques, não leads.
**Pergunta:** "Você tem acesso de admin da LP nova ou precisa pedir pra cliente?"

## 🟡 Alta prioridade (impede otimização)

### 7. Ticket médio do tratamento pós-avaliação
**Impacto:** define CPL alvo, ROAS realista e teto de bid.
**Pergunta:** "Quanto a Keila cobra pelo tratamento completo após a avaliação R$100? Tem ranges (anti-queda, dermatite, MMP, microagulhamento)?"

### 8. Jornada do lead
**Impacto:** define se o ad direciona pra form, WhatsApp direto ou agendamento online.
**Pergunta:** "Lead chega no anúncio → cai onde? Form do Meta com follow-up por WhatsApp? Direto pro WhatsApp? Calendário online?"

### 9. Quem atende cada unidade
**Impacto:** se for Keila itinerante, copy muda. Se for equipe treinada, copy enfatiza método. Afeta posicionamento.
**Pergunta:** "Keila atende as 3 unidades pessoalmente em dias diferentes ou tem outras terapeutas treinadas no método dela em Moema/Paulista?"

### 10. Horário de funcionamento por unidade
**Impacto:** ad schedule + tempo de resposta esperado pelo lead.
**Pergunta:** "Qual o horário de funcionamento de cada unidade?"

### 11. Material visual disponível
**Impacto:** sem vídeo, fica só imagem estática = CPM muito mais caro. Smart Plástica tem 25 vídeos como base.
**Pergunta:** "A Keila tem vídeos curtos (Reels) que possamos usar? Antes/Depois com autorização escrita? Fotos da clínica/Keila?"

## 🟢 Média prioridade (ajuda calibrar)

### 12. Histórico da gestão anterior
**Impacto:** ponto de partida realista pra CPL e leads/mês.
**Pergunta:** "A cliente tem dados (mesmo aproximados) do gestor anterior? CPL atual, leads/mês, melhores criativos?"

### 13. Meta de leads/mês ou CPL alvo
**Impacto:** define se vamos escalar agressivo ou conservador.
**Pergunta:** "Qual a expectativa da cliente? Quantos leads/mês por unidade? Ou CPL teto?"

### 14. Conversões Google Ads
**Impacto:** sem conversão configurada, não dá pra usar Maximizar Conversões.
**Ação SP3:** após URL da LP, plantar tag e importar para Google Ads.

### 15. Identidade visual da marca
**Impacto:** consistência visual nos ads.
**Pergunta:** "Tem logo, paleta, tipografia e tom de voz já definidos? Manual da marca?"

## 🔵 Baixa prioridade (refinamento)

### 16. Concorrentes diretos
**Impacto:** quem monitorar via auction insights / spy de criativos.
**Pergunta:** "Quem são as principais concorrentes em tricologia em SP (Zona Sul/Leste/Centro)?"

### 17. Sazonalidade
**Pergunta:** "Tem épocas do ano com mais procura? (ex: pós-verão por queda solar?)"

### 18. Cross-unidade
**Pergunta:** "Lead que mora em Tatuapé mas trabalha na Paulista — qual unidade atende?"

---

## Mensagem sugerida pra cliente (consolidada)

```
Oi Keila! Pra subir as campanhas da Renove com qualidade, preciso de algumas
informações que ainda faltam. Pode me responder?

1. Endereço completo da unidade Paulista (rua, número, bairro, CEP)
2. WhatsApp da unidade Paulista
3. Horário de funcionamento das 3 unidades
4. Ticket médio dos tratamentos após a avaliação (R$100)
5. Como o lead é atendido depois que preenche o formulário? (vai pra WhatsApp humano?
   Tem calendário online?)
6. Você atende as 3 unidades pessoalmente ou tem outras terapeutas treinadas
   no método em Moema e Paulista?
7. Tem vídeos curtos (Reels) da Renove que possamos usar nos anúncios?
   Antes/Depois com autorização das pacientes? Fotos da clínica?
8. Tem algum dado da gestão anterior? Quantos leads/mês, custo por lead?
9. Tem a logo, paleta de cores e identidade visual da marca?

Sobre o site novo:
10. Em qual URL ficou a LP nova? Tem versões por unidade?
11. Posso plantar nossos pixels (Google + Meta) na LP ou precisa pedir pro
    desenvolvedor?

Falta criar o Instagram da unidade Paulista (@renovecapilarpaulista) antes
de subir os anúncios — pode autorizar a criação?

Obrigado!
```
