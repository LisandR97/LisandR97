# RedM Relógio – versão web (Vercel)

Esta pasta contém apenas o site estático para deploy no Vercel.

## Deploy no Vercel

1. No **Vercel** → teu projeto → **Settings** → **Build & Deployment**
2. Em **Root Directory** escreve: `web`
3. **Build Command:** deixa em branco (ou `echo 'Static'`)
4. **Output Directory:** `.` ou em branco
5. Guarda e faz **Redeploy**

O Electron (package.json, main.js, etc.) fica na raiz do repositório e não é usado pelo Vercel.

## Manter atualizado

Quando alterares o `index (1).html` na raiz do projeto, copia o conteúdo para `web/index.html` antes de fazer push, para o site publicado ficar em dia.
