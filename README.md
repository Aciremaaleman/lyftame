#LYFT

##Pasos

###estructura html

1. Crear estructura html.
  - Tendra el link para ligar html con css.
  - Link de las fuentes de google Fonts.
  - Link de los iconos de awesome.
  - Estara dividida en un header, 6 secciones seguidad y un footer.

Se hace una section general que contendra las demás.

Dentro de header habrá:
  - el header tendra una clase (en este caso la llamamos menu)
  - vendra la imagen del logo, cuenta con un id para llamarlo en css.
  - A continuacion tres vinculos para los botones del menu en el header. El primer boton y el ultimo tendran un id para llamarlos individual.
  - A continuacion se abrira la etiqueta nav, con una clase (en este caso llamada form)
  Dentro de nav tendremos nuestro h1, h2, el input para colocar el numero telefonico, 2 vinculos,
  Y dos parrafos que dentro de cada uno tendra un vinculo.

Dentro de la primer section:
  - Tendra una clase (en este caso llamada secondpart)
  - Comenzara con 3 h1 y 3 parrafos, alternados.
  - Se pondra la imagen respectiva a la section.

Dentro del segundo section:
  - Tendra una clase (en este caso llamada thirdpart)
  - Tendremos un h5, un h1 y un parrafos.
  - agregaremos un div que contendra el iframe del video de la section.

Las siguientes 2 sections contendrán lo mismo que la anterior, con una clase diferente para cada una.

Dentro del footer encontraremos:
  - Una clase declarada (en este caso le nombramos column)
  - Se abrira un div que contenga una clase.
  - A continuacion un h3 y los parrafos respectivos para cada palabra

Se realizaran 2 div más con las mismas etiquetas cada una con su respectivo contenido.

  - Se abriran dos div mas dentro de cada uno ira una imagen.
  - En otro div se colocarn los iconos que se necesiten.
  - Se pondra un hr.
  - Para finalizar un parrafo que contendra el icono respectivo.

###Estructura CSS

1. Se abrira el body con un margin 0 y un background de color #76278F.
2. El header llevara una imagen como fondo y ocupara todo el tamaño del header.
3. La clase form dentro del nav del header tendra un fondo blanco, sera display inline-block
y estara pegado del lado derecho de la pantalla, se solocara la misma fuente para todo el bloque en este caso font-family: 'Montserrat', sans-serif; , dentro de este habra un h1 que tendra un color de #352384 y el h2 sera del mismo color, el input text solo tendra borde de abajo y tendra dentro de el la leyenda de phone number, el parrafo que le sigue tendra el color #728099 los vinculos que estan dentro solo cambiaran de color como el parrafo.
4. El menu con los vinculos iran pegados del lado derecho de la pantalla sobre el formulario, el ultimo vinculo (log in) debe de tener borde redondeado.
5. La imagen del logo se hará más pequeña y quedara del lado izquierdo de la pantalla. (con un margen adeacuado)
6. La siguiente seccion tendra 3 h1 y 3 parrafo alternados pegados del lado izquierdo con margen adecuado, en esta seccion se tendra el color de fondo #76278F.
7. Con un float right colocamos la imagen de esta seccion a la derecha de la pantalla y le damos altura y ancho.
8. La tercera seccion tendra un clear right para evitar que se suba el contenido a la seccion anterior. tendra una fuente de font-family: 'Montserrat', sans-serif; el h5, h1 y el parrafo tendra que ir del lado izquierdo.
9. El video utilizara un float right para que quede a la derecha, con el id que contiene le damos ancho y altura.
10. La siguiente seccion contiene los mismos elementos que la anterior solo que esta vez estan al reves.
11. la ultima seccion es igual que el paso numero 9.
12. el footer tendra un fondo de color #333447, letras font-family: 'Montserrat', sans-serif color blanco, se colocar un clear right en la clase column del footer para no permitir que los elementos se suban a la seccion anterior. ocuparemos nuestras otras clases y practicamente contendra las mismas caracteristicas display inline-block con un texto centrado el margen cambiara deacuerdo a la posicion que se desee, las tres columnas tendran que estar alineadas y los parrafos tendran una accion hoover de color #FF00BF.
13. las imagenes seran llamadas con su id para darles altura y ancho y poderlas acomodar a un lado de las columnas de manera vertical con display inline block y un float right
14. los iconos se colocaran con un margen, centrado en el footer.
15. el hr se le dara un ancho más pequeño y un margen, centrado en el footer.
16. el ultimo parrafo con el icono copyright tendra un margen arriba y abajo y estara centrado.
