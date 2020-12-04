### I. Visión general de la aplicación

El resultado debe mostrar una captura semejante a esta pantalla siguiente:

<img src="Medio\imagen1.PNG">

### Tarea 1.1: Crear y explorar el proyecto

<img src="Medio\imagen2.PNG">

 Primeramente lo que vamos hacer es crear un nuevo proyecto en el cual estare trabajando, para eso vamos a dar clic en <crear un nuevo proyecto>.

<img src="Medio\imagen3.PNG">
Luego de eso nos envia a otra ventana, en la cual debemos elegir una plantilla, estare elegiendo la plantilla llamda <Empty Activity>

<img src="Medio\imagen4.PNG">

Seguido de esto nos envia a otra ventana, pero esta vez vamos lo que vamos hacer es rellenar los campos con lo que se nos indica. 

<img src="Medio\imagen5.PNG">

Ya llegando a esta parte solo vamos a dar <Finish> para que entremos en el programa en el cual vamos a estar trabajando.

<img src="Medio\imagen6.png">

<img src="Medio\imagen7.png">


### Tarea 1.2: Agregar elementos Views en el editor de Layout

### Examinar las restricciones (constraint) de los elementos

Abra activity_main.xml desde el panel Proyecto > Android si aún no está abierto. Si la pestaña Design (diseño) aún no está seleccionada, haga clic en ella.

Esta opcion la podemos encontrar en el archivo <res>, luego desplegamos el archivo <layout>.

<img src="Medio\imagen8.png/">

<img src="Medio\imagen9.png/">

como podemos observar, que la pestaña <Design> si se encuentra seleccionada.

### Si no hay ningún blueprint, haga clic en el botón Select design surface de la barra de herramientas (puede presionar la tecla B, para cambiar entre cada modo) y elija Design + blueprint

<img src="Medio\imagen11.png/">

### La herramienta Conexión automática también se encuentra en la barra de herramientas. Está habilitado de forma predeterminada. Para este paso, asegúrese de que la herramienta no está deshabilitada.

<img src="Medio\imagen12.PNG/">

como podemos observar, la herramienta se encuentra deshabilitada, asi que debemos asegurarnos de habilitarla, para esto simplemente hacemos clic sobre la herramienta.

<img src="Medio\imagen13.PNG/">

### Haga clic en el botón de acercar para acercar los paneles de diseño y blueprint para ver de cerca.

<img src="Medio\imagen14.PNG/">


 cuando hacemos zoom automaticamnete los paneles de diseño se ven mejor, y el mensaje es mas posible leerlo.

 ### Seleccione TextView en el panel del árbol de componentes (Component tree). El "Hello World" se resalta en los paneles de diseño y blueprint y las restricciones para el elemento TextView son visibles.

 <img src="Medio\imagen16.PNG/">

### A continuación, se muestra como establecer una restricción o constraint con el contenedor padre al lado derecho del TextView

<img src="Medio\imagen17.png/">


### Añadir un botón al layout

### Comience con una pizarra limpia. El elemento TextView no es necesario, por lo que mientras está seleccionado, pulse la tecla Supr o elija Edición > Eliminar. Ahora tiene un diseño completamente en blanco

<img src="Medio\imagen18.PNG/">


### Arrastre un botón desde el panel Paleta a cualquier posición de la presentación. Si coloca el elemento Button en el área media superior de la presentación, pueden aparecer restricciones automáticamente. Si no es así, puede arrastrar restricciones a la parte superior, izquierda y derecha del diseño


<img src="Medio\imagen19.png/">

<img src="Medio\imagen17.png/">


### Añada un segundo botón en la parte inferior del layout y del mismo modo cree las restricciones correspondientes con los elementos próximos a él.

<img src="Medio\imagen20.png/">

### Pruebe borrar todos los constraints o restricciones de un elemento, seleccionando y pasando el puntero sobre este y seleccionar cleal all constraints

<img src="Medio\imagen21.PNG/">

