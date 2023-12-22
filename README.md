# simulacion_satelital
En este programa realizamos simulaciones de orbitas de un satelite en distintas alturas sobre la superficie de la tierra, empleando el metodo de integración de Leapfrog. Las dependencias del código son principalmente las librerías de numpy y matplotlib.pyplot.

Primero se creó una clase llamada cuerpo donde tendrá las principales funciones y atributos  como:
se definen atributos para la masa, pocisiones, constantes y distancias. Valores para cada poscisión sea X e Y. 
cal_a donde calcula la aceleracion de un cuerpo debido a todos los otros, 
def update_pos que actualiza la poscisión,
update_vel se actualiza la velocidad con cada paso de tiempo 
y cal_energy donde se busca calcular la energía para tener una nocion de como esta el error de nuestra simulación

# simulacion_satelital
En este porgrama realizamos simulaciones de orbitas de un satelite en distintas alturas sobre la superficie de la tierra, empleando el metodo de integración de Leapfrog. Las dependencias del código son principalmente las librerías de numpy y matplotlib.pyplot.

Primero se creó una clase llamada cuerpo donde tendrá las principales funciones y atributos  como:
se definen atributos para la masa, pocisiones, constantes y distancias. Valores para cada poscisión sea X e Y. 
cal_a donde calcula la aceleracion de un cuerpo debido a todos los otros, 
def update_pos que actualiza la poscisión,
update_vel se actualiza la velocidad con cada paso de tiempo 
y cal_energy donde se busca calcular la energía para tener una nocion de como esta el error de nuestra simulación

Simulación de Órbitas de Satélite
Este programa realiza simulaciones de órbitas satelitales a diversas alturas sobre la superficie de la Tierra, utilizando el método de integración Leapfrog. Las dependencias principales del código incluyen las bibliotecas de numpy y matplotlib.pyplot.

Descripción del Código
Clase "Cuerpo"
Se ha creado una clase llamada "Cuerpo" con atributos esenciales, como masa, posición, constantes y distancias. Los atributos X e Y almacenan valores para cada posición. Las funciones principales de la clase son:

cal_a: Calcula la aceleración de un cuerpo debido a la influencia de otros.
update_pos: Actualiza la posición del cuerpo.
update_vel: Actualiza la velocidad del cuerpo en cada paso de tiempo.
cal_energy: Calcula la energía para evaluar la precisión de la simulación.
Dependencias
numpy: Biblioteca para operaciones numéricas.
matplotlib.pyplot: Biblioteca para la creación de gráficos y visualizaciones.
Uso del Código
Definición de Condiciones Iniciales:

Establezca la altura del satélite sobre la superficie terrestre.
Configure la masa del satélite y otras constantes relevantes.
Parámetros de Simulación:

Ajuste el paso de tiempo y el número total de pasos para la simulación.
Ejecución de la Simulación:

Ejecute el programa para obtener la trayectoria simulada del satélite.
Análisis de Resultados:

Utilice matplotlib para visualizar y analizar las órbitas generadas.
