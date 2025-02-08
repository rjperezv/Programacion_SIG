FLUJO DE TRABAJO PARA MAPEO DIGITAL DE SUELOS

Este ejercicio presenta el flujo de trabajo que se realiza cuando desarrollamos un mapeo de suelos, este 
permite trabajar con datos vector y raster, a su vez se trabaja con datos tabulares, que son los datos tomados por lxs levantadorxs 
de suelos en campo.

El mapeo digital de suelos es un proceso que utiliza tecnologías de teledetección, sistemas de información geográfica (SIG) y modelos 
predictivos para crear mapas detallados y precisos de los diferentes tipos de suelo en una región específica. Estos mapas son fundamentales 
para entender la distribución espacial de los suelos y sus características, lo que permite tomar decisiones informadas en áreas como la agricultura, 
la gestión del medio ambiente, la planificación del uso del suelo y la conservación de los recursos naturales.

TRABAJO CON DATOS VECTOR Y RASTER 

Cuando se empieza a trabajar con un conjunto de datos, es necesario hace un poco de exploración para entender qué información 
puede contener. Existen varias formas de extraer información básica de un objeto, ya sean listas, matrices, data frames o cualquier otra clase.
Se pueden subir archivos de diistintos tipos (xlsx, xls, csv, txt, etc…). En los datos tabulados, generalmente las columnas son variables y las 
filas son observaciones o individuos de esas variables.


LIMPIEZA DE DATOS 
En el proceso de transcripción de los datos suele presentar errores en los datos obtenidos en campo y luego pueden alterar el análisis 
que se realice. Es importante resaltar que de aquí en adelante es crucial el conocimiento de la persona que esté mapeando; el criterio y 
la experiencia permiten que la interpetación y edición de los datos tengan éxito.

Primero se deben haber definido unas estándares previos que resuelvan: qué datos son necesarios en el muestreo, qué unidades 
se van a utilizar, quiénes tomaron los datos y con qué métodos. Esto se vuelve necesario para saber a qué fuentes acudir cuándo 
los datos presenten muchas confusiones.

En los procesos de transcripción, cálculos en campo, estimaciones y demás, se puede presentar modificación en los datos lo que 
aumenta los errores en el estudio. Se procede a filtrar los datos que se salgan de la normalidad de cada variable y es necesario 
definir si fueron errores de cálculo de tipeo. Para esto se debe ubicar en cada variable esos valores y transformarlos 
o eliminarlos si es el caso.

También se puede hacer un set aparte, seleccionando solo las columnas de interés. Donde se debe especificar que columnas
 se quieren conservar en lugar de eliminar las que no se necesitan


ARMONIZACION DE PERFILES

El Equal - area spline también conocido como spline de suavizado cuadrático de áreas iguales, es un tipo específico de función 
spline que es utilizada en diversos campos, particularmente en la ciencia del suelo y los estudios ambientales. Esta función matemática 
ajusta una curva suave a través de una serie de puntos de datos, conservando al mismo tiempo el área total bajo los datos originales y la 
curva ajustada. Lo que facilita el análisis y modelamiento en funciones de profundidad continuas, como la variación de las propiedades del suelo 
(carbono orgánico, pH) u otras variables ambientales a diferentes profundidades.
Resulta una tecnica fundamental para el proceso de armonizacion de datos en los perfiles de suelos.

SELECCION DE COVARIABLES 

Para este proceso se busca reunir la mayor cantidad de información que servirá como fuente de entrada para el DSM, es importante 
identificar las fuentes que son útiles en este proceso y realizar la recopilación.

Seleccionar las covariables adecuadas es fundamental dentro de la preparación de los datos. En este paso se busca explicar la relación que tienen
 las variables. Una covariable es influyente en la variable dependiente (la que se quiere estudiar) pero no es parte 
 de la variable independiente (la que se manipula).
 
 Para cada factor del modelo se debe colectar la mayor cantidad de información, con la mejor calidad posible. Para esto se verifica 
 que las fuentes sean confiables y que en medida de lo posible contengan información durante un largo periodo de tiempo para que los 
 datos no estén sesgados a fenómenos con poca ocurrencia.

Recopilación de datos: Se obtienen los archivos vectoriales, ráster y demás que pertenecen a cada factor. Se recomienda guardarlos 
de forma ordenada para facilitar el procesamiento.

ESTADO DEL CODIGO 

El presente ejercicio se ecnuentra en un avance del 50% , encontrandose en el proceso de estandarizacion de las covariables.