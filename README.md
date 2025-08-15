# Conversor de Unidades de Almacenamiento

Una aplicación web moderna y responsiva para convertir entre diferentes unidades de almacenamiento de datos. Desarrollada con Astro, TypeScript y Tailwind CSS.

## Descripción

Esta aplicación permite a los usuarios convertir de manera sencilla y precisa entre diferentes unidades de almacenamiento de datos como Bytes, Kilobytes, Megabytes, Gigabytes y Terabytes. La interfaz cuenta con un diseño moderno, limpio y completamente responsivo.

## Características

- Conversión en tiempo real entre unidades de almacenamiento
- Interfaz moderna con efectos glassmorphism
- Diseño completamente responsivo
- Soporte para las siguientes unidades:
  - Byte
  - Kilobyte (KB)
  - Megabyte (MB)
  - Gigabyte (GB)
  - Terabyte (TB)
- Formato inteligente de números grandes
- Valores sugeridos para conversiones comunes
- Validación de entrada en tiempo real

## Tecnologías

- **Astro 5.13.0** - Framework web moderno
- **TypeScript 5.9.2** - Tipado estático para JavaScript
- **Tailwind CSS 4.1.12** - Framework de CSS utilitario
- **Vite** - Herramienta de construcción rápida
- **HTML5** - Marcado semántico
- **CSS3** - Estilos avanzados con gradientes y animaciones

## Requisitos Previos

- Node.js (versión 18 o superior)
- pnpm (recomendado) o npm

## Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/Over1185/Conversor-Web.git
cd Conversor-Web
```

1. Instalar las dependencias:

```bash
pnpm install
```

O usando npm:

```bash
npm install
```

## Desarrollo

Para iniciar el servidor de desarrollo:

```bash
pnpm dev
```

O usando npm:

```bash
npm run dev
```

La aplicación estará disponible en `http://localhost:4321`

## Construcción

Para construir la aplicación para producción:

```bash
pnpm build
```

Para previsualizar la construcción:

```bash
pnpm preview
```

## Estructura del Proyecto

```text
src/
├── components/          # Componentes reutilizables
│   ├── Header.astro    # Cabecera de la aplicación
│   ├── Footer.astro    # Pie de página
│   ├── Selector.astro  # Selector de unidades
│   └── InputNumber.astro # Campo de entrada numérica
├── layouts/
│   └── Layout.astro    # Layout principal
├── pages/
│   └── index.astro     # Página principal
└── styles/
    └── global.css      # Estilos globales
```
---

**Versión:** 1.0.0