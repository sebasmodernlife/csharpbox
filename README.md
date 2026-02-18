⚠️ Este proyecto se encuentra actualmente en estado Alpha.

**csharpbox** es una herramienta CLI para sistemas Unix-like que genera entornos de desarrollo containerizados para programar en .NET usando Neovim + LazyVim.

Su objetivo es permitir un flujo de trabajo reproducible y aislado, reutilizando tu configuración personal de Neovim sin que el contenedor modifique tu sistema host.

La herramienta automatiza la creación del entorno y permite parametrizar aspectos como:

- Nombre del proyecto
- Versión del SDK de .NET
- Puertos de desarrollo
- Bootstrap inicial de APIs
- Tooling y dependencias aisladas por proyecto

Diseñado para developers que prefieren un workflow terminal-first y una experiencia similar a devcontainers, pero centrada en Neovim.
