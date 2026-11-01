# Draco Pixel Creature

Criatura pixel art autónoma desarrollada con Canvas 2D, migrada a React 19, TypeScript y Vite.

## Contenido

- **Código fuente:** [draco-pixel-creature-v11-react.zip](releases/draco-pixel-creature-v11-react.zip)
- **Git bundle:** [draco-pixel-creature.bundle](releases/draco-pixel-creature.bundle)
- **Versión base:** v11.0.0
- **Rama de desarrollo:** main

## Requisitos

- Node.js >= 22.12.0
- npm

## Desarrollo

```bash
npm install
npm run dev
```

## Comprobaciones

```bash
npm test
npm run typecheck
npm run build
```

La migración conserva el motor Canvas 2D existente como implementación de transición, encapsulado desde React con limpieza del ciclo de vida. La interfaz y la estructura del proyecto ya están separadas por componentes, dominio, motor, servicios y estilos.

**Estado de validación:** se realizaron comprobaciones estructurales y de TypeScript. La compilación de producción con Vite queda pendiente de ejecutar en un entorno con acceso al registro de npm.