Para poder borrar todos los constraints o restricciones de un elemento, vamos a susar la herramienta que se encuentra señalada con el circulo rojo, en donde si ubicamos el puntero sobre de ella, nos muestra un mensaje, dandonos a entender de que se ocupa para eso.


### Tarea 1.3: Cambiar los atributos de los elementos de la interfaz de usuario

### Cambiar el tamaño del Button

para cambiar el tamaño del Button, ubicamos en la perte donde se encuentra el <Component tree>, ahi estan los Button.

<img src="Medio\imagen22.PNG/">

### Haga clic en la pestaña Atributos en el lado derecho de la ventana del editor de layout.

<img src="Medio\imagen23.png/">

### Haga clic en el control de ancho las veces que sea necesario; debe lograr el valor match_constraint para el layout_width.

<img src="Medio\imagen24.png/">

### Realice la misma modificación para el botón inferior, el resultado es que ambos botones deben cubrir todo el ancho del constraint.

<img src="Medio\imagen26.png/">

### Establezca wrap_content al layout_height, también puede usar un valor fijo de 16dp

<img src="Medio\imagen27.png/">

### Cambiar los atributos de Button

* Después de seleccionar el primer botón, edite el campo ID en la parte superior del panel Atributos a button_toast para el atributo android: id, que se usa para identificar el elemento en el layout.

<img src="Medio\imagen28.PNG/">

### Establezca el atributo de background en @color/colorPrimary. (A medida que ingresa @c, aparecen opciones para una fácil selección). Si no está establecido el color, hágalo en colors.xml

<img src="Medio\imagen29.PNG/">
<img src="Medio\imagen30.PNG/">




### Establezca el atributo textColor en @android:color/white.
<img src="Medio\imagen31.PNG/">

### Edite el atributo text en Toast.

<img src="Medio\imagen32.PNG/">


### Selecciona el segundo botón y edite su campo id a button_count

<img src="Medio\imagen33.PNG/">

### Edite el atributo text del segundo botón a Contar

<img src="Medio\imagen34.PNG/">

### Cambie el color de texto y de fondo a los botones
<img src="Medio\imagen35.PNG/">
<img src="Medio\imagen36.PNG/">

### Agregar el elemento TextView y sus atributos correspondientes


* Desde el panel Palette y el apartado Common, agregue un elemento View TextView y establezca el atributo id a show_count.

<img src="Medio\imagen39.png/">
<img src="Medio\imagen38.PNG/">

* Establezca las restricciones del TextView, la parte superior con el botón de Toast y su parte inferior con el botón contador.

<img src="Medio\imagen40.png/">

### Establezca las restricciones izquierda y derecha del elemento TextView al lado correspondiente al contenedor padre.

<img src="Medio\imagen41.png/">

### Establezca el valor text a 0

<img src="Medio\imagen42.PNG/">
 
 Cuando le establecemos el valor 0 al texto ocurre que se reduce de manera notable.

 <img src="Medio\imagen43.png/">

 ### Establezca el valor textSize a 160sp

 <img src="Medio\imagen44.PNG/">


### Establezca el textStyle a bold

<img src="Medio\imagen45.PNG/">

### Cambie layout_width y layout_height a match_constraint

<img src="Medio\imagen46.PNG/">


### Establezca el textColor a @color/colorPrimary

<img src="Medio\imagen47.PNG/">

### Establezca un valor preferido al atributo background, opcional el #0F49CD

<img src="Medio\imagen48.PNG/">

<img src="Medio\imagen49.png/">

### Establezca el valor gravity a center_vertical

<img src="Medio\imagen53.PNG/">

<img src="Medio\imagen54.PNG/">

<img src="Medio\imagen55.PNG/">

<img src="Medio\imagen56.PNG/">

## Tarea 1.4: Editando el layout en el XML

* Abra el fichero activity_main.xml y cambie el modo solamente a código

<img src="Medio\imagen57.PNG/">



