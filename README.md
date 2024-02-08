# 🚀 Automatización de Configuración con Rulesets 🛡️

## Configuración de BranchProtect

Este repositorio utiliza BranchProtect para establecer reglas y restricciones en el flujo de trabajo. A continuación se detallan las configuraciones clave:

### 🌟 Rama Feature

- Solo se permiten Pull Requests desde la rama `Feature` a la rama `Develop`.
  
### 🚀 Rama Develop

- La rama `Develop` es inmutable.
- Cambios a esta rama solo pueden realizarse a través de un Pull Request.

### 🎉 Rama Release

- Solo los TL (Líderes de equipo) tienen el privilegio de crear ramas `Release`.
- La rama `Release` es inmutable y no se puede modificar de ninguna manera.

### 📝 Comentarios de Commit

- Todos los comentarios para cada commit deben comenzar obligatoriamente con `AB#`.

### 🌲 Rama Main

- Solo se aceptan cambios en la rama `Main` provenientes de un Pull Request.
