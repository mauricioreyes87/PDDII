# Selección, limpieza, Análisis y Visualización de Datos con OpenRefine y Datawrapper

_Mauricio Reyes Rojas - Actividad Dirigida III - Periodismo de Datos II_

A partir de los datos publicados del [Proyecto TRESCA](https://github.com/flowsta/nebrija-2021/ ) sse realizó un conjunto de operaciones para preparar los datos para la selección, limpieza, análisis y visualización de los datos. Estos procesos se efectuaron respectivamente en Open Refine, Excel y Datawrapper.

## Gráfico Final

[![Carga de datos](https://github.com/mauricioreyes87/docs/blob/main/img/graficofinal.png?raw=true)]()

El gráfico escogido para visualizar los datos fue un gráfico de dispersión con el cual buscábamos establecer la relación entre la cantidad de tweets sobre una tendencia especifica en una determinada fecha.

[Vea aquí el grafico Interactivo](https://datawrapper.dwcdn.net/zS8gj/1/)

Este gráfico permitió establecer la relación de los datos de las cuatro tendencias, la distribución de los datos en el tiempo de estudio.

Además, en el gráfico se implementó una línea de tendencia cuadrática con la cual se pudo establecer runa tendencia negativa en la cantidad de tweets de las tendencias. Esta tendencia negativa se evidencia desde octubre en la finalización de la campaña. Esta tendencia continuó hasta mediados de diciembre luego las votaciones, para iniciar una recuperación a finales de diciembre hasta enero de 2021.

## Proceso de construcción el gráfico

Luego de la selección y limpieza descrita en el siguiente aparte se procedió a cargar los datos en el Datawrapper, el archivo seleccionado fue: [Depuradopordias.csv](https://github.com/mauricioreyes87/docs/blob/main/img/Depurado%20por%20dias.xlsx?raw=true).

[![Carga de archivo CSV](https://github.com/mauricioreyes87/docs/blob/main/img/gra6.png?raw=true)]()

Luego de este procedimiento, iniciamos la fase de verificar y describir en la que se asignó el tipo de dato a cada columna.

[![Verificar y describir](https://github.com/mauricioreyes87/docs/blob/main/img/gra7.png?raw=true)]()

Paso seguido de culminar este procedimiento, continuamos con la visualización. En esta etapa se escogió el tipo de gráfico de dispersión.

[![Gráfico](https://github.com/mauricioreyes87/docs/blob/main/img/visua1.png?raw=true)]()

Luego de escoger el tipo de gráfico, se continuó con la mejora del gráfico en el que se ordenó las variables del eje vertical y del eje horizontal. También se definió el formato y posición de las variables y la disposición de la cuadrícula del gráfico.

[![ejes, formatos y posición](https://github.com/mauricioreyes87/docs/blob/main/img/visua2.png?raw=true)]()

En este mismo apartado se modificaron los colores, asignando a cada tendencia un color, también se ajustó el tamaño y forma de los símbolos que representaban los datos. Además, se asignó una línea de tendencia.

[![style](https://github.com/mauricioreyes87/docs/blob/main/img/visua3.png?raw=true)]()

En el apartado de Anotar se agregó el título del gráfico, la descripción, fuente de datos y su enlace. También se agregaron las etiquetas los datos, se activaron las descripciones emergentes y se personalizaron.

[![style](https://github.com/mauricioreyes87/docs/blob/main/img/visua4.png?raw=true)]()

[![style](https://github.com/mauricioreyes87/docs/blob/main/img/visua5.png?raw=true)]()

En el último apartado de Visualizar se ajustó el diseño final del IFRAME en el cual se activaron la descarga de los datos, la imagen de la visualización y el código embed. Además, se habilitó la posibilidad de compartir el gráfico en redes sociales.

[![style](https://github.com/mauricioreyes87/docs/blob/main/img/visua6.png?raw=true)]()

El proceso culminó con la publicación de la visualización y la configuración para compartir o integrar el gráfico.

[![style](https://github.com/mauricioreyes87/docs/blob/main/img/visua7.png?raw=true)]()

## Proceso de Selección y Limpieza

Luego de obtener los datos respectivos mediante la descarga de los ficheros se procedió a cargarlos en OpenRefine en el cual se realizaron los siguientes pasos:

- Selección de Datos

[![Carga de datos](https://raw.githubusercontent.com/mauricioreyes87/docs/main/img/gra1.png)]()

Carga de datos: se procedió a mover la columna tuits a la primera posición. Este procedimiento se realiza con el fin de organizar los datos para la visualización.

[![intercambio de Columnas](https://github.com/mauricioreyes87/docs/blob/main/img/gra2.png?raw=true)]()

Eliminación de las Columnas Harris - Pance - Biden - Trump ya que para la visualización proyectada no se requerían.

[![Eliminación de Columnas](https://github.com/mauricioreyes87/docs/blob/main/img/gra3.png?raw=true)]()

Transformación de la columna fecha: en las celdas de la columna se aplicó la función value.toDate(). Función que convirtió los campos Text en campos Date.

[![Transformación de Tex to Date](https://github.com/mauricioreyes87/docs/blob/main/img/gra4.png?raw=true)]()

Tras ejecutar estas operaciones en OpenRefine, se exportó el documento en formato CSV, el cual fue importado en Excel en él se ejecutó un proceso de limpieza de datos.

La base de datos contenía duplicidad en los campos, debido a la toma obtención de varios datos a distintas horas del día, sobre las tendencias analizadas. Frente a esta duplicidad se decidió ubicar el dato más significativo por tendencia en el día de análisis. Para ellos se ubicó el de mayor cantidad de tweets, los demás datos se desecharon.

[![Limpieza de Datos](https://github.com/mauricioreyes87/docs/blob/main/img/gra5.png?raw=true)]()
