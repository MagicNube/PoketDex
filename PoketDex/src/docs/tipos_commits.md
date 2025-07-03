# Guía de Tipos de Commits

Este documento recoge las convenciones de mensajes de commit basadas en **Conventional Commits**, para mantener un historial claro y consistente.

| Prefijo      | Descripción                                                                           | Ejemplo                                                     |
|--------------|---------------------------------------------------------------------------------------|-------------------------------------------------------------|
| **feat**     | Añade una nueva funcionalidad (“feature”).                                            | `feat: Implementar minijuego Wordle`                        |
| **fix**      | Corrige un error o bug.                                                               | `fix: Solucionar Null Pointer Exception al filtrar Pokémon` |
| **docs**     | Cambios en la documentación (README, guías, comentarios).                             | `docs: Actualizar sección de instalación`                   |
| **refactor** | Refactorización de código: modifica la estructura interna sin añadir funcionalidades. | `refactor: Extraer lógica de filtrado en PokemonService`    |
| **test**     | Añade o modifica pruebas (JUnit, Mockito…).                                           | `test: Añadir casos para PokemonService`                    |
| **build**    | Cambios en el sistema de build o en dependencias (pom.xml, scripts, etc.).            | `build: Actualizar Spring Boot a 3.5.3`                     |
| **chore**    | Tareas de mantenimiento general (gitignore, configuración IDE, limpieza de archivos). | `chore: Añadir .idea/scopes compartidos`                    |
| **revert**   | Revertir un commit anterior.                                                          | `revert: feat: Implementar teambuilder`                     |

