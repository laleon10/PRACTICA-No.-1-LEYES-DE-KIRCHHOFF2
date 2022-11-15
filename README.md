# PRACTICA-No.-1-LEYES-DE-KIRCHHOFF2
LEYES-DE-KIRCHHOFF
# El objetivo general:

• Explicar y demostrar experimentalmente la ley de voltaje de Kirchhoff y la ley de corriente de Kirchhoff.

# Objetivos específicos:

• Fortalecer la ley de conservación de la electricidad y la ley de conservación de la carga con la ayuda de la simulación. 

• Comprobar la suma de las corrientes con cálculos analíticos.

• Desarrollar un circuito de entrenamiento en el simulador de potencia para comprobar los resultados obtenidos. 

• Correcta aplicación de la segunda ley de Kirchhoff en esquemas prácticos.

# MARCO TEORICO

![6](https://user-images.githubusercontent.com/116819463/201846160-e0286c96-b9b6-490d-a655-c5ca3bfb46e5.png)
![image](https://user-images.githubusercontent.com/116819463/201846217-67bf0e79-3a68-4f24-8b12-a02cc935e180.png)
# MATERIAL Y EQUIPO REQUERIDO

Descripción de equipos y materiales.

Protoboard: un Protoboard es una placa de prueba donde se pueden colocar componentes electrónicos y cables para crear un circuito sin soldar ningún componente.

Resistencia: una resistencia se usa para introducir cierta resistencia entre dos puntos en un circuito. 

Fuente de voltaje: Los componentes activos que pueden transferir energía se denominan fuentes de voltaje. 

Multímetro : Un multímetro es una herramienta que se utiliza para medir dos o más valores eléctricos como la corriente, la resistencia, el voltaje, etc.

Armado del circuito

pasos:
a) Colocamos una energia de 5 voltios

b) Buscamos los resistores con su codigo de colores.

c) Conectamos el circuito

![image](https://user-images.githubusercontent.com/116819463/201865986-80e4cc8d-d9ab-48e1-9e07-199c0cdc5561.png)

Procedemos a medir los voltajes

![image](https://user-images.githubusercontent.com/116819463/201866847-85fdb727-0a0c-4bc2-9377-8db1a11f4416.png)

calculamos los valores teóricos de corriente y voltaje de los elementos pasivos, para completar la tabla:

Aplicamos 
 
la ecuación de la Malla de I1

1kΩ· I1 + 3.9kΩ· I1 + 1.8kΩ· I1 - 3.9kΩ· I2 = 5

la ecuación de la Malla de I2

2.2kΩ· I2 + 2.2kΩ· I2 + 3.9kΩ· I2 - 3.9kΩ· I1 = 0

Unimos terminos 

6.7kΩ· I1 - 3.9kΩ· I2 = 5

8.3kΩ· I2 -3.9kΩ· I1 = 0

Resolver el sistema de ecuaciones por método de reducción de Gauss Jordan:

I1 = 1.027 mA

I2 = 0.4826 mA

Para encontrar I3 se despeja de la ecuación: I1 = I2 + I3

Nos queda que I3 = I1 – I2

I3 = 1.027 - 0.4826

la Ley de Ohm para obtener los voltajes

 VR1 = I1·R1 = 1.027 mA·1kΩ = 1.027 V

 VR2 = I3·R2 = 0.5444 mA·3.9kΩ = 2.12 V
 
 VR3 = I2·R3 = 0.4826 mA·2.2kΩ = 1.06 V

 VR4 = I2·R4 = 0.4826 mA·2.2kΩ = 1.06 V

 VR5 = I1·R5 = 1.027 mA·1.8kΩ = 1.84 V
 
 #llenamos las tablas:
 
 ![image](https://user-images.githubusercontent.com/116819463/201876205-1975e088-5cc9-43b8-a878-1588d6609d0d.png)

  
![7](https://user-images.githubusercontent.com/116819463/201886678-e5f438c4-916b-4cbd-88ad-f7c3d89747f3.png)

Compare los resultados medidos con los valores obtenidos como resultado del análisis del circuito analítico y saque conclusiones.

Se concluye que el mismo valor se obtiene al conectar el amperaje o voltaje con un cálculo analítico, debido a que el valor no debe cambiar y por lo tanto el margen no es grande.

#coclusion:

• La fuente de voltaje que suministra la energía debe estar balanceada con el voltaje perdido por la caída de corriente.

• Las resistencias son responsables de absorber energía y ralentizar el flujo, creando una caída de voltaje. 

• En la práctica de laboratorio, el valor de la corriente que circula por el circuito y su caída de tensión se obtienen teóricamente.

#BIBLIOGRAFÍA

F. (2021). Principles Of Electric Circuits, 8Ed. Pearson.
