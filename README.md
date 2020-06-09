# Proyecto Montreal
# <center> Analisis y ajuste de la serie de tiempo de la energia electrica en Colombia entre 1995 - 2018.
Actividad Final Clase Fundamentos de Analitica
Actividad Final Clase Redes Neuronales
  
**Universidad Nacional de Colombia**

La energía eléctrica es la forma de energía que resulta de la existencia de una diferencia de potencial entre dos puntos, lo que permite establecer una corriente eléctrica entre ambos cuando se los pone en contacto por medio de un conductor eléctrico. La energía eléctrica puede transformarse en muchas otras formas de energía, tales como la energía lumínica o luz, la energía mecánica y la energía térmica.

Actualmente la energía eléctrica se puede obtener de distintos medios, que se dividen principalmente en:

* Renovables:
  + Centrales termoeléctricas solares
  + Centrales solares fotovoltaicas
  + Centrales eólicas
  + Centrales hidroeléctricas    (Principal en Colombia)
  + Centrales geo-termoeléctricas
* No renovables:
  + Centrales nucleares
  + Combustibles fósiles:

**Problema**

Se cuenta con 23 archivos en los cuales se encuentra los precios diarios por hora de la energía eléctrica, los archivos tienen de diferentes extensiones y con diferentes dimensiones. Se necesita lectura de estos, unificación, análisis y realizar el ajuste por redes neuronales (tipo a consideración), encontrar el rezago pertinente y los hiperparámetros que mejor ajusten el modelo.

**Objetivo**

Realizar el estudio la estructura temporal o dinámica de los datos de la energía eléctrica en Colombia para posteriormente realizar pronóstico del precio.

**Resultados y conclusiones**

Se encontraron 238 registros nulos y 1951 registros duplicados que fueron retirados. Se organiza la serie de tiempo por precio medio diario.

![alt text](https://github.com/oecorrechag/Proyecto-Montreal-Energia/blob/master/mean_day.PNG)

**Nota:** El pico que se encuentra entre los años 2015 y 2016 se debe al fenomeno del niño, por lo que no se debe ni modificar ni retirar. 

![alt text](https://github.com/oecorrechag/Proyecto-Montreal-Energia/blob/master/serie.PNG)

