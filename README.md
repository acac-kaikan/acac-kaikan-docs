# ACAC Kaikan - Docs

Padrões compartilhados por todos os repositórios do projeto. Veja a visão geral do projeto no [README da organização](https://github.com/acac-kaikan).

## Conteúdo

| Arquivo | O que define |
|---|---|
| [`PADRONIZACAO_COMMITS.md`](./PADRONIZACAO_COMMITS.md) | Padrão de mensagens de commit (baseado em Conventional Commits) |
| [`FLUXO_DE_DESENVOLVIMENTO.md`](./FLUXO_DE_DESENVOLVIMENTO.md) | Fluxo de branches: `feat/nome-da-feature → dev → main` |
| `ENDPOINTS.md` | Contrato de API consumido por `acac-kaikan-api` e `acac-kaikan-web` (ainda em rascunho, não confirmado pelo time) |

## Por que estes arquivos ficam juntos

`acac-kaikan-api` e `acac-kaikan-web` compartilham o mesmo padrão de commits e branches. `ENDPOINTS.md` é o contrato entre os dois lados.