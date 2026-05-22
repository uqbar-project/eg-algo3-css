<img src="./images/css-logo.png" alt="CSS Logo" height="20%" width="20%">

# Entorno

Si estás en entorno Windows te recomendamos instalarte [Git Bash](https://gitforwindows.org/)

# Editor de Texto: Visual Studio Code

El editor de texto que vamos a soportar en la cursada es [**Visual Studio Code**](https://code.visualstudio.com/) (hay [una versión portable](https://sourceforge.net/projects/vscode-portable/) si estás en una máquina sin privilegios de administrador).

Dentro de Visual Studio Code, te recomendamos que crees un perfil vacío y lo asocies a tus nuevos proyectos CSS (podés ver [cómo se trabaja con perfiles en VSCode en este video](https://www.youtube.com/watch?v=_2F2Zt-_tUA). También te dejamos [este tutorial muy piola - en inglés](https://www.youtube.com/watch?v=QjvvqR9KyVo) y [la documentación oficial](https://code.visualstudio.com/docs/editor/profiles)).

## Instalación

### Importar extensiones

Podés importar [este archivo que trae todas las extensiones para CSS](./css.code-profile)

### Instalación manual

Si querés instalar las extensiones manualmente, para 2026 te recomendamos las siguientes:

- **Live Preview - Microsoft**: Levanta un servidor local dentro de VS Code o en tu navegador externo y refresca automáticamente ante cualquier cambio. ¡Es súper estable y oficial!
- **CSS Peek - Pranay Prakash**: Permite encontrar y editar las definiciones de estilos directamente desde el HTML (con `F12` o `Cmd + Click` / `Ctrl + Click`).
- **IntelliSense for CSS class names in HTML - Zignd**: Te ofrece autocompletado inteligente para clases CSS en tus archivos HTML.
- **Image preview - Kiss Tamás**: Muestra una previsualización de las imágenes en el margen izquierdo del editor de código cuando las referenciás.

### Configuraciones recomendadas (sin extensiones)

En lugar de instalar extensiones adicionales, te recomendamos activar y verificar estas características que ya vienen integradas en VS Code. 

Para configurarlas, abrí la configuración global (`Ctrl` + `,` en Windows/Linux o `Cmd` + `,` en Mac):

#### 1. Auto Rename Tag (Linked Editing)
Permite renombrar una etiqueta HTML (tanto la de apertura como la de cierre) y que la otra se actualice automáticamente en tiempo real.
- **Desde la interfaz gráfica:** Buscá `Linked Editing` en la barra de búsqueda de la configuración y tildá la casilla **Editor: Linked Editing**.
- **Desde el archivo `settings.json`:** Agregá la siguiente línea:
  ```json
  "editor.linkedEditing": true
  ```

#### 2. Bracket Pair Colorization (Coloreado de llaves y paréntesis)
Te ayuda a identificar visualmente qué llave, corchete o paréntesis cierra con cuál mediante distintos colores. Aunque en las versiones modernas de VS Code ya viene activado por defecto, podés verificarlo:
- **Desde la interfaz gráfica:** Buscá `Bracket Pair Colorization` y asegurate de que **Editor › Bracket Pair Colorization: Enabled** esté marcado (o configurado en `true`).
- **Desde el archivo `settings.json`:** Agregá la siguiente línea:
  ```json
  "editor.bracketPairColorization.enabled": true
  ```

![Bracket colorization VSC setting](/images/bracket-colorization.png)


### Control de Versiones (Git)

VS Code tiene soporte nativo excelente para Git (en la pestaña de Source Control), por lo que no necesitás instalar extensiones adicionales para realizar commits, push o pull. Si querés ver el historial de commits de forma visual, podés instalar opcionalmente **Git Graph - mhutchie**, que es muy intuitivo.

# Alternativa a Visual Studio Code

## Web Storm

Otra opción es utilizar [Web Storm](https://www.jetbrains.com/webstorm/) (de la suite de IntelliJ), si tienen una cuenta de la facultad pueden solicitar una licencia educativa. Solo que como no vamos a aprovechar todas las herramientas de este IDE poderoso quizás convenga ir por el Visual Studio Code.

## Trabajo online

Si tenés ganas de practicar fuera del TP, podés trabajar directamente desde el navegador con [CodePen](https://codepen.io/), o bien probar [Prepros](https://prepros.io/)
