# Lyft

* **HTML:**

Al igual que con `freelancer` comenzaré explicando el código del `HTML`para hacerlo más ordenado. 

Comienzo con el titulo de la pestaña, lo saqué de la página original ya que crei que solo "lyft" se veria muy simple. 
En seguida linkee el archivo css, la fuente y los iconos de icomoon. 

Para la barra de navegacion cree un `header` y una `nav-bar` en el `nav` hay unas `a`que son las que tienen los botones o links a Drive, Explore y Help, dentro de este `nav`cree una etiqueta `button`para incluir el botón `log in`.

Terminando con la barra de navegacion, cree una seccion para poder incluir el `gif`de Lyft y el logo. Para lograr esto cree un `div`contenedor, el que incluye la imagen de fondo, el logo y ademas el formulario para los drivers. Ya que dentro de esta seccion del formulario hay unos titulos, lo que hice fue crear unos `div`y dentro de ellos unos `p`para poder posicionarlos de manera más fácil. Creé otro div para poder incluir el formulario, dentro del div hay dos botone, uno tiene fondo y el otro no, explicare esto cuando detalle el `css`.Bajo el formulario hay un pequeño texto, esto lo hice por medio de dos `p`, para que asi quedara uno en cada linea.

Cree una nueva seccion, la que corresponde al telefono celular (le llamo asi ya que es la imagen con que lo distingo). En esta seccion cree un `div`contenedor para asi poder incluir los textos y los titulos, todos los titulos de esta seccion estan creados por medio de un `h3`y las lineas que van debajo estan conformadas por `p`. Cree un `div`aparte para la imagen del telefono celular. 

La ultima seccion corresponde a los videos y los parrafos de texto que se encuentran a sus lados. 
Para poder lograr esto cree un `div`contenedor para los parrafos y para los videos tambien cree `divs`contenedores, asi me costo menos poder posicionarlos de la forma correcta. Los parrafos y titulos pequeños y grandes de esta seccion, estan conformados por etiquetas `p` y los videos fieron insertados con la etiqueta `iframe`, modifique un poco estas etiquetas ya que venian con el ancho y alto del video de forma predeterminada, pense que se veia desordenado y puse esas caracteristicas en el CSS. 

Para finalizar, cree una etiqueta `footer`y dentro de esta etiqueta footer genere un `div` con el id `footer-container` para asi poder ordenar mejor los elementos, para poder poner las tres lineas de texto utilice un `div`que corresponde a `footer-list`y dentro de este div una `ul` los titulos de estos parrafos fueron insertados con etiquetas `h4`.

Para poder posicionar los banner, cree un `div`contenedor y dentro de este div contenedor cree una nueva lista, en la que van incluidas las imagenes de los bamner, en el caso de las redes sociales los iconos fueron insertados por medio de `icomoon`y tambien dentro de una `ul`

Para poder incluir la linea debajo de los iconos de redes sociales, cree un `div`y dentro de este div una etiqueta `hr`

Y para terminar el footer cree el ultimo `div`y dentro puse un `p`con el texto del copyright. 


* **CSS:**

Para comenzar utilice un selector universal para poder dar un `margin`y `padding`de 0 a toda la página y hacer que no se vieran espacios en blanco. 

Para aplicarle los estilos al `header`utilice solo el nombre y asi le asigne un color de fondo y ademas de ancho. 

Para el menu de navegacion lo que hice fue darle estilos por medio de la `a`con eso pude seleccionar todos los links de esta seccion y asi darles estilo a todos juntos, le saque la linea de abajo con `text-decoration:none`y con `display: inline-block`hice que todo se comportara como elemento en linea, para asi poder posicionarlo de manera más facil.

`.log-in`corresponde al boton de su mismo nombre, este está ubicado dentro de la barra de navegacion, utilice un boton para poder darle estilos y que se viera más parecido a la página original.

`#lyft-container`este id tiene ese nombre ya que contiene todo lo que se refiere a lyft, osea su imagen de fondo y su logo, le da el fondo de color blanco al formulario ademas.

