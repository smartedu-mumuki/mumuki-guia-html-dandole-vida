Como vimos antes, las direcciones son una parte fundamental de **flexbox** ya que mediante la propiedad `flex-direction` de tipo `column` o `row` nos permite definir la dirección en la que diseñamos nuestro CV.

**Encontremos cuantas direcciones tenemos.**

Si tomamos el eje central, podemos ver que nuestra `.section` es una columna en la que apilamos 4 diferentes areas, `.header`, `.navbar`, `.container` y `.footer`. Entonces tenemos una dirección principal `flex-direction: column;`

Sin embargo si tomamos el eje horizontal de cada una de nuestras areas, los elementos o tags que se encuentran dentro de cada una se agrupan de manera horizontal, por ejemplo nuestro menú no aparece un botón arriba del otro, sino que están uno al lado del otro, eso se debe a dirección lineal. Eso significa que nuestra areas tienen una `flex-direction: row;`.

**Pero ahora veamos más en detalle.**

Ya tenemos la dirección principal del CV y de cada una de las áreas, pero si se fijan bien la dirección de nuestro `.aside` y `.curriculum` tienen un eje vertical, es decir cambian nuevamente de dirección y apilan los elementos uno arriba del otro, lo que nos muestra que estos contenedores tienen una `flex-direction: column;`.





