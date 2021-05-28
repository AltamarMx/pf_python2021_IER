# pf_python2021_IER
Proyecto final para la materia de Python impartida de febrero a junio 2021,
se debe entregar a m'as tardar el d'ia 25 de junio a las 12:00 horas tiempo
del centro de Mx.

Se debe programar una clase que haga lo siguiente:

```
import proyecto as pf

a = pf.analisis()

a.importa('archivo.csv')
```

La clase debe realizar cuatro acciones explíticas, es decir
```
a.boxplot()
```
y así, según se requiera.

Puntos:
| Descripción |  Puntos |
|-------------|--------:|
|Clase en un archivo .pu          | 10 |
|Documentaci'on por m'etodo final | 20 |
|Estructura de proyecto adecuada  | 10 |




___
1. Una gr'afica de boxplot, tomen como guía la siguiente figura:
![Boxplot](img/boxplot.png)

 Para cada mes se deben graficar el boxplot correspondiente
 al mes. El boxplot debe visualizar
 el promedio de la variable seleccionada en lugar de la mediana.
 El método debe permitir seleccionar las variables a graficar, cada
 variable debe tener su propio eje y con su escala.



___  



2. Una rosa de vientos, tomen como guía la siguiente figura:
![Rosa de viento](img/rosa_vientos.png)

Utilizando [Python-windrose](https://github.com/python-windrose/windrose)
crear una rosa de vientos donde permita definir la estación (primavera,
  verano, otoño, invierno) y grafique los meses que incluyen esa estación
  como se esquematiza en la figura.
  Además, el método debe permitir seleccionar si la rosa de viento mostrada
  corresponde a todo el día (0 a 23 horas) o solo diurno (8 a 20 horas) y
  nocturno (20:01  a 7:59 horas).



__


3. Un gráfica donde se presente el valor de la variable promediada cada paso
temporal, tomen como referencia la imagen:
![promedio horario](img/promedio_horario.png)

El m'etodo debe permitir seleccionar la variable a graficar, y en
sombra (fill between) se debe poder seleccionar entre: desviación estándard,
promedio del valor máximo o mínimo, y el valor máximo de ese paso temporal.

También se debe poder seleccionar si se desea una gráfica anual o de un mes
específico.


___
4. Un  __heatmap__ de la **variable** seleccionada para las horas
y los d'ias , toma como referencia la siguiente imagen:

![heatmap](img/heatmap.png)

Se debe poder seleccionar la variable a visualizar, y el valor a calcular
por variable debe ser el valor m'aximo, el valor m'inimo, el promedio,
y la desviaci'on est'andard de la variable.
