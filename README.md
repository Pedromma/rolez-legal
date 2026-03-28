# Rolez — páginas legais (GitHub Pages)

Este diretório é o conteúdo publicado em **`pedromma.github.io/rolez-legal/`** (repo GitHub separado ou espelho desta pasta).

## Como nomear os arquivos

| Arquivo | URL na loja / navegador |
|---------|-------------------------|
| **`index.html`** | Abre quando a pessoa entra na **raiz** do site: `https://pedromma.github.io/rolez-legal/` — o servidor entrega automaticamente o `index.html`. Por isso a **política de privacidade** fica nele. |
| **`excluir-conta.html`** | Segunda página: `https://pedromma.github.io/rolez-legal/excluir-conta.html` — o nome do arquivo vira o último pedaço da URL (sem espaços, minúsculas com hífen é o mais comum). |

**Regra simples:** só existe **um** `index.html` por pasta (é a “capa” daquela pasta). Qualquer outra página é um **outro arquivo** `.html` com nome explícito.

Exemplos futuros, se precisar:

- `termos.html` → `.../termos.html`
- `cookies.html` → `.../cookies.html`

## Arquivos atuais

- `index.html` — Política de Privacidade  
- `excluir-conta.html` — Instruções para exclusão de conta (Google Play)

## Publicar

1. Commit + push neste repo (ou copie os arquivos para `pedromma/rolez-legal` no GitHub).  
2. GitHub Pages: branch `main`, pasta raiz.  
3. Aguarde alguns minutos e teste as duas URLs.

## Monorepo

No projeto **role-agenda**, esta pasta fica na **raiz**: `role-agenda/legal/`.  
Modelos e cópias antigas também existem em `front/bares-app/docs/google-play/site/` — a **fonte que você publica** é esta pasta `legal/`.
