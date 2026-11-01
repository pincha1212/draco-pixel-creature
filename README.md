# Draco Pixel Creature

Criatura pixel art autónoma. La versión de trabajo v11 fue migrada a React 19, TypeScript y Vite.

## Estado del repositorio

Este repositorio contiene actualmente la documentación inicial. El código fuente de la migración todavía no está publicado aquí.

Los paquetes de la migración están disponibles como archivos adjuntos en la conversación:
- `draco-pixel-creature-v11-react.zip`: proyecto completo.
- `draco-pixel-creature.bundle`: historial Git de la migración, rama `main`.

## Requisitos del proyecto

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

## Arquitectura

La migración conserva el motor Canvas 2D existente como implementación de transición, encapsulado desde React con limpieza del ciclo de vida. La interfaz está separada en componentes, dominio, motor, servicios y estilos.

## Validación

Se realizaron comprobaciones estructurales y de TypeScript. La compilación de producción con Vite queda pendiente de ejecutarse en un entorno con acceso al registro de npm.
