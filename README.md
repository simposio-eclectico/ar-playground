# AR Playground

Este proyecto es una experiencia de realidad aumentada (AR) en la web, creada usando A-Frame y AR.js, y gestionada con Vite.

## Requisitos

- Node.js y pnpm instalados

## Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/simposio-eclectico/ar-playground
    cd ar-playground
    ```

2. Instala las dependencias:
    ```bash
    pnpm install
    ```

## Ejecución del Proyecto

Para iniciar el servidor de desarrollo, ejecuta:

```bash
pnpm run dev
```

Esto abrirá tu aplicación en `http://localhost:3000`.

## Estructura del Proyecto

- `index.html`: El archivo principal de la aplicación.
- `maxwell/scene.gltf`: El modelo 3D usado en la experiencia AR.
- `data/kanji.patt`: El archivo de patrón para la detección de marcadores AR.

## Despliegue

Para construir la aplicación para producción, ejecuta:

```bash
pnpm run build
```

Los archivos construidos estarán en la carpeta `dist`.

## Licencia

Este proyecto está bajo la Licencia MIT.