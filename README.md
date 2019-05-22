# RobotCarTemplate
Plantilla para el robot car de arduino

El presente proyecto contiene la librería "RobotCar.h" que controla el Carro Robot Arduino de dos motores.

HARDWARE:
El primer paso es armar el Robot Car, para la parte del armado dejo el siguiente enlace donde muestra con imágenes paso a paso lo que se debe hacer:
https://robotarduinoues.blogspot.com/2019/05/armando-el-robot.html

Una vez armado el robotCar, descarga esta libreria y agregala a Arduino la libreria expone las siguientes clases:
*****************     *****************
*  Ultrasonido  *     *   Carro       *
*****************     *****************
* pinEcho       *     * ancoderI      *
* pinTrigger    *     * ancoderD      *
* distancia     *     * adelanteI     *
*****************     * atrasI        *
* medir()       *     * potenciaI     *
*****************     * adelanteD     *
                      * atrasD        *
                      * potenciaD     *
                      * sensortrigerC *
                      * sensorechoC   *
                      * sensortrigerI *
                      * sensorechoI   *
                      * sensortrigerD *
                      * sensorechoD   *
                      * *UltraC       *
                      * *UltraI       *
                      * *UltraD       *
                      * contaI        *
                      * contaD        *
                      *****************
                      * mover()       *
                      * girar()       *
                      *****************
                      
Estas clases seran el punto de partida, de aqui podra agregar la programación necesaria para incorporar el funcionamiento.
Los miembros: UltraC, UltraI y UltraD representan los sensores ultrasonido del centro, izquierda y Derecha, estos miembros se implementan como punteros

Queda en sus manos ahora el programar y desarrollar la funcionalidad requerida.
