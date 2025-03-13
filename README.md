# Mi Proyecto de Portafolio

Este es el README para mi proyecto de portafolio. Aquí encontrarás información sobre cómo configurar y ejecutar el proyecto.
![Shots Mockup 1x](https://github.com/user-attachments/assets/62c5701e-5074-4352-916c-ab9ee4ee3b85)

## 🚀 Comenzando

Para comenzar con este proyecto, clona el repositorio y navega a la carpeta del proyecto:

```sh
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
```

## 📦 Instalación

Instala las dependencias necesarias utilizando `bun`:

```sh
bun install
```

## 🧑‍💻 Desarrollo

Para iniciar el servidor de desarrollo, ejecuta:

```sh
bun dev
```

El servidor de desarrollo estará disponible en `http://localhost:4321`.

## 🏗️ Construcción

Para construir el sitio para producción, ejecuta:

```sh
bun build
```

Los archivos de producción se generarán en la carpeta `./dist/`.

## 👀 Vista previa

Para previsualizar tu sitio de producción localmente, ejecuta:

```sh
bun preview
```

## 📂 Estructura del Proyecto

Dentro de tu proyecto, verás los siguientes archivos y carpetas:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Para aprender más sobre la estructura de carpetas de un proyecto Astro, consulta [nuestra guía sobre la estructura del proyecto](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `bun install`             | Instala las dependencias                         |
| `bun dev`                 | Inicia el servidor de desarrollo en `localhost:4321` |
| `bun build`               | Construye tu sitio de producción en `./dist/`    |
| `bun preview`             | Previsualiza tu construcción localmente          |
| `bun astro ...`           | Ejecuta comandos CLI como `astro add`, `astro check` |
| `bun astro -- --help`     | Obtén ayuda usando el CLI de Astro               |

## 👀 ¿Quieres aprender más?

Siéntete libre de consultar [nuestra documentación](https://docs.astro.build) o unirte a nuestro [servidor de Discord](https://astro.build/chat).
