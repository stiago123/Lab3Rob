<h1 align="center"; style="text-align:center;">Laboratory 3: Robotica Industrial Entradas y Salidas</h1>
<p align="center";style="font-size:50px; text-align:center; line-height : 50px;  margin-top : 0; margin-bottom : 0; "> <br> Universidad Nacional de Colombia</p>
<p align="center";style="font-size:50px; text-align:center; line-height : 50px;  margin-top : 0; margin-bottom : 0; "> <br> Robotics</p>
<p align="center";style="font-size:50px; text-align:center; line-height : 40px;  margin-top : 0; margin-bottom : 0; "> <br> Santiago Mariño (samrinoj) - Daniel Pineda (dpinedasi)</p>


<p align="center"; style="font-size:50px; text-align:center; line-height : 30px; margin-top : 0; "> <br>30 de Septiembre de 2022</p>

## Introducción

Este laboratorio tiene como objetivo implementar y utilizar el modulo de entradas y salidas digitales del controlador IRC5 por medio me codigo de RAPID en RoboStudio.

La idea es poder seleccionar la pose deseada para el Robot 1RB140 por medio de una entrada digital y conocer el estado de esta por medio de una salida digital 

## Descripción de la solucón 

- Por medio del software RobotStudio se crean los targets, los path para cada pose deaseada y rutina de escritura. Las posiciones deseadas son:
    * Posición de Home (Todos los ángulos igual a 0)
    * Posición para la montura de la herramienta 
    * Rutina de escritura de las letras SM-DP
- Al controlador de RobotStudio se le crean las 3 entradas y una salida digitales. Se reinicia el controlador y podemos usar estas entradas y salidas en el simulador de I/O
- Por ultimo a cada rutina y posición se le asignan la entreda digital como acción
- Se verifica en la simulación que la acciones solo sucedan despues de activar la entrada digital 

## Vídeo demostrativo
### Simualción RobotStudio
[![Simualcion](http://img.youtube.com/vi/6UFMKc55c4w/0.jpg)](https://www.youtube.com/watch?v=6UFMKc55c4w&ab_channel=DanielPineda)

## Codigo en rapid










	



