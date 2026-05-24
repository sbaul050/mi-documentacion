# Guía de Inicio rápido
Bienvenido a la documentación principal. Aquí encontrarás enlaces directos y contenido introductorio sobre la instalación, configuración y despliegue de tu proyecto.

## Navegación principal
- [Guía de Instalación](guia/instalacion.md)
- [Configuración](guia/configuracion.md)
- [Despliegue](guia/despliegue.md)

---

## ¿Qué incluye esta documentación?
Este índice te ayuda a encontrar rápidamente los pasos para poner en marcha tu proyecto con MkDocs y GitHub Pages.

- Instalación: cómo instalar las dependencias básicas y preparar el entorno.
- Configuración: cómo definir la estructura del sitio, el tema y las opciones de MkDocs.
- Despliegue: cómo publicar tu sitio estático en GitHub Pages con un workflow automatizado.

## Resumen de secciones
### 1. Guía de Instalación
En la página de instalación verás:
- Requisitos previos de software.
- Instalación de Python y MkDocs.
- Instalación del tema `mkdocs-material`.
- Comandos para verificar que todo funciona.

### 2. Configuración
En la página de configuración verás:
- Cómo crear y editar `mkdocs.yml`.
- Definición del nombre del sitio y la navegación.
- Configuración del tema, los plugins y los enlaces.
- Cómo organizar las páginas dentro de `docs/`.

### 3. Despliegue
En la página de despliegue verás:
- Creación del workflow en `.github/workflows/deploy.yml`.
- Uso de `actions/checkout`, `actions/setup-python` e instalación de dependencias.
- Comando `mkdocs gh-deploy --force` para publicar en GitHub Pages.
- Consejos para mantener el sitio actualizado en cada `push` al branch principal.

## Primeros pasos rápidos
1. Abre el archivo `mkdocs.yml` y verifica que el sitio esté configurado correctamente.
2. Asegúrate de que tus páginas están dentro de `docs/`.
3. Confirma que el workflow existe en `.github/workflows/deploy.yml`.
4. Haz un `commit` y `push` a la rama `main` para activar el despliegue automático.

## Por qué es importante
Tener un índice claro y enlaces directos al proceso completo te ayuda a mantener la documentación organizada y facilita el trabajo en equipo. Esta página funciona como punto de entrada para cualquier persona que deba instalar, configurar o publicar el sitio.

> Si necesitas, también puedo ayudarte a crear el contenido completo de `guia/instalacion.md`, `guia/configuracion.md` y `guia/despliegue.md`.
