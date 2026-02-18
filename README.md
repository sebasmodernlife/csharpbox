# csharpbox

Neovim-first .NET devcontainers for macOS and Linux.

⚠️ **Estado actual:** Alpha (en desarrollo activo).

## ¿Qué es csharpbox?

**csharpbox** es una herramienta CLI para sistemas Unix-like que genera entornos de desarrollo containerizados para programar en .NET utilizando **Neovim + LazyVim**, manteniendo intacta la configuración personal del usuario.

El objetivo es ofrecer un entorno reproducible, portable y aislado, similar a un devcontainer, pero diseñado específicamente para workflows terminal-first y usuarios de Neovim.

## ✨ Características principales

- Creación automática de proyectos .NET (Web API incluida)
- Entorno completamente aislado mediante Docker
- Uso de tu configuración personal de Neovim (sin modificar el host)
- Plugins y LSPs instalados dentro del contenedor
- Hot reload y ejecución accesible desde el navegador
- Tooling y caches aislados por proyecto
- Configuración parametrizable:
  - Nombre del proyecto
  - Versión del SDK de .NET
  - Puerto de desarrollo
  - Bootstrap inicial del proyecto

## 🎯 Objetivo del proyecto

Reducir la fricción al iniciar proyectos .NET en Linux/macOS y facilitar un entorno consistente entre distintas máquinas, priorizando:

- Developer Experience (DX)
- Reproducibilidad
- Portabilidad
- Flujo de trabajo basado en terminal

## 🚧 Estado actual

csharpbox está en fase Alpha.  
El foco actual es estabilizar el workflow base antes de publicarlo como proyecto open source.

Feedback y sugerencias son bienvenidos.
