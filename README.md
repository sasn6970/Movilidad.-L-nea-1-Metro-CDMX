# Movilidad. Línea 1 (Metro CDMX)

![banner](https://user-images.githubusercontent.com/95544784/203678584-f35376ae-30aa-4fd1-abe3-f74c80db72c9.png)

## Resumen

Con motivo del proyecto de [remodelación y modernización](https://www.capital21.cdmx.gob.mx/noticias/?p=14612) del Metro de la CDMX, la Línea 1 del Metro de la  Ciudad de México se encuentra cerrada temporalmente en el tramo que comprende de la terminal de *Pantitlán* a la estación *Salto del Agua*, desde el 11 de julio de 2022.  

Se estima que estará cerrada 8 meses y que, en marzo de 2023, se dará inicio a la renovación de las estaciones restantes(desde la terminal de *Observatorio* a la estación *Balderas*), concluyendo, al fin, en agosto de 2023.  

El Metro es el medio de transporte más importante de la Ciudad de México y la Línea 1, usada diariamente por miles de habitantes, es una de las más importantes... pero ¿sabemos realmente cuánto? 

## Recursos

- Los Datos consultados para la elaboración de este proyecto fueron publicados por el gobierno de esta entidad y pueden consultarse directamente en el [siguiente enlace](https://datos.cdmx.gob.mx/dataset/da3fcf80-f15f-4478-9795-26eddaa6fe86/resource/5d33f9c7-e033-4676-a02d-9e2129017acf/download/afluencia-preliminar-en-transporte-publico.xlsx-afluencia_diaria.csv).
- Versión de Python: 3.7
- Librerías: Pandas, Plotly, Matplotlib, Seaborn

## Conclusiones

Este análisis de impacto demuestra, con cifras claras, la importancia de la L1 del Metro de la Ciudad de México y el alcance de su cierre temporal. Los usuarios del STC se cuenta por billones y aproximadamente el 15% usan la Línea 1, haciéndola indiscutiblemente la más transitada.

![afluencia_ordenada_por_linea_y_servicio](https://user-images.githubusercontent.com/95544784/203679464-fe96d2e8-ec43-401b-9f25-498c89e27f1f.png)

Esto, sin mencionar el impacto de los transbordes con las estaciones cerradas, dado que las líneas no existen aisladamente y pertenecen a una red de servicio.

![heatmap_afluencia_por_linea_y_servicio](https://user-images.githubusercontent.com/95544784/203678696-f9a6cdf0-d4d5-4d06-b867-080e2d7b33f0.png)

De igual manera, la información recabada por el Gobierno de la CDMX permite visualizar cómo se distribuye la afluencia de los usuarios, según el día de la semana, desafortunadamente no existen datos más precisos respecto a las *horas pico* y no sería posible, únicamente con los datos obtenidos aquí, establecer patrones que permitan a los servicios temporales predecir la cantidad de usuarios que tendrán que desplazar en cada horario. Esto podría resultar en unidades insuficientes en los horarios de mayor transito y un despliegue excesivo en horarios de poco transito.

![heatmap_dia](https://user-images.githubusercontent.com/95544784/203678745-c4f58cd9-c5c1-4204-a41e-7303e347c2ff.png)

En términos generales, habría sido más conveniente remodelar una Línea tan importante durante la cuarentena por COVID 19, considerando que la afluencia de usuarios era mucho menor y las afectaciones habrían sido controladas, de manera eficiente, con menos recursos.

![l_temp](https://user-images.githubusercontent.com/95544784/203681128-c52dd653-9f48-4633-b713-f31a46ec2991.png)
