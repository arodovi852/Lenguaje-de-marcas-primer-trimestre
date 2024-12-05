Para este proyecto decidí hacer una página web donde puedes llevar un seguimiento de tus juegos completados: Un backlog. Aquí podrás escoger distintos juegos, ver valoraciones e información de estos juegos y marcarlos como completados o en proceso de compleción,

Sin embargo antes de comenzar con el propio diseño de la web, para la creación de esta se utilizó HTML para su estructura y CSS para los estilos. Cabe destacar que todos los estilos fueron recogidos en un único archivo CSS comparado con la posibilidad de recogerlos en varios estilos o varios archivos CSS. Esto fue por mera organización, ya que es mucho más legible de esta forma y ocupa menos espacio.

Con esto dicho, podemos comenzar con la distribución de la página:
Nada más entrar, la página principal te muestra los títulos más populares entre los usuarios en caso de que alguno te llame la atención.

Comenzando por la cabecera, nos encontramos con las distintas páginas principales en la que se divide la web: Los juegos, las estadísticas de la página, las reseñas, las listas, la página de hacer login y un buscador.

Por el contrario, abajo del todo nos encontramos con el footer, donde se recoge las redes sociales de la página web y tanto un enlace para contactar con la página como un formulario para añadir juegos a esta, que explicaré en detalle más adelante.

Ambas estructuras son universales y se encuentran en todas las páginas del proyecto.

Por otro lado, el cuerpo en sí está compuesto por los propios juegos con sus títulos y valoraciones promedias por usuarios, donde si se le da click a la imagen esta te llevará a la página informativa de su respectivo caso, en este caso Silent Hill 3. 

Por otra parte, si algún juego no está recogido en la página web, tienes la posibilidad de rellenar un formulario para añadirla a esta. Solo requiere el nombre del juego y un enlace que demuestre su existencia, bien sea una imagen del juego u otra página web donde se mencione.

Y como punto de referencia, este era el wireframe original del formulario, y esta es la página final. La página fue ajustada para que no ocupase demasiado espacio innecesario y fuese visualmente atractiva.

De esta misma forma, si volvemos a la página inicial, así se veía el wireframe de la página y este es el resultado final.
Como se puede observar, los juegos populares terminaron constituyendo toda la página en lugar de estar clasificado por secciones. Esto se debe principalmente por motivos de variedad, ya que inicialmente iban a haber muchas más páginas pero estas eran idénticas como podéis ver por el Balsamiq, por lo que terminó quedándose así.

Pero volviendo al cuerpo principal de esta página y a las imágenes, pulsando en una nos lleva a su página de información. 

Aquí se pueden observar varias cosas: El título del juego, su portada, puntuación y botón de guardado a un lado, su descripción, y finalmente su tráiler todo en una misma línea.

Más abajo se encuentran juegos parecidos al título, para aquellos que disfrutaron de la experiencia y quieren conocer juegos similares.

Finalmente, al fondo del todo se encuentra una sección con varias reviews, donde se muestran reviews populares de distintos usuarios.

Aquí el Balsamiq es ligeramente distinto, ya que en medio del proyecto surgió la idea de implementar un vídeo para aportar variedad a este, y los juegos similares fueron relegados a la sección inferior al vídeo.

Dándole click a “Reviews” en esta página o arriba en la cabecera nos lleva a la página de reviews del juego, donde se puede escribir una review de cualquier título deseado. Además, como referencia aparecerán varias reviews de diversos títulos por debajo de esta.

Si seguimos con las páginas de la cabecera, nos topamos con las estadísticas. Aquí se recoge la información acerca de los juegos mejores valorados, peores valorados, más jugados y más controversiales en base a reseñas, además de un gráfico de sectores de las consolas de preferencia de los usuarios.

La piechart fue creada completamente con CSS. Para obtener el círculo se aumentaron los valores de los bordes hasta que fuesen los suficientemente altos como para formar un círculo. Además, para dividirlo por secciones solo hizo falta aplicarle una gradiente cónica y asignándoles a cada color una posición mediante sus grados. Esto hace que el círculo entero se divida en secciones y se vea como un gráfico de sectores.

Había otra forma de hacerlo con JavaScript pero era mucho más compleja y como no entraba dentro del temario decidí optar por esta opción.

De hecho, si miramos el Balsamiq es muy similar a excepción de unas gráficas que iban a estar por debajo de los juegos, pero debido al estricto uso de JavaScript que requerían para ser funcionales opté por omitirlos.

Más adelante nos topamos con la siguiente página: Las listas. Aquí se recogen diversas listas que contienen juegos relacionados entre sí por algún motivo u otro, por ejemplo juegos indie o de bajo presupuesto. Esto facilita la búsqueda de juegos del mismo calibre o de una misma franquicia.

Y como se puede ver en el Balsamiq, esta página inicialmente iba a contener muchas más imágenes, sin embargo visualmente se veía demasiado compreso por lo que esta separación es más visualmente digerible comparado a la idea inicial. 

Finalmente nos encontramos con la sección de inicio de sesión, donde las personas pueden introducir su correo y contraseña para acceder a su cuenta con sus juegos y datos registrados. Además, incluye enlaces en caso de que al usuario se la haya olvidado la contraseña y otro para el propio inicio de sesión. 
Por limitaciones de código, ninguno de estos botones funciona realmente, pero son enlaces que llevarían a sus páginas correspondientes, evitando así el uso de botones que está considerado como una mala práctica.

