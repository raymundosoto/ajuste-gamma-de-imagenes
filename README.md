# Ajuste gamma de imágenes

Este repositorio contiene la información para realizar el ajuste gamma en imágenes digitales. Se realizó como una práctica de la materia de procesamiento  digital de imágenes en UNITEC

## Objetivo

Implementar la mejora del contraste en imágenes digitales usando el ajsute gamma

## Teoría 

El ajuste gamma utiliza una función matemática para asignar un nuevo valor a los pieles de forma local. El valor de gamma se elige a partir del valor del piel que se quiere corregir: Para valor de gamma = 1 no hay corrección, para valor de gamma > 1 corrige píxeles oscuros y para gamma < 1 corrige pixeles claros. 

El resultado final es una imagen donde se observan tonos claros,, oscuros e intermedios, de tal forma que se observan detalles que pasan desapercibidos a simple vista. 

La función de ajuste gamma es 

![image](https://user-images.githubusercontent.com/72757419/192912411-65992c03-1071-46eb-bb86-c73da49831b7.png)

Se agregan algunos resultados  de las imágenes procesadas con el script de Matlab.

## Resultados

Comparación entre una imagen sin ajuste gamma (imagen superior) y una imagen corregida con gamma = 2.5 (imagen inferior)

![image](https://user-images.githubusercontent.com/72757419/192911235-7d040965-b2d7-4f0f-994a-77deacb74497.png)


### Conclusiones  

