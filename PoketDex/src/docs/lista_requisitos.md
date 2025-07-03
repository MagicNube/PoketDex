# Requisitos del Proyecto PoketDex Desktop

## Requisitos Funcionales (RF)

| ID   | Requisito                                                       | Prioridad | Comentarios                                                                     |
|------|-----------------------------------------------------------------|-----------|---------------------------------------------------------------------------------|
| RF01 | Pokédex con Pokémon de la primera generación.                   | Alta      |                                                                                 |
| RF02 | Mostrar vista detallada de un Pokémon.                          | Alta      |                                                                                 |
| RF03 | Minijuego wordle con Pokémon de 5 letras.                       | Alta      |                                                                                 |
| RF04 | Adivinar el Pokémon con pistas.                                 | Alta      | Falta definir atributos que se van a mostrar en la tabla de correcto/incorrecto |
| RF05 | Registrar juegos oficiales y romhacks.                          | Alta      | Información del juego y puntuación                                              |
| RF06 | Filtrar/buscar Pokémon en la Pokédex.                           | Media     |                                                                                 |
| RF07 | Teambuilder que muestre debilidades y fortalezas de tus equipo. | Media     |                                                                                 | 
| RF08 | Guardar Pokémon favoritos.                                      | Media     |                                                                                 |
| RF09 | Opciones extra en el wordle.                                    | Media     | El usuario puede elegir el número de letras.                                    |
| RF10 | Opciones extra en adivinar el Pokémon.                          | Media     | El usuario puede elegir si es por grito, sprite...                              |
| RF11 | Estadísticas de los minijuegos                                  | Baja      |                                                                                 |
| RF12 | Comparar stats de un Pokémon al lado de otro                    | Baja      |                                                                                 |
| RF13 | Internacionalización (i18n) para al menos español e inglés.     | Baja      |                                                                                 |

## Requisitos No Funcionales (RNF)

| ID    | Requisito                                                         | Detalle / Métrica                  |
|-------|-------------------------------------------------------------------|------------------------------------|
| RNF01 | Rendimiento                                                       | Tiempo de carga inicial < 3s       |
| RNF02 | Usabilidad                                                        | Interfaz basada en JavaFX MVC      |
| RNF03 | Logging                                                           | SLF4J + Logback configurado        |