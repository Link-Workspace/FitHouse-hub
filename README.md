# Fit House Hub — Vite

## Rodar localmente

Abra a pasta no VS Code e execute:

```bash
npm install
npm run dev
```

O endereço normalmente será `http://localhost:5173`.

## Requisitos

- Node.js 18 ou superior
- npm

Confira com:

```bash
node -v
npm -v
```

## Produção

```bash
npm run build
npm run preview
```

## Links dos produtos

No final de `index.html`, altere:

```javascript
const productLinks = {
  playStore: "#",
  appStore: "#",
  website: "#",
  management: "#"
};
```

## GitHub Pages

O workflow `.github/workflows/deploy.yml` publica automaticamente os arquivos da pasta `dist` quando houver push na branch `main`.

No GitHub, entre em **Settings > Pages** e escolha **GitHub Actions** em **Build and deployment**.
