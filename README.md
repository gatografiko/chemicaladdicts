# Chemical Addicts — Sitio Web Oficial

Sitio web oficial de **Chemical Addicts**, banda de punk de Lugo, Galicia.

## Tecnologías

- [Astro](https://astro.build/) `v6.1.5` — framework web
- [Tailwind CSS](https://tailwindcss.com/) `v4.2.2` — estilos utilitarios (via `@tailwindcss/vite`)
- Google Fonts — Bebas Neue + Oswald + Inter

## Estructura del proyecto

```text
chemicals/
├── public/
│   ├── favicon.ico
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro       # Layout base (meta, fuentes, lang="es")
│   ├── pages/
│   │   └── index.astro        # Página principal — todas las secciones
│   └── styles/
│       └── global.css         # Tailwind + animaciones globales (glitch, marquee, scanlines)
├── astro.config.mjs
└── package.json
```

## Desarrollo local

```bash
npm install
npm run dev
```

El servidor arranca en `http://localhost:4321`.

## Comandos disponibles

| Comando               | Acción                                      |
| --------------------- | ------------------------------------------- |
| `npm run dev`         | Servidor de desarrollo con hot-reload       |
| `npm run build`       | Build de producción en `./dist/`            |
| `npm run preview`     | Preview del build de producción             |
| `npm run astro ...`   | CLI de Astro (`astro add`, `astro check`…)  |

## Secciones del sitio

- **Hero** — Título con efecto glitch animado, grid decorativo y spotlight rojo
- **La Banda** — Bio + tarjeta de premios Muralleando 2025
- **Miembros** — Areny (voz), Manu (guitarra), Rubén (bajo), Tabo (batería)
- **Directos** — Historial y próximos conciertos
- **Ticker** — Banda animada con logros de la banda
- **Contacto** — Links a redes sociales + formulario

## La Banda

Chemical Addicts son una banda de punk de Lugo, Galicia. Ganadores en el festival **Muralleando 2025**:

- Mejor Banda de Versiones
- Mejor Canción Original
- Mejor Álbum

| Red       | Enlace                                                        |
| --------- | ------------------------------------------------------------- |
| Instagram | [@chemicaladdicts](https://www.instagram.com/chemicaladdicts) |
| Facebook  | [chemical.addicts](https://www.facebook.com/chemical.addicts) |

## Requisitos

- Node.js `>=22.12.0`
