# Estratégia Renove Capilar — Dashboard SP3

Dashboard estático de planejamento de mídia paga para o cliente **Renove Capilar** (Keila Alves · tricologia). Estrutura clonada do modelo Smart Plástica e adaptada para 3 unidades em São Paulo.

## Estrutura

```
estrategia-renove-capilar/
├── index.html             # Hub com cards das 3 unidades
├── tatuape.html           # Estratégia Tatuapé (Meta-only · R$500/mês)
├── moema.html             # Estratégia Moema (Google + Meta · R$1.750/mês)
├── paulista.html          # Estratégia Paulista (Google + Meta · R$1.750/mês)
└── docs/
    ├── stories/
    │   ├── EPIC-001-dashboard-estrategia-renove.md
    │   ├── STORY-001.1-clone-html-estrutural.md
    │   └── STORY-001.2-estrategia-paid-media.md
    ├── strategy/
    │   └── STRATEGY-DRAFT.md   # Estratégia completa @paidmedia-orqx
    └── PENDING.md              # 18 pendências priorizadas pra cliente
```

## Como visualizar localmente

```bash
cd ~/Desktop/Projetos/estrategia-renove-capilar
open index.html
# ou
python3 -m http.server 8000
# → http://localhost:8000
```

## Status

| Item | Status |
|---|---|
| Estrutura HTML | ✅ pronta |
| Estratégia mídia paga | ✅ draft v0.1 |
| Pendências documentadas | ✅ priorizadas |
| Dados Paulista | 🔴 pendente |
| Material visual | 🔴 pendente |
| Tracking (GTM/Pixel/GA4) | 🔴 aguarda LP |
| Deploy GitHub Pages | ⏸ próxima story |

## Orçamento total

R$ 4.000/mês · R$ 133/dia

| Unidade | Google | Meta | Total |
|---|---:|---:|---:|
| Tatuapé | — | R$ 500 | R$ 500 |
| Moema | R$ 500 | R$ 1.250 | R$ 1.750 |
| Paulista | R$ 500 | R$ 1.250 | R$ 1.750 |

## Próximos passos

1. João coleta pendências de docs/PENDING.md com a cliente
2. SP3 cria BM Meta + IG Paulista + GTM/Pixel/GA4 isolados
3. SP3 valida RSAs com skill `rsa-excelente`
4. SP3 sobe campanhas pausadas no painel
5. Go live após aprovação cliente
