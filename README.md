# zecabr.github.io

Site pessoal do Zeca — [zecabr.github.io](https://zecabr.github.io).

Astro 5 + MDX, hospedado no GitHub Pages via GitHub Actions. Sem framework CSS. Fraunces + Manrope via Google Fonts. Zero JS por padrão.

## Rodar local

```bash
npm install
npm run dev
```

Site sobe em http://localhost:4321.

## Publicar

Push na `main`. O workflow em `.github/workflows/deploy.yml` faz build + deploy no GitHub Pages automaticamente.

**Pré-requisito na primeira vez:** ir em `Settings → Pages` do repo e selecionar **Build and deployment: Source → GitHub Actions**.

## Estrutura

```
src/
├── components/     # blocos reutilizáveis (Header, Footer)
├── layouts/        # HTML shell com meta tags, fontes, favicon
├── pages/          # rotas (index, sobre, projetos, notas, contato)
└── styles/         # CSS puro, tokens, dark/light
public/             # favicon, og-image, .nojekyll
```

## Licença

MIT — código e conteúdo.
