# Pagecraft — site

Site institucional da Pagecraft. É um site estático (HTML + CSS + um pouco de JavaScript), sem etapa de build.

## Arquivos

| Arquivo | O que é |
| --- | --- |
| `index.html` | O site inteiro |
| `404.html` | Página de "não encontrada" |
| `assets/` | Logos (versão clara e para fundo escuro) |
| `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png` | Ícone da aba e do atalho no celular |
| `og.png` | Imagem que aparece quando o link é enviado no WhatsApp e nas redes |
| `vercel.json` | Configuração da Vercel |
| `robots.txt` | Libera o Google para indexar o site |

## Publicar na Vercel

1. Crie um repositório no GitHub (ex.: `pagecraft-site`) e envie estes arquivos para ele.
2. Em vercel.com, clique em **Add New → Project** e importe o repositório.
3. Configure assim:
   - **Framework Preset:** Other
   - **Root Directory:** `./`
   - **Build Command:** deixe vazio
   - **Output Directory:** deixe vazio
   - **Install Command:** deixe vazio
   - **Environment Variables:** nenhuma
4. Clique em **Deploy**.

Depois disso, todo `git push` na branch `main` publica o site automaticamente.

## Depois de publicar

**Imagem de compartilhamento:** troque `content="/og.png"` no `index.html` pelo endereço completo, por exemplo `https://pagecraft.vercel.app/og.png`. O WhatsApp só mostra a imagem com o endereço completo.

**Domínio próprio:** na Vercel, abra o projeto → **Settings → Domains** → adicione o domínio e siga as instruções de DNS que ela mostrar.

## Contato no site

Todos os botões abrem o WhatsApp `+55 21 96692-0110` com mensagem pronta. Para trocar o número, procure `5521966920110` no `index.html` e substitua em todos os lugares.
# pagecraft-site
