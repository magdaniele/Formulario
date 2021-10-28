# Formulario
## Al abrirlo por primera vez:
Se deberan habilitar las macros, excel al iniciar el archivo por primera vez abre una pequeña alerta de **naranja claro** el cual permmite habilitar el contenido de las macros y que el formulario se ejecute correctamente.
## Una vez habilitada las macros.
Se ejecutara el formulario al iniciar el excel siempre apareciendo una interfaz muy intuitiva la cual te muestra 2 formularios para llenar las distintas bases de datos. 

### Interfaz de clasificación de basuras:
La primera interfaz es para la clasificación de basura, en esta se nos muestran todas las actividades y dependiendo la actividad se nos despliega las personas pertenecientes a esa actividad, en la parte de seleccionar fecha, al hacer clic en dicho boton se nos despliega una pequeña ventana en la cual podemos escoger el dia, el mes y el año (para editar el año o el mes facilmente, solo se deberá darle clic al mes o al año que aparece en la parte superior de dicha ventana y se podrá elegir el mes y/o el año deseado). Posteriormente se tienen unos pequeños cuadros en los cuales solo podremos escribir los datos en kg de cada uno de los residuos (en dicho cuadro de texto unicamente se pueden escribir numeros positivos). Al finalizar dicho formulario tendremos 3 botones los cuales corresponden a las siguientes funcionalidades.
**AGREGAR:** Funciona para agregar los datos insertados en el formulario a la base de datos.
**BUSCAR:** Este abre una hoja excel donde se muestran graficas de los resultados de todos los datos que aparecen en la base de datos.
*En primera instancia:* se podrá filtrar dichas graficas por fechas, por sector o por el tipo de persona.
**ATRÁS:** Como el mismo nombre nos dice, nos regresa a la interfaz anterior.

### Interfaz de seguridad y salud:

En esta interfaz al igual que en la de clasificación de basuras se nos muestran unas listas desplegables de las cuales dependen otros valores del formulario y estas dependencias son en base a cada tipo, por ejemplo, si se va a realizar un reporte de un accidente, se despliegan los posibles accidentes que hallan podido tener y así con el resto de elementos del formulario. El apartado de la fecha y de la actividad y las personas que pertenecena a dicha actividad funciona exactamente igual al de la interfaz de clasificación de basura al igual que los botones.

## ¿Como encontrar los datos?

Para encontrar estos datos se deberá desproteger el libro con la clase suministrada y una vez colocada la clave será posible editar el libro y en la zona inferior donde aparecen las hojas, se deberá hacer clic derecho y presionar donde dice "mostrar" y ahi se desplegará la lista de todas aquellas hojas ocultas en las cuales estan toda la información de la base de datos. **(IMPORTANTE)** Antes de cerrar el excel, asegurarse de proteger el libro nuevamente con la *misma clave* y volver a ocultar todas las hojas que se mostraron manualmente y viceversa, mostrar todos las hojas que se mostraron manualmente para no afectar la funcionalidad del programa.

## Para añadir mas categorias, mas enfermedades, personas etc para el formulario

En este caso se deberá acceder a aquella hoja a la cual se quiere agregar la categoria/persona/enfermedad o lo que desee ingresar que estará oculta. Posteriormente, para añadir la información es requerido seguir el mismo patrón de la hoja, es decir, si en las filas se encuentra el nombre de la categoria deseada y en las columnas el contenido, seguir añadiendo las categorias en las filas y el contenido en las columnas. 
