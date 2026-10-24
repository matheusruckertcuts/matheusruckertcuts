# Portfólio — Matheus Rückert

Site estático (HTML, CSS e JavaScript puros). Não precisa de build nem de dependências.

## Estrutura

```
index.html
style.css
script.js
.nojekyll
assets/
```

O `index.html` precisa ficar na raiz do repositório, sem pasta extra em volta.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (público).
2. Envie **o conteúdo** desta pasta (não a pasta em si): `index.html`, `style.css`, `script.js`, `.nojekyll` e `assets/`.
3. No repositório, vá em **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
6. Aguarde 1 a 2 minutos e abra o endereço mostrado pelo GitHub:
   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

Dica: se o repositório se chamar `SEU-USUARIO.github.io`, o site abre direto em `https://SEU-USUARIO.github.io/`.

## Testar no computador

Os vídeos do YouTube só tocam em endereço web (abrir o `index.html` com duplo clique causa o erro 153). Na pasta do projeto, rode:

```
python -m http.server 4173
```

e abra http://localhost:4173. Para encerrar, `Ctrl+C`.

## Observações

- Os vídeos são incorporados do YouTube: precisam de internet e de "Permitir incorporação" ativo em cada vídeo.
- As fontes (Syne, Manrope, DM Mono) vêm do Google Fonts.
