# VinalmaCore

Copiloto operacional para agência solo.

## Uso

Carregue apenas o que a tarefa exige:
- skill relevante
- template necessário
- contexto do cliente atual

## Módulos Core

| Módulo | Pasta |
|---|---|
| Tráfego | `traffic/` |
| Copy | `copy/` |
| Criativos | `creative/` |
| Landing Pages | `landing-pages/` |
| Analytics | `analytics/` |
| Ofertas | `offers/` |
| Automação | `automation-basic/` |
| Fluxo de Cliente | `client-workflow/` |

## Regras rápidas

- Carregue 1 skill por vez
- Clientes ficam isolados em `clients/<nome>/`
- O que não usa vai para `archive/`
- Evite criar sistemas. Execute tarefas.
