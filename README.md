# Landing Page (Vite + Tailwind CDN)

Este projeto usa **Vite** (dev server/build) e mantém **Tailwind via CDN** + **Font Awesome via CDN** no `index.html`.

## Rodar localmente

Instale dependências e rode o dev server do Vite:

```bash
npm install
npm run dev
```

Abra o endereço que o Vite mostrar (normalmente `http://localhost:5173`).

## Build / preview

```bash
npm run build
npm run preview
```

## Deploy no Netlify

Este repositório inclui `netlify.toml` para:

- **Build command**: `npm run build`
- **Publish directory**: `dist`


