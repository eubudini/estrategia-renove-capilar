# STORY-001.1 — Clone HTML estrutural + adaptação Renove

**Epic:** [EPIC-001](./EPIC-001-dashboard-estrategia-renove.md)
**Status:** Ready
**Owner:** @developer (Pixel)
**Validado por:** @product-lead (Axis)
**Criado:** 2026-05-11

## Descrição

Clonar a estrutura HTML estática do dashboard Smart Plástica e adaptar para Renove Capilar, gerando 4 arquivos HTML (index + 3 unidades). Manter padrão visual (tipografia, paleta minimalista, tabelas, hierarquia). Substituir todos os dados da Smart Plástica pelos dados da Renove. Onde não houver dados confirmados, usar marcador `[TBD]`.

## Escopo IN

- ✅ Clone HTML estático (4 arquivos)
- ✅ Substituição de dados: nome cliente, profissional, endereços, WhatsApps, IGs, orçamentos
- ✅ Adaptação de nomenclatura padrão SP3 (tag `[RENOVE]` ao invés de `[MOEMA]` etc.)
- ✅ Adaptação de regiões Tier 1/Tier 2 por unidade (Zona Leste para Tatuapé, Zona Sul para Moema, Centro/Jardins para Paulista)
- ✅ Adaptação do funil para contexto tricologia (problemas: queda, falhas, rarefação, caspa, dermatite, oleosidade, coceira, enfraquecimento)
- ✅ Placeholders `[TBD: …]` em campos sem dado confirmado

## Escopo OUT

- ❌ Deploy GitHub Pages (story futura)
- ❌ Conteúdo de copy detalhado por anúncio (depende de material visual e estratégia)
- ❌ IDs de Instagram dos vídeos (depende de material da Keila)
- ❌ Implementação de GTM/Pixel/GA4 (depende de URL da LP nova)
- ❌ Criação de campanhas no Google/Meta (story futura, após validação)

## Critérios de Aceite

```
DADO que o desenvolvedor implementa a estrutura
QUANDO o usuário abrir index.html no navegador
ENTÃO vê 3 cards (Tatuapé, Moema, Paulista) com endereço, WhatsApp e métricas resumo
E ao clicar em cada card, abre a página interna correspondente
E cada página interna contém as 9 seções do template Smart Plástica
E todos os campos sem dado confirmado estão marcados como [TBD]
```

## File List

- [x] `index.html`
- [x] `tatuape.html`
- [x] `moema.html`
- [x] `paulista.html`
- [x] `docs/PENDING.md`

## Tasks

- [x] Cabeçalho do projeto e padrão de nomenclatura SP3
- [x] index.html com 3 cards + tabela resumo
- [x] tatuape.html (estrutura adaptada Meta-only R$500/mês)
- [x] moema.html (estrutura adaptada Google + Meta)
- [x] paulista.html (estrutura adaptada Google + Meta, mais TBDs por falta de dados)
- [x] Lista de pendências priorizadas
