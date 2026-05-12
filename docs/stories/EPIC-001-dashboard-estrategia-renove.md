# EPIC-001 — Dashboard de Estratégia Renove Capilar

**Status:** In Progress
**Owner:** @sinapse-orqx (Imperator)
**Criado:** 2026-05-11
**Cliente:** Renove Capilar (Keila Alves — tricologista)

## Contexto

Cliente novo SP3 (Renove Capilar) com 3 unidades em São Paulo: Tatuapé, Moema, Paulista. Foco exclusivo em **tricologia capilar**. Cliente saiu da gestão anterior e SP3 assume gestão exclusiva. Orçamento total: R$ 4.000/mês.

## Distribuição de orçamento

| Unidade | Google Ads | Meta Ads | Total |
|---|---:|---:|---:|
| Tatuapé | — | R$ 500 | R$ 500 |
| Moema | R$ 500 | R$ 1.250 | R$ 1.750 |
| Paulista | R$ 500 | R$ 1.250 | R$ 1.750 |
| **TOTAL** | **R$ 1.000** | **R$ 3.000** | **R$ 4.000** |

## Objetivo

Replicar a arquitetura visual e funcional do dashboard de referência (Smart Plástica — `matheus-soier.github.io/estrategia-meta-ads-smart-plastica`) adaptada para o contexto **tricologia capilar / Renove**, com:

- `index.html` — cards das 3 unidades + resumo consolidado
- `tatuape.html`, `moema.html`, `paulista.html` — página dedicada por unidade com 9 seções (nomenclatura, regiões, orçamento, TOFU/MOFU/BOFU/ENG, copy master, audiências)
- Hospedagem futura: GitHub Pages do João Vitor

## Stories vinculadas

- [STORY-001.1](./STORY-001.1-clone-html-estrutural.md) — Clone HTML estrutural + adaptação Renove
- [STORY-001.2](./STORY-001.2-estrategia-paid-media.md) — Estratégia de mídia paga (paidmedia)
- STORY-001.3 (futura) — Preenchimento de dados pendentes
- STORY-001.4 (futura) — Deploy GitHub Pages

## Critérios de Aceite (Epic)

- [ ] index.html publicado com 3 cards de unidade clicáveis
- [ ] 3 páginas internas (uma por unidade) com estrutura completa
- [ ] Dados confirmados preenchidos · pendências marcadas como `[TBD]`
- [ ] Estratégia de mídia documentada em `docs/strategy/`
- [ ] Pendências de informação consolidadas em `docs/PENDING.md`
