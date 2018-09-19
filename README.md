# curso-responsive-design
Curso de Responsive Design por Platzi

## ¿Qué es Responsive Design?

Son todas aquellas técnicas que usamos para adaptar nuestras aplicaciones web a la mayor cantidad de pantallas

## Patrones de diseño

* Mostly Fluid: Es el patrón más popular entre todos, consiste en el apilamiento de todas las columnas como el nacho del navegador    deje de acomodarlos. Los elementos se vuelven fluidos y se expanden hsata los diferentes breakpoints.
Además se puede combinar con la técnica de colocación de columnas.
Otro concepto que este patrón emplea es definir un ancho máximo para el wrapper que contiene las capas pudiendo crecer el diseño y expandirse a cualquier resolución quedando un espacio en blanco a los lados.

  ![alt text](https://developers.google.com/web/fundamentals/design-and-ux/responsive/imgs/mostly-fluid.svg?hl=e "Mostly Fluid")
  
* Colocación de columnas: En el caso de los diseños con varias columnas de ancho completo, durante el proceso de colocación de  columnas éstas únicamente se colocan de forma vertical debido a que el ancho de la ventana es demasiado reducido para el contenido.

  En un momento dado, todas las columnas se apilan verticalmente. La selección de puntos de interrupción para este patrón de diseño depende del contenido y cambia para cada diseño. 

  ![alt text](https://developers.google.com/web/fundamentals/design-and-ux/responsive/imgs/column-drop.svg?hl=es "Colocación de columnas")
  
* Layout shifter: El patrón Layout shifter es el más adaptable, ya que posee varios puntos de interrupción en diferentes anchos de pantalla.

  La clave para este diseño es el desplazamiento del contenido, en lugar de su reprocesamiento y colocación debajo de otras columnas. Debido a las diferencias significativas entre cada punto de interrupción principal, es más complejo de mantener, y es posible que se deban realizar cambios dentro de los elementos, no solo en el diseño de contenido general.

  ![alt text](https://developers.google.com/web/fundamentals/design-and-ux/responsive/imgs/layout-shifter.svg?hl=es "Layout shifter")

* Tiny tweaks: El patrón Tiny tweaks permite realizar pequeños cambios en el diseño, como ajustar el tamaño de la fuente, cambiar el tamaño de las imágenes o desplazar el contenido de maneras muy poco significativas.

  Funciona correctamente en diseños con una sola columna, como los sitios web lineales de una sola página y los artículos con mucho texto.

  [Link de Ejemplo por Google](https://googlesamples.github.io/web-fundamentals/fundamentals/design-and-ux/responsive/tiny-tweaks.html)

* Off canvas: En lugar de apilar contenido verticalmente, el patrón Off canvas coloca contenido menos usado (tal vez menús de navegación o de apps) fuera de la pantalla y solo lo muestra cuando el tamaño de la pantalla es suficientemente grande. En las pantallas más pequeñas, el acceso al contenido es posible con solo a un clic.

  Muchas veces visto en las webs como un menú hamburguesa.

  ![](https://developers.google.com/web/fundamentals/design-and-ux/responsive/imgs/off-canvas.svg?hl=es "Off Canvas")

## Conceptos Nuevos

* Viewport: Área visible del navegador.
* Portrait: Orientación vertical del celular.
* Landscape: Orientación horizontal del celular.
* Mobile First: Website desde la menor resolución de pantallas hasta la mayor
* Desktop First: Website desde la mayor resolución de pantallas hasta la menor
