# Mi Proyecto Web

Sitio web sencillo en HTML creado para practicar Git y GitHub. Incluye navegación por secciones y un formulario de contacto de ejemplo.

## Contenido

- [Descripción](#descripción)
- [Instalación](#instalación)
- [Estructura](#estructura)
- [Mejoras implementadas](#mejoras-implementadas)
- [Flujo de trabajo](#flujo-de-trabajo)

## Descripción

La página se puede abrir directamente en un navegador. El formulario es únicamente una estructura HTML y no envía datos.

## Instalación

Clona el repositorio y abre `index.html` en tu navegador:

```bash
git clone https://github.com/dariorivasg/proyecto-git.git
cd proyecto-git
```

## Estructura

- `index.html`: contenido y estructura de la página.
- `.gitignore`: excluye `.vscode/` y archivos temporales comunes.
- `README.md`: documentación del proyecto.

## Mejoras implementadas

- Menú de navegación con enlaces internos a Inicio, Información y Contacto.
- Formulario de contacto con campos de nombre, correo electrónico y mensaje.

## Flujo de trabajo

Las mejoras se desarrollaron en ramas independientes y se integraron en `main` mediante Pull Requests:

- `feature/menu` → [Pull Request #1](https://github.com/dariorivasg/proyecto-git/pull/1)
- `feature/formulario-contacto` → [Pull Request #2](https://github.com/dariorivasg/proyecto-git/pull/2)
