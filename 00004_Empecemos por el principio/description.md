Ahora que tenemos nuestro contenedor flexible empecemos por el principio, el `header`.

Si vemos el diseño podemos ver que tenemos un titulo con el nombre, que llamaremos `.cv_name` y dentro del `.header` un fondo de color que ocupa el 50% del ancho.

Para lograr este efecto vamos a comenzar por el `.header` y creamos una propiedad `height: 200px;` y para el efecto de color hasta la mitad, la propiedad `background` posee un valor de tipo `linear-gradient`, que nos deja hacer este efecto declarando el angulo, color inicial y color final, de esta manera `linear-gradient(90deg, #fff 50%, #50acef 50%);`.

Ejercicio:
> Con el selector `.header` vamos crear un `height: 200px;` y le vamos a dar un fondo `background: linear-gradient(90deg, #fff 50%, #50acef 50%);`