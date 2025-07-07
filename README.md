# Proyecto DBU-UCI – Portal de Bienestar Universitario

Este repositorio contiene el desarrollo completo del portal web para el Departamento de Bienestar Universitario (DBU) de la Universidad de las Ciencias Informáticas (UCI). Incluye tanto el cliente (frontend) como el servidor (backend) organizados en dos carpetas independientes.

## Estructura del repositorio
```plain-text
univ-wellbeing/
│
├── dsbu-uci-client/ # Frontend del portal, desarrollado con Astro + Tailwind CSS
├── dsbu-uci-server/ # Backend del portal, desarrollado con Strapi CMS
└── README.md
```


## Tecnologías utilizadas

- **Frontend**:
  - Astro
  - Tailwind CSS
  - TypeScript

- **Backend**:
  - Strapi CMS
  - SQLite (modo desarrollo)
  - REST API

## Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/EcoFuturo/univ-wellbeing.git
cd univ-wellbeing
```

### 2. Instalar dependencias - Cliente

```bash
cd dsbu-uci-client
pnpm install
```

### 3. Instalar dependencias - Servidor

```bash
cd ../dsbu-uci-server
pnpm install
```

### 4. Uso en desarrollo

Cliente:

```bash
pnpm dev
```

Servidor

```bash
pnpm develop
```

# Autor
Jerry de Jesús Rivero Aguilar (@KabraX)

# Licencia

Este proyecto se entrega como parte del trabajo de tesis y está bajo los términos definidos por la Universidad de las Ciencias Informáticas de Cuba.
