# simulacion_satelital
En este programa realizamos simulaciones de orbitas de un satelite en distintas alturas sobre la superficie de la tierra, empleando el metodo de integración de Leapfrog. Las dependencias del código son principalmente las librerías de `numpy` y `matplotlib.pyplot`.

Primero se creó una clase llamada `cuerpo` donde tendrá las principales funciones y atributos  como:
se definen atributos para la masa, pocisiones, constantes y distancias. Valores para cada poscisión sea X e Y. 
`cal_a` donde calcula la aceleracion de un cuerpo debido a todos los otros, 
`def update_pos` que actualiza la poscisión,
`update_vel` se actualiza la velocidad con cada paso de tiempo 
y `cal_energy` donde se busca calcular la energía para tener una nocion de como esta el error de nuestra simulación.


Contenido del Código
El código se divide en varias secciones:

Importación de Librerías
`import matplotlib.pyplot as plt`
`import numpy as np`
Se importan las librerías necesarias para la visualización de datos y cálculos numéricos.

Constantes y Alturas de Órbita
`masa_tierra = 5.972e24  # Masa de la Tierra en kilogramos`
`G = 6.67e-11  # Constante de gravitación universal`
`rt = 6370e3  # Radio de la Tierra en metros`

`LEO = 1250e3 + rt`
`MEO = 10000e3 + rt`
`GEO = 35786e3 + rt`
`HEO = 70000e3 + rtmasa_tierra = 5.972e24  # Masa de la Tierra en kilogramos`
Se definen constantes y alturas de órbita para la simulación.

Clase `cuerpo`
