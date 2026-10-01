# 🎃 La Krypta del Cementerio Maldito (Halloween 31-Day Advent Calendar)

Hub principal del **Calendario de Adviento de Halloween de 31 Días**, inspirado en la estética de la **Krypt de Mortal Kombat (PlayStation 2)**.

Diseñado para ser alojado como un **único repositorio maestro en GitHub Pages**.

---

## 🚀 Despliegue en GitHub Pages

1. Inicializa este directorio como repositorio de Git o súbelo a tu repositorio en GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Krypta Advent Calendar Hub"
   git remote add origin https://github.com/<tu-usuario>/<tu-repo>.git
   git push -u origin main
   ```
2. En GitHub, ingresa a **Settings** > **Pages**.
3. En **Build and deployment** > **Source**, elige `Deploy from a branch`.
4. Selecciona la rama `main` y la carpeta `/ (root)`.
5. Haz clic en **Save**. ¡Tu calendario estará en línea en `https://<tu-usuario>.github.io/<tu-repo>/`!

---

## 🎵 Estructura de Audio MP3 Reemplazable

El proyecto incluye soporte directo para archivos `.mp3` en la carpeta `/audio/`:

| Archivo | Función | Descripción recomendada |
|---|---|---|
| `audio/ambient.mp3` | Música / Sonido de fondo | Viento nocturno de cementerio, cuervos lejanos, órgano fúnebre. |
| `audio/hover.mp3` | Efecto on-hover | Susurro espectral, resonancia de piedra hueca, viento fino. |
| `audio/click.mp3` | Efecto on-click | Golpe pesado de losa de cripta, portazo gótico de hierro. |

> **Respaldo de Sonido Automático (Web Audio API):** Si los archivos `.mp3` aún no han sido colocados en la carpeta `audio/`, el motor sintetiza los sonidos proceduralmente por software en tiempo real. ¡El hub nunca se quedará mudo durante las pruebas!

---

## 🔮 Funcionalidades del Landing Hub (Fase 1)

1. **Cuadrícula de 31 Lápidas (Krypt Style)**:
   - Formato gótico con números romanos de fondo, textura de piedra agrietada y títulos de maleficios.
   - **Día en curso**: Iluminada con fuego espectral verde/dorado, runas pulsantes y antorchas encendidas.
   - **Días anteriores**: Desbloqueados, rejugables todas las veces que el usuario desee.
   - **Días futuros**: Sellados con cadenas de hierro y candados oscuros.
2. **Visión del Oráculo (Simulador de Fecha)**:
   - Selector en la barra superior para alternar entre la **Fecha Real** del sistema o **forzar cualquier día del 1 al 31** para probar instantáneamente cómo se ven las lápidas de hoy, del pasado y del futuro.
3. **Cámara de Inspección de la Cripta (Modal)**:
   - Al hacer clic en cualquier lápida disponible, se reproduce el sonido de cripta y se abre una ficha detallada con el nombre del juego, la mecánica clásica inspirada y su descripción de lore.
   - El botón de inicio permanece en modo prueba para que puedas validar la calidad visual y auditiva antes de ir conectando juego por juego.

---

## 📜 Catálogo de los 31 Juegos Planificados

| Día | Título Temático | Mecánica Clásica |
|:---:|:---|:---|
| **01** | El Ojo del Nigromante | *Simon Says / Memoria Audiovisual* |
| **02** | Cripta de las Bestias | *Whack-a-Mole* |
| **03** | Almas en Fila | *4 en Raya (Connect 4)* |
| **04** | Poción de Baba | *Tetris / Caída de bloques* |
| **05** | Burbujas del Caldero | *Puzzle Bobble* |
| **06** | Escape del Laberinto | *Pac-Man* |
| **07** | Parejas Malditas | *Memory Card Flip* |
| **08** | Cazador de Sombras | *Buscaminas (Minesweeper)* |
| **09** | Flappy Bat | *Flappy Bird* |
| **10** | Torre de Cráneos | *Tower Stacker* |
| **11** | Rune Match 3 | *Match-3 (Candy Crush)* |
| **12** | Cruce del Río Estigia | *Frogger* |
| **13** | El Salto de la Gárgola | *Doodle Jump* |
| **14** | 2048: Cráneos Arcanos | *2048 Puzzle* |
| **15** | Tiro a la Bruja | *Duck Hunt* |
| **16** | Desliza la Tumba | *15-Puzzle (Sliding Tile)* |
| **17** | El Péndulo de la Muerte | *Timber / Lumberjack* |
| **18** | Pinball de Nosferatu | *Pinball Clásico* |
| **19** | El Espejo de las Ánimas | *Lights Out* |
| **20** | Corta las Raíces | *Fruit Ninja* |
| **21** | Defensa del Bastión | *Tower Defense Mini* |
| **22** | Criptograma del Demonio | *Cryptogram Puzzle* |
| **23** | Duelo Espectral | *Pong / Air Hockey* |
| **24** | El Descenso al Abismo | *Downwell* |
| **25** | Catapulta de Huesos | *Angry Birds / Scorched* |
| **26** | Pesadilla Eterna | *Dino / Endless Runner* |
| **27** | El Ahorcado del Pantano | *(Existente)* *Hangman* |
| **28** | Autopista del Averno | *(Existente)* *Vertical Racing* |
| **29** | Invasión de Ultratumba | *(Existente)* *Space Invaders* |
| **30** | Ciempiés de Sangre | *(Existente)* *Snake* |
| **31** | Rompe-Catacumbas (Gran Final) | *(Existente)* *Arkanoid* |