`#lyft-image`corresponde a la imagen `.gif`de lyft, la que va en el fondo. 

`#logo` es el logo de lyft, esta posicionado encima de la imagen, al lado superior izquierdo. 

`#form-section`cree este id para poder darle estilos al formulario. 

`div #subtitle p` debajo del titulo donde se encuentra el formulario hay un texto más pequeño, este id le da los estilos a este texto. 

`div input[type=text]`con este selector estoy dandole estilos al formulario completo. 

`#driver`corresponde al boton become a driver.

`#sign p`corresponde al boton sign up to ride, todos los estilos que utilice fueron para que no tuviera fondo y pareciese mas un link que un boton.

`#already, #earn`estos id le dan estilos al parrafo pequeño que se encuentra debajo del formulario. 

`div #already` con este id lo que hice fue posicionar el parrafo pequeño que se encuentra debajo del formulario, `div #earn`realiza la misma accion, pero para la segunda linea de texto. 

`#phone-container` corresponde al fondo que se encuentra en gradiente, este fondo lleva dentro la imagen del telefono y los textos del lado izquierdo. 

Con `h3`di estilos a todos los titulos h3 de la seccion del telefono. 

`#ride` `#request` `#repeat``#serious` `#knowing` `#trust` `#happy-drivers` `#happy-riders` `#with` y `#five`corresponden a todo el texto que se encuentra del lado izquierdo de la seccion a la que llamo "del telefono".

`#phone-image`corresponde a la imagen del telefono, que se encuentra al lado derecho de la seccion. 

`#youtube-videos`creé este id para poder darle el fondo a esta seccion y ademas para poder contener el texto que llevaba cada uno de los videos. 

`#text1-container`contiene el texto que va al lado del primer video. 

`#watch`dentro de esta seccion hay 3 titulos pequeños con la leyenda watch, para todos use un id con el que le di un tamaño de 10px. 

`#amplify`debajo del pequeño titulo hay uno mas grande, por esto cree este id, para darle estilos por separado. 

`#text-p`corresponde al parrafo mas extenso que se encuentra al lado del video, la p es porque estan dentro de varias p, para que queden en una linea cada uno. 

Lo que hace `iframe` es darle estilos a los tres videos de esta seccion. 
`#video1``#video2` y `#video2` son los estilos de los enlaces de youtube. 

mas abajo solamente cambie los nombres de los id, pero hacen lo mismo que `watch`y el resto, solamente cambian de nombre. 

`footer`corresponde a la seccion del pie de pagina, al llamar a footer lo que hice fue darle el color de fondo y ademas dejarlo como el contenedor de las listas que se encuentran en el, con listas me refiero a las listas de texto, a los iconos y a los banner, ya que para poder posicionarlas en forma vertical cree solo listas. 

`h4` le da los estilos a todos los titulos h4 del footer. 

`ul`da el estilo de fuente, el color y la posicion de esta. 

`li` por medio de li tambien di el estilo de fuente, el color y ademas su posicion. 

`#footer-list a`le da los estilos a todas las etiquetas `a`del footer, de este modo selecciono todo. 

`a:hover`esto hace que al pasar el mouse por encima de las listas, estas cambien de color, solamente cambiara el color del texto, no su fondo. 

`#footer-list-container` por medio de este id, seleccione todas las listas del footer a la vez, para asi poder posicionarlas de una forma mas facil. 


al llamar a `li img` le doy la posicion y tamaño a las imagenes de los banner. 

Con `#banners` lo que hice fue darle posicion y dejar el cursor como pointer. 

`#redes-sociales` le da los estilos a los iconos de estas. 

`#redes-sociales li` por medio de este llamado lo que hice fue hacer la circunferencia que rodea los iconos. 

`#redes-sociales a` de esta forma lo que hice fue posicionar los iconos, ya que quedaban fuera de la circunferencia. 

`#line hr`corresponde a la linea que va bajo los iconos de redes sociales. 

`#copyright`corresponde al texto pequeño que se encuentra al final de la pagina. 









