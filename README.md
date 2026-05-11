# Exercise - Git and GitHub - Little Red Riding Hood

## Descripción

El objetivo de este ejercicio es practicar **cuándo y por qué** se realizan los commits, aplicando buenas prácticas de control de versiones. Deberás contar una historia clásica mediante código, prestando especial atención al historial (Git Graph) de tu repositorio.

## Instrucciones

1. Crea un repositorio en GitHub llamado `ex-git-little-red-riding-hood` (o `ex-git-three-little-pigs` si prefieres esa historia. También puedes elegir otro cuento según tu preferencia).
2. **Planificación**: Utiliza Stitch (o herramienta similar) para prototipar tu historia. Antes de programar, analiza y planifica qué commits vas a realizar. Explica en el Readme tu analizis y tu planificación.
3. **Desarrollo**:
   - Cuenta la historia de Caperucita Roja mediante **HTML**. (División clara entre momento claves o capítulos)
   - Añade estilos y diseño con **CSS**.
   - Enriquece la historia con imágenes.
4. **Control de Versiones**: Realiza los commits pertinentes y súbelos al repositorio. **Importante**: El *cuándo* se hace el commit es clave.
5. **Despliegue**: Activa **GitHub Pages** para visualizar el resultado.

## Buenas Prácticas para Commits

Para superar este ejercicio con éxito, aplica estas reglas en tu flujo de trabajo:

- **Atomicidad**: Cada commit debe resolver una única tarea lógica (ej: "Crear estructura HTML básica", "Añadir estilos al header"). No mezcles cambios de diferentes contextos en un solo commit.
- **Mensajes Descriptivos**: El mensaje debe explicar *qué* hace el commit y el *por qué* de los cambios, en lugar del *cómo*. Usa imperativo (ej: `feat: add navigation bar` o `style: change background color`).
- **Frecuencia**: Haz commit a menudo. No esperes a terminar todo el proyecto. Si algo funciona, haz commit.
- **Convenciones**: Usar *Conventional Commits* (prefijos como `feat:`, `fix:`, `docs:`, `style:`) para mantener el historial ordenado. [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#summary)

## Requisitos Técnicos

- Uso de HTML5 y CSS3.
- Despliegue funcional en GitHub Pages.

## Entregables

- Enlace al repositorio de GitHub.
- Enlace a la página desplegada en GitHub Pages.
- Una captura de pantalla del resultado final (visible en el `README.md` del repositorio).

---


|   Nivel                            | Descripción del desempeño                                                                                      | Puntuación |
|------------------------------------|----------------------------------------------------------------------------------------------------------------|------------|
| Ejercicio no entregado | No se entrega repositorio, no hay código, o no existe ninguna contribución real en el historial de commits.                |	0 pts      |
| Ejercicio no cumple con un mínimo. | El repositorio existe pero no cumple los requisitos mínimos: historia incompleta, HTML o CSS insuficientes, commits escasos o mal estructurados, README pobre o inexistente, sin despliegue en GitHub Pages. | 40 pts |
| Ejercicio cumple con un mínimo pero falla en ciertos aspectos | La historia está contada en HTML, hay estilos CSS básicos, imágenes añadidas, commits realizados con cierta lógica, README funcional, y GitHub Pages activado. Sin embargo, faltan buenas prácticas claras, planificación insuficiente o commits poco atómicos. | 70 pts |
| Ejercicio  completo y con todos los requisitos implementados | Historia completa en HTML con capítulos claros, CSS trabajado, imágenes integradas, planificación explicada en el README, commits atómicos y bien descritos siguiendo Conventional Commits, historial limpio, despliegue en GitHub Pages funcional, y README bien redactado con captura final. | 100 pts |



#Project: Three Little Pigs

##Project Structure & Planning
This version of The Three Little Pigs is specially written for easy reading and accessibility. We use simple words, short sentences, and a clear structure to make the story enjoyable for everyone.

**Chapter 1:** The Big Decision
**Chapter 2:** Straw, Sticks, and Bricks
**Chapter 3:** The Hungry Wolf
**Chapter 4:** Safe at Last

* **Tech stack:**HTML and CSS

###Accessibility & Design
To ensure this story is accessible to a larger variety of readers I implemented:
*  **All images and non-text elements  have equivalent text alternatives 
*  **Font choice: Straw, Sticks, and Bricks/dyslexia-friendly tyopography
*  **Readability: Large font sizes (20px) and wide line spacing (1,6)
*  **Visual Comfort: High-contrast colors (cream background) to reduce eye strain.

###·Project design & Wireframe
* **Design:** 
![Chapter 1 The Big Decision](docs/img/initial%20design/Screenshot%20Chapter%201%20the%20Big%20decision.jpg)
![Chapter 2 Straw, Stricks and Bricks](docs/img/initial%20design/Screenshot%20Chapter%202%20Straw%20Sticks%20and%20Bricks.jpg)
![Chapter 3 Hungry Wolf](docs\img\initial design\Screenshot Chapter 3 Hungry Wolf.jpg)
![Chapter 4 Safe at least](docs\img\initial design\Screenshot Chapter 4 Safe at least.jpg)
![Chapter 3 Hungry Wolf](docs/img/initial%20design/Screenshot%20Chapter%203%20Hungry%20Wolf.jpg)
![Chapter 4 Safe at least](docs/img/initial%20design/Screenshot%20Chapter%204%20Safe%20at%20least.jpg)


* **Wireframe:**
![Initial wireframe](docs/img/initial%20design/Screenshot%20initial%20wareframe.jpg)
###Commit Planning
 * **Setup:**
    - "feat": add giltignore
    - "feat": add initial HTML, initial CSS
   
* **Docs:/ ** 
   -   "docs": add project documents
   
	
* **Chapters:**
   - "feat": add structure and styling for main title "The Threee Little pigs"

	- "feat": add structure and styling for header "Chapter 1 The Big Decision"
	- "feat": add structure and styling for figure of Chapter 1
	- "feat": add structure and styling for content/paragraph of Chapter 1
	- "feat": add structure and styling for header  "Chapter 2 Straw, Sticks and Bricks"
	- "feat": add structure and styling for  figure of "The Straw House "
	- "feat": add structure and styling for sub-header "The Straw House "
	- "feat": add structure and styling for content/paragraph of "The Straw House "
	- "feat": add structure and styling for  figure of "The Stick House "
	- "feat": add structure and styling for sub-header "The Stick House "
	- "feat": add structure and styling for content/paragraph of "The Stick House "
	- "feat": add structure and styling for  figure of "The Brick House "
	- "feat": add structure and styling for sub- header "The Brick House "
	- "feat": add structure and styling for content/paragraph of "The Brick House 
   - "feat": add structure and styling for header  "Chapter 3 The Hungry Wolf"
   - "feat": add structure and styling for  figure of "Chapter 3 The Hungry Wolf "
   - "feat": add structure and styling for the first content/paragraph of "Chapter 3 The Hungry Wolf "
   - "feat": add structure and styling for quote "Little pig, little pig, let me come in! "
   - "feat": add structure and styling for second content/paragraph of "Chapter 2 The Hungry Wolf "
   - "feat": add structure and styling for third content/paragraph of "Chapter 2 The Hungry Wolf "
   - "feat": add structure and styling for header  "Chapter 4 Safe at Last"
   - "feat": add structure and styling for figure of "Chapter 4 Safe at Last"
   - "feat": add structure and styling for content/paragraph of "Chapter 4 Safe at Last"
   - "feat": add structure and styling for footer of "Chapter 4 Safe at Last"

