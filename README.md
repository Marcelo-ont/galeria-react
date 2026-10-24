# Galería plus

Galería de imágenes en React + Vite, con calificación por estrellas, promedio y modal de detalle.

**Demo:** https://galeria-351ad.web.app

## Características

- Galería de imágenes de las cuatro estaciones
- Sistema de calificación con estrellas (`Rate` / `Star`)
- Cálculo del promedio de calificaciones
- Modal de detalle implementado con `useRef`

## Requisitos

- Node.js 18 o superior

## Desarrollo

```bash
npm install
npm run dev
```

## Build de producción

```bash
npm run build
npm run preview
```

## Despliegue

El sitio se publica en Firebase Hosting (proyecto `galeria-351ad`):

```bash
npm run build
firebase deploy --only hosting
```

## Estructura

```
src/
├── App.jsx
├── main.jsx
├── index.css
├── assets/            # imágenes de las estaciones
└── components/
    ├── header.jsx
    ├── mainSection.jsx
    ├── footer.jsx
    ├── rate.jsx
    ├── star.jsx
    ├── modal.jsx
    └── button.jsx
```
