# PoketDex

PoketDex es una aplicación de escritorio ligera y autónoma que te permite:

- Consultar información de todos los Pokémon de la primera generación de forma **offline**  
- Jugar minijuegos como **Wordle** (5 letras) y **Adivina el Pokémon**  
- Construir equipos y analizar debilidades/fortalezas  
- Guardar favoritos y ver estadísticas de tus partidas  
- Internacionalización (español & inglés)

---

## 📦 Tecnologías

| Capa        | Tecnología                                |
|-------------|-------------------------------------------|
| Lenguaje    | Java 17                                   |
| Build       | Maven + Maven Wrapper (`mvnw` / `mvnw.cmd`) |
| Framework   | Spring Boot 3.5.3 (Core + Data JPA)       |
| Base de datos | H2 embebida (persistente en `./data/`) |
| UI          | JavaFX 21 (Controls + FXML)               |
| Testing     | JUnit 5 + Spring Boot Starter Test + Mockito |
| Logging     | SLF4J + Logback                           |
| i18n        | `messages_en.properties`, `messages_es.properties` |

---

## 🚀 Requisitos

- JDK 17 instalado y en `PATH`  
- Maven (o usar `./mvnw`)  
- (Opcional) Scene Builder para editar los `.fxml`  
- Git para clonar y versionar

---

## 🛠️ Estructura del proyecto

```text
PomketDex/
├─ pom.xml
├─ mvnw*  mvnw.cmd*  .mvn/
├─ src/
│  ├─ main/
│  │  ├─ java/com/nubafri/poketdex/
│  │  │   ├─ config/        ← Configuración Spring & beans
│  │  │   ├─ model/         ← Entidades JPA
│  │  │   ├─ repository/    ← Repositorios Spring Data
│  │  │   ├─ service/       ← Lógica de negocio
│  │  │   └─ ui/
│  │  │       └─ controller ← Controladores JavaFX (@FXML)
│  │  └─ resources/
│  │      ├─ application.properties
│  │      ├─ init.sql
│  │      ├─ fxml/          ← Vistas FXML
│  │      ├─ css/           ← Estilos CSS
│  │      └─ i18n/          ← messages_*.properties
│  └─ test/                 ← Pruebas JUnit & Mockito
└─ docs/
   ├─ requisitos.md
   └─ checklist_requisitos.md
