<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->

## Robótica Educativa
## CEP Jaén              
Diciembre 2014
![CC](https://licensebuttons.net/l/by-sa/3.0/88x31.png)
## José Antonio Vacas  @javacasm

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->

# Sensores

Los más habituales los de visión

Otros:

* Magnéticos
* De contacto
* De luz

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->

## Visión artificial: 

No siempre vemos de la misma manera
(visión cuando conducimos)

Tampoco nos interesa

Superposición de las sensaciones = 
Resultado final -> Percepción

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->
## ¿Visión?"
Puede ser muy diferente de lo que entendemos:
* Otro tipo de ojos 
 - insectos: ojos compuestos de sensores independientes, ejemplo de como ve una mosca en movimiento
 - ojos de precisión: 
   * sensores en determinados puntos aseguran la alineación de piezas, ejemplo: colocación de parabrisas en coches por medio de robots
   * alineación de tuneladoras con láser
   * Otras radiaciones
 - sensores de calor en misiles

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->
# Posicionamiento

Detección de la posición:

Posicionamiento por GPS

Posicionamiento por movimiento

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->

# Estado y posición 

Definiremos unas coordenadas que definen el estado y/o posición de la maquina.

Estos valores pueden estar referidos a un sistema **absoluto** e independiente de la máquina o 
Definidos de una forma **relativa** como si la máquina fuera el centro del universo.

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->

# Coordenadas

Necesitamos las coordenadas absolutas porque nuestra maquina está incluida en el mundo y además nuestro objetivo es que interaccione con él

Las coordenadas relativas son las más sencillas de usar y representan el estado de nuestra maquina

Estas coordenadas relativas no tienen que ser independientes sino que están relacionadas con su geometría.

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->

## Transformaciones

Para poder controlar nuestra maquina tendremos que programar operaciones de transformación entre ambas, tanto en sentido directo como inverso.

Habitualmente sabemos en que punto del espacio queremos posicionar nuestra herramienta.

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->

# Mapa sensorial 
(Ejemplo mapa de contaminación sonora o lumínica)

Las lecturas de todos los sensores se pueden agrupar en un mapa, del que podemos tomar "imágenes"

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->

# Procesamiento de imágenes

Podemos aplicar técnicas tradicionales de reconocimiento y procesamiento de imágenes

Los ojos pueden ser:
* en color
* en escala de grises
* en blanco y negro

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->
# Sensores

Nuestro robot tendrá: 

* 2 en blanco y negro  (digitales) 

* 2 en escala de grises (analógicos)

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->

# Actuadores y accionamiento

Tenemos un conjunto de variables que definen el estado de las salidas. 

A veces usaremos: 
* variables digitales (on/off), 
* otras veces analógicas (movimiento, giro, velocidades, aceleraciones)

En función del programa  elaboraremos una **estructura de decisiones**

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->

# Funcionalidades

El software define el comportamiento

***

<!-- background: #184bc6-->
<!-- color: #fff -->
<!-- font: centurygothic -->

# Comportamientos

Huyeluz:  http://diwo.bq.com/programando-un-huyeluz/

No te caigas: http://diwo.bq.com/programando-el-no-te-caigas/

Sigue líneas: http://diwo.bq.com/programando-un-siguelineas/