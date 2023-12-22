# simulacion_satelital
En este programa realizamos simulaciones de orbitas de un satelite en distintas alturas sobre la superficie de la tierra, empleando el metodo de integración de Leapfrog. Las dependencias del código son principalmente las librerías de `numpy` y `matplotlib.pyplot`.

Primero se creó una clase llamada `cuerpo` donde tendrá las principales funciones y atributos  como:
se definen atributos para la masa, pocisiones, constantes y distancias. Valores para cada poscisión sea X e Y. 
`cal_a` donde calcula la aceleracion de un cuerpo debido a todos los otros, 
`def update_pos` que actualiza la poscisión,
`update_vel` se actualiza la velocidad con cada paso de tiempo 
y `cal_energy` donde se busca calcular la energía para tener una nocion de como esta el error de nuestra simulación.
