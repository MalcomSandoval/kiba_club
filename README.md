# **Estructura de carpetas** 

📦 kiba-dashboard/
│
├── 📁 public/                 # Archivos estáticos (logos, íconos, etc.)
│   ├── logo.svg
│   └── favicon.ico
│
├── 📁 src/
│   ├── 📁 components/         # Componentes reutilizables (UI)
│   │   ├── Navbar.astro
│   │   ├── Sidebar.astro
│   │   ├── CardStat.astro
│   │   ├── Table.astro
│   │   └── PlayerForm.astro
│   │
│   ├── 📁 layouts/            # Estructuras base de páginas
│   │   ├── BaseLayout.astro
│   │   └── DashboardLayout.astro
│   │
│   ├── 📁 pages/              # Rutas del sistema
│   │   ├── index.astro               # Pantalla de inicio de sesión
│   │   ├── dashboard.astro           # Panel principal
│   │   ├── jugadores.astro           # Gestión de jugadores
│   │   ├── pagos.astro               # Pagos y cuentas de acceso
│   │   ├── configuracion.astro       # Configuración general
│   │   └── api/                      # Endpoints (si usas Astro API routes)
│   │       └── jugadores.ts
│   │
│   ├── 📁 lib/                # Conexión y utilidades
│   │   ├── supabaseClient.ts        # Inicialización del cliente Supabase
│   │   ├── auth.ts                  # Funciones de autenticación
│   │   └── utils.ts                 # Funciones auxiliares (formato fechas, colores, etc.)
│   │
│   ├── 📁 styles/
│   │   ├── base.css
│   │   └── tailwind.css
│   │
│   └── env.d.ts               # Tipado de variables de entorno
│
├── .env                      # Claves Supabase (anon y url)
├── astro.config.mjs
├── tailwind.config.mjs
├── tsconfig.json
├── package.json
└── README.md



# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── astro.svg
│   ├── components
│   │   └── Welcome.astro
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
