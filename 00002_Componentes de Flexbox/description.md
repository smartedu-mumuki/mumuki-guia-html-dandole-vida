**Contenedor flexible (Flex container)**
El elemento "padre" que contiene los elementos flexibles. Un contenedor flexible se define usando los valores flex o inline-flex en la propiedad display.

**Elemento flexible (Flex item)**
Cada hijo de un contenedor flex se convierte en un elemento flexible. Si hay texto directamente incluido en el contenedor flexible, se envuelve automáticamente en un elemento flexible anónimo.

**Ejes**
Cada diseño de "caja flexible" sigue dos ejes. El eje principal es el eje a lo largo del cual los elementos flexibles se suceden unos a otros. El eje secundario es el eje perpendicular al eje principal.

* La propiedad **flex-direction** establece el eje principal.
* La propiedad **justify-content** define cómo los elementos flexibles se disponen a lo largo del eje principal en la línea en curso.
* La propiedad **align-items** define cómo los elementos flexibles se disponen a lo largo del eje secundario de la línea en curso.
* La propiedad **align-self** define cómo cada elemento flexible se alinea respecto al eje secundario, y sustituye al valor por defecto establecido por align-items.

Direcciones
Los lados inicio principal/fin principal (main start/main end) e inicio secundario/fin secundario (cross start/cross end) del contenedor flexible describen el origen y final del flujo de los elementos flexibles. Estos siguen los eje principal y secundario según el vector establecido por writing-mode (izquierda-a-derecha, derecha-a-izquierda, etc.).

* La propiedad order asigna elementos a grupos ordinales y determina qué elementos aparecen primero.
* La propiedad flex-flow property combina las propiedades flex-direction y flex-wrap para colocar los elementos flexibles.

