# Laboratorio No. 2 - Robótica Industrial - Análisis y Operación del Manipulador Motoman MH6

## Integrantes

* Sergio Andrés Bolaños Penagos
* Sergio Felipe Rodriguez Mayorga

## Introducción

## Objetivos

## Movimiento EPSON T3-401S
* Descripci´on de las configuraciones home del EPSON T3-401S, indicando la posici´on de cada articulaci´on.
* Describir el procedimiento y cu´ales teclas se usan para realizar el movimiento manual del manipulador EPSON T3-401S por articulaciones, cambiar a movimientos cartesianos y realizar movimientos de traslaci´on y rotación en los ejes X, Y, Z.
* Detallar los niveles de velocidad del EPSON T3-401S para movimientos manuales y su configuraci´on, ¿C´omo se hace el cambio entre niveles de velocidad?, ¿C´omo se identifica en la pantalla el nivel de velocidad establecido?

## Comparación especificaciones técnicas Motoman MH6, ABB IRB140 y EPSON T3-401S
* Comparar las especificaciones t´ecnicas del EPSON T3-401S, Motoman MH6 y el ABB IRB140 en un cuadro comparativo. incluyendo carga m´axima, alcance, n´umero de grados de libertad, velocidad, aplicaciones t´ıpicas, etc.

## Características EPSON RC+ 7.0
* Describir las diferencias entre los diferentes tipos de trayectorias disponibles en el sofware EPSON RC+ 7.0.
* Explicar las aplicaciones principales de EPSON RC+ 7.0 y c´omo se comunica con el manipulador, ¿Qu´e hace EPSON RC+ 7.0 para mover el manipulador?

## Comparación RC+ 7.0, RobotStudio y RoboDK
* Analizar las diferencias entre EPSON RC+ 7.0, RoboDK y RobotStudio y describir los usos espec´ıficos de cada herramienta, ¿Qu´e significa para usted cada una de esas herramientas?
* Destacando ventajas, limitaciones y aplicaciones de cada herramienta.

## Diseño Gripper
* Dise˜nar un gripper neum´atico por vac´ıo utilizando las entradas y salidas digitales del robot EPSON T3-401S, que tenga la capacidad de levantar un huevo de manera segura y estable.
* Incluyendo diagrama esquem´atico, componentes utilizados y configuraci´on de las E/S digitales del robot.

## Diseño y programación de trayectoria
* Diagrama de flujo de la rutina de movimiento de huevos con patr´on de caballo de ajedrez.
* Dise˜nar y programar una trayectoria en EPSON RC+ 7.0 que permita manipular dos huevos ubicados inicialmente en los extremos de una cubeta de 30 huevos (6x5). La rutina debe posicionar los huevos en todas las posiciones de la cubeta, moviendo un huevo y luego el otro alternadamente, con la restricci´on de que los huevos solo pueden moverse siguiendo el patr´on de movimiento del caballo en el ajedrez.
* C´odigo desarrollado en EPSON RC+ 7.0 para ejecutar la trayectoria con patr´on de caballo, adjuntado como
 anexo dentro del repositorio.

## Resultados

* Video de simulaci´on en EPSON RC+ 7.0 mostrando la trayectoria completa y evidencia de su implementaci´on física en el manipulador EPSON T3-401S.

* Video demostrativo del gripper neum´atico levantando un huevo de manera segura.