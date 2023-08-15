## SISTEMA-DE-CONTROL-DE-AGUA-EN-POZOS
Proyecto que conlleva a la sostenibilidad e sustentabilidad en el mundo actual y futuro.  

##### USOS CONSUNTIVOS DEL AGUA

La cantidad de agua que consumen los diferentes sectores difiere entre países y regiones debido a sus características ambientales, socioeconómicas y poblacionales.
La agricultura, con excepción de Europa, es el mayor sector consumidor de agua a nivel mundial (entre 70 y 90% del total), seguido del sector público (entre 7 y 
18%) y, en menor proporción, el sector industrial (de 1 a 11%; Aquastat-FAO, 2018).

En México, la Conagua clasifica a los consumidores de agua en tres sectores: agrícola, abastecimiento público e industrial.7 En 2017, el volumen que se concesionó a 
estos usos consuntivos fue 21% mayor al registrado en 2001, pasando de 72.7 a 87.9 kilómetros cúbicos; esta última cifra representa el 19.2% del agua renovable 
total (451.6 km3 ). En 2017, además de los 87.9 kilómetros cúbicos concesionados a los sectores antes mencionados, se concesionaron 183 kilómetros cúbicos 
adicionales para usos no consuntivos,8 en particular, para la generación de electricidad en hidroeléctricas.

Si se detalla la concesión de agua en 2017 a los tres usos consuntivos principales se observa que 66.8 kilómetros cúbicos le correspondieron al sector agrícola 
(76.3% del total concesionado), 12.6 km3 al abastecimiento público (14.4%) y 8.5 km3 a la industria: 4.3 a la industria autoabastecida (4.9%) y 4.2 a energía 
eléctrica excluyendo hidroelectricidad (4.7%). El sector que más ha crecido en cuanto al volumen concesionado entre 2001 y 2017 fue el abastecimiento público, que 
se incrementó 32.8%, mientras que los sectores agrícola e industrial aumentaron 18.3 y 26.9% (Figura 6.8; IB 2.1-2).

![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/SISTEMA-DE-CONTROL-DE-AGUA-PLUVIAL/assets/136390705/0744cc0d-63eb-4cc6-a179-fb14e34ac579)

###### ABASTECIMIENTO PÚBLICO

El agua para el abasto público corresponde a la que se entrega por las redes de agua potable y que abastece a los usuarios domésticos, así como al sector público 
urbano. Es el sector con el segundo mayor consumo de agua en el país: en 2017 utilizó el 14.4% del volumen total concesionado, siendo su principal fuente de abasto 
los acuíferos (58% del volumen para este uso, 7 378 hm3 ); no obstante, puede observarse que durante el periodo 2001-2017 la demanda de agua superficial asignada a 
este sector creció 59% (pasó de 3 306 a 5 250 hm3 ; Figura 6.14).

![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/SISTEMA-DE-CONTROL-DE-AGUA-PLUVIAL/assets/136390705/2c255853-5847-4f3f-93df-d5e2ff031654)

##### EL USO DE AGUA EN LA INDUSTRIA

La industria autoabastecida y de generación de energía eléctrica utilizó alrededor del 9% del agua concesionada en 2017 (Conagua, 2017a y 2017b). Con respecto a su 
fuente de abasto, lo dominan las aguas superficiales (osciló entre 68 y 77% en el periodo 2001 y 2017, esto es, entre 5 074 y 5 659 hm3 respectivamente), sin 
embargo, la extracción de agua subterránea para la industria aumentó poco más del 68.6% entre 2001-2017 alcanzando 2 683 hm3 ; Figura 6.15).

![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/SISTEMA-DE-CONTROL-DE-AGUA-PLUVIAL/assets/136390705/753af251-8e2f-407c-9e36-c09acbc76371)

#### REALIZACION DEL PROTOTIPO 


#### Materiales
A continuación se enlistará primero los materiales por parte del kit que se usarán. Cabe aclarar que este proyecto está pensado para hacerse en un grupo de tres debido a la cantidad necesaria de productos electrónicos como sensores y demás:

    Sensores de flujo de agua (3 piezas)
    ESP32-CAM (3 piezas) - En este caso usamos una tarjeta ESP32-WROOM por falta de una tercer tarjeta ESP32-CAM, pero no cambia en nada el funcionamiento, sólo el reacomodo de los pins.
    1. RFTDI (2 piezas)
    2. Relé (1 pieza)
    3. HT11 (2 piezas)
    4. Sensor ultrasónico (1 pieza)
    5. Jumpers M-M (20 piezas aprox)
    6. Jumpers M-H (20 piezas aprox)
    7. Electroválvulas 12V DC (2 piezas)
    8. Bomba de agua* (En este caso por el fin de hacerlo a una escala mayor usamos una bomba de 127V, pero la bomba del kit de 5V funciona bien para una escala menor)

A continuación agregaremos también el equipo usado para plomería en caso de que quiera realizarlo a la escala mayor como el proyecto original:

    9. Tubería PVC 1/2" (20 piezas de 5 cm c/u)
    10. Codos PVC 1/2" (4 piezas 90° c/u)
    11. Llaves de paso 1/2" (2 piezas PVC o metal)
    12. Teflón 
    13. Pegamento para tubería PVC hidráulica 
    14. Cinta de aislar


#### Esta es la forma esquematica de la central en la que se administra el pozo 
![padpz](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/SISTEMA-DE-CONTROL-DE-AGUA-EN-POZOS/assets/136390705/058de169-b51a-4062-8f34-560656cefc61)

### De manera esquematica de los ramales para poder monitorear e controlar es de la siguiente manera:

![Untitled Sketch_bb](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/SISTEMA-DE-CONTROL-DE-AGUA-EN-POZOS/assets/136390705/ace79465-b186-4a16-9217-418fb1fc435e)





#33
