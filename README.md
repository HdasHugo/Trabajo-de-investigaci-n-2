# Trabajo-de-investigación-n-2
# 1. TEMA: INTRODUCCIÓN A LA PROGRAMACIÓN POR BLOQUES DE ARDUINO EN TINKERCAD
# 2. PLANTEAMIENTO DEL PROBLEMA
La utilización de Arduino hoy en día es muy demandada en proyectos de electrónica, ya que al ser una plataforma libre y de código abierto, los usuarios pueden modificar los requerimientos a sus necesidades, debido a que incorpora un microcontrolador y un entorno de desarrollo que permiten que todo esto sea posible.

En nuestro caso, al ser un entorno virtual en el cual vamos a trabajar, utilizaremos el Arduino UNO que incorpora Tinkercad, realizando la programación de un circuito mediante un entorno de desarrollo gráfico (Programación por bloques). El propósito de este trabajo de investigación es analizar los aspectos de hardware que ofrece un Arduino, haciendo énfasis en la entrada y salida de información. 
Esto se determinará a partir de la fundamentación correspondiente a los componentes que conforma un Arduino, su funcionalidad y aplicándolo a un circuito, en nuestro caso, a la operatividad de un sistema de semáforos, donde las entradas, corresponden al control de la modalidad en la que funcionan los mismos (modo habitual o modo precaución) y las salidas a los indicadores, los cuales ilustran que todo funcione correctamente. 

# 3. OBJETIVOS
# 3.1 OBJETIVO GENERAL
Implementar y analizar en base a la información de datos de entrada y salida de un Arduino, un circuito en el cual se muestre el funcionamiento del mismo, a través de la programación en un entorno gráfico y uso del Arduino en tinkercad, con el fin de entender el comportamiento del sistema de hardware que ofrece esta plataforma.
# 3.2 OBJETIVOS ESPECÍFICOS
- Investigar la funcionalidad y la composición del hardware de un Arduino y el funcionamiento de cada componente que lo conforma, haciendo énfasis principalmente en las entradas y salidas de información
-	Desarrollar la programación, mediante un entorno gráfico en Tinkercad (Diagrama de bloques) para el circuito a implementar (Sistema de semáforos) observando su funcionalidad y como lo aplicamos dentro de nuestro circuito.
-	Entender el funcionamiento de la entrada y salida de datos que nos ofrece el uso del Arduino aplicado en el circuito implementado. Todo esto con el apoyo de la investigación que se habrá realizado y de los artículos de diferentes autores que permitan tener una idea mucho más clara y significativa de lo que está por realizarse, relacionándolos a su vez, con nuestro circuito/programa.
# 4. ESTADO DEL ARTE
# Influencia de Arduino en el desarrollo de cursos avanzados de microcontroladores
Fue desarrollado por Juan Carlos Martinez Santos, Oscar Acevedo Patino y Sonia H. y publicado el 29 de noviembre del 2017. [1].

En este artículo se nos describe el desarrollo de cursos en el campo del diseño digital que utilizan placas Arduino como sus principales plataformas. Arduino ofrece un entorno de desarrollo intuitivo y múltiples recursos de hardware y software que permiten el desarrollo rápido de proyectos basados en microcontroladores aquí se nos presenta una metodología que introduce el estudio de los microcontroladores que utilizan Arduino para desarrollar diferentes tipos de proyectos y procede a estudiar la arquitectura del sistema para obtener el control del dispositivo. 
Este tipo de enseñanza se ha utilizado en un curso de pregrado en microcontroladores y un curso de posgrado en técnicas avanzadas en diseño digital, gracias a esto las personas que participaron dentro de esta metodología presentaron mejoras en sus habilidades al momento de diseñar sus propios controladore.

La metodología de esta consiste en hacer uso del Arduino para desarrollar o diseñar nuestros propios microcontroladores en base a este, ya el Arduino presenta un hardware con el cual podemos conectar a la placa principal, las bibliotecas de código que se pueden usar con este las diferentes formas de programación que se pueden aplicar en este además de que existen gran cantidad de proyectos, videos tutoriales por si no encontramos o no entendemos cómo implementar una idea dentro de nuestro diseños.

JC Martínez-Santos, O. Acevedo-Patino y SH Contreras-Ortiz, "Influencia de Arduino en el desarrollo de cursos avanzados de microcontroladores", en IEEE Revista Iberoamericana de Tecnologías del Aprendizaje, vol. 12, no. 4, pp. 208-217, noviembre de 2017.

Este artículo nos da una idea sobre el funcionamiento del Arduino, sus usos y aplicaciones y de esta manera poder implementarlo en el diseño de un proyecto, incluso en crear y desarrollar nuestros propios microcontroladores, en base al mencionado Arduino. 

# API para la comunicación entre LabVIEW y Arduino UNO
Fue desarrollado por F. J. Jiménez, F. R. Lara y M. D. Redel y publicado el 08 de septiembre de 2014. [2]

En este documento presenta una API para la comunicación entre las plataformas Arduino y LabVIEW, proponiendo una estructura flexible para la programación que sirva como plantilla para cualquier proyecto que desee realizar y optimice el tiempo de desarrollo de estas. 

Propone el uso de la plataforma Arduino UNO, que es hardware abierto y de bajo costo, siendo su software de desarrollo de código abierto y gratuito. Los proyectos que pueden abordarse con la estructura propuesta pueden ser de varios tipos, adquisición de datos, control, hardware en bucle, monitoreo de procesos, creación rápida de prototipos, tanto para educación como para investigación.

Para optimizar el tiempo de desarrollo de aplicaciones entre estas plataformas, se ha desarrollado una estructura inicial en los códigos de ambas, que se traducen en una API de comunicación de propósito general, flexible y de cómoda implementación, facilitando la interconexión y transmisión de datos, con independencia del tipo de aplicación o proyecto en el que se integre, se muestra el contenido y estructura de la API desarrollada facilitando de este modo la labor de todos aquellos desarrolladores que deseen trabajar con ambas plataformas de forma conjunta.

F. Javier Jiménez, F. Ramón Lara y M. Dolores Redel, "API para la comunicación entre LabVIEW y Arduino UNO", en IEEE Latin America Transactions, vol. 12, no. 6, págs. 971-976, septiembre de 2014

Como podemos observar, aquí tenemos un ejemplo de cómo el Arduino puede ser utilizado junto a otra plataforma programable, también usada para la toma de datos, cuyas versatilidades son una ventaja para aplicaciones que solventen necesidades enfocadas a un determinado propósito.

# Sincronización de tiempo en redes de sensores inalámbricos basados en Arduino
En este artículo se nos presentan como las redes de sensores inalámbricos han atraído mucha atención debido a su amplia variedad de aplicaciones, que van desde la gestión de inventario hasta la vigilancia en el campo de batalla. En la mayoría de los casos, una sincronización de tiempo precisa de los nodos es esencial para proporcionar una referencia de tiempo común y facilitar acciones coordinadas. 

Sin embargo, surgen desafíos importantes cuando los nodos de la red se sincronizan con osciladores de bajo costo y baja estabilidad, además de sufrir un fuerte consumo de energía y limitaciones de capacidad computacional. Además, los protocolos de comunicación inalámbrica utilizados por esos nodos simples a menudo tienen desventajas funcionales y de rendimiento. En base a eso, este documento presenta una técnica de sincronización para redes de sensores basadas en Bluetooth pobladas por nodos de detección altamente limitados de recursos. En este papel, Los principales factores que influyen en la sincronización horaria se caracterizan y validan experimentalmente en un sistema real, incluidos los canales de comunicación Bluetooth. Al final, la técnica de sincronización propuesta se implementa y evalúa en una red inalámbrica de sensores basada en Arduino, cuya aplicación motivadora es la localización de eventos acústicos. [3]

MS Perez y E. Carrera, "Sincronización de tiempo en redes inalámbricas de sensores basadas en Arduino", en IEEE Latin America Transactions , vol. 13, no. 2, págs. 455-461, febrero de 2015

En esta aplicación de Arduino vemos su uso para la toma de datos, dado su fácil manejo de hardware, en el cual se presentan diferentes usos que puede tener y a su vez ver cuán versátil es el hardware en el que se puede trabajar, que no solo se basa en una simple programación para un circuito pequeño si no que puede llegar a ser usado a mayores escalas, como en este caso en comunicación de redes inalámbricas.

# 4. MARCO TEÓRICO
# Arduino
Arduino es una plataforma de creación de electrónica de código abierto, la cual está basada en hardware y software libre, flexible y fácil de utilizar para los creadores y desarrolladores. (F, 2018).

En este caso nos enfocaremos en el Arduino UNO, una placa electrónica basada en el chip de Atmel ATmega328 que tiene 14 pines digitales de entrada / salida, es el Arduino Pinout de los cuales 6 los puede utilizar como salidas PWM, 6 entradas analógicas, un oscilador de cristal de 16 MHz, una conexión USB, un conector de alimentación, una cabecera ICSP y un botón de reset. (Anónimo, 2016).

Los Arduino tienen puertos de entrada y salida y puertos de comunicación. 
-	Pines digitales: Se pueden configurar como entrada para leer o como salida. 
-	Pines analógicos de entrada: Usan un conversor analógico/digital y sirven para leer sensores analógicos como sondas de temperatura.
-	Pines analógicos de salida (PWM): La mayoría de Arduino no tienen conversor digital/analógico y para tener salidas analógicas se usa la técnica PWM. No todos los pines digitales soportan PWM.
-	La técnica PWN es: La modulación de ancho de pulso, o PWM, es una técnica para obtener resultados analógicos con medios digitales. 

El control digital se utiliza para crear una onda cuadrada, una señal conmutada entre encendido y apagado. Este patrón de encendido y apagado puede simular voltajes entre encendido y apagado al cambiar la parte del tiempo que la señal pasa en comparación con el tiempo que la señal pasa.

-	Puertos de comunicación: USB, serie, I2C y SPI.

# Tipos de memoria dentro del Arduino
- SRAM: Donde Arduino crea y manipula las variables cuando se ejecuta. Es un recurso limitado y debemos supervisar su uso para evitar agotarlo.
- EEPROM: Memoria no volátil para mantener datos después de un reset o apagado. Las EEPROMs tienen un número limitado de lecturas/escrituras, tener en cuenta a la hora de usarla.
- Flash: Memoria de programa. Usualmente desde 1 Kb a 4 Mb, donde se guarda el sketch (programa realizado).

# Composición de la placa de Arduino
![Captura partes arduino](https://user-images.githubusercontent.com/68835261/88507070-312df080-cfa1-11ea-8c21-d2e615ba8267.JPG)
1. Botón de Reset: Sirve para inicializar nuevamente el programa cargado en el microcontrolador de la placa. Cuando deje de responder el Arduino Uno es el botón de encendido o apagado para que vuelva a restablecerse. 
2. Pines o puertos de entrada y salida: son los pines donde conectar los sensores, componentes y actuadores que necesiten de señales digitales.
3. Pines o puertos de entrada y salida: son los pines donde conectar los sensores, componentes y actuadores que necesiten de señales digitales
4. Puerto USB: Utilizado tanto para conectar con un ordenador y transferir o cargar los programas al microcontrolador como para dar electricidad al Arduino. También se usa como puerto de transferencia .
5. Chip de interface USB: es el encargado de controlar la comunicación con el puerto USB. 
6. Reloj oscilador: Es el elemento que hace que el Arduino vaya ejecutando las instrucciones. Es el encargado de marcar el ritmo al cual se debe ejecutar cada instrucción del programa.
7. Led de encendido. Es un pequeño LED que se ilumina cuando la placa esta correctamente alimentada. 
8. Microcontrolador. (ATMEGA 328) Este es el cerebro de cualquier placa Arduino. Es el procesador que se encarga de ejecutar las instrucciones de los programas. 
9. Regulador de tensión: Este sirve para controlar la cantidad de electricidad que se envía a los pines, con lo que asegura que no se estropee lo que conectemos a dichos pines. 
10. Puerto de corriente continua. Este puerto es el que se usa para darle electricidad a la placa si no se usa alimentación USB. 
11. Zócalo de tensión. Aquí estarán los pines con los que alimentaremos nuestro circuito. 
12. Entradas analógicas: Zócalo con distintos pines de entrada analógica que permiten leer entradas analógicas. (Anónimo, 2016).

## Entrada y salida, Comunicación
![Captura pines digitales](https://user-images.githubusercontent.com/68835261/88509037-d21eaa80-cfa5-11ea-83d0-26cd44f25c41.JPG)
-	Cada uno de los 14 pines digitales de la Uno puede utilizarse como entrada o salida, utilizando las funciones pinMode(), digitalWrite() y digitalRead(). (En nuestro caso esto último se lo realizaría mediante interfaz gráfica).
-	Funcionan a 5 voltios. 
-	Cada clavija puede proporcionar o recibir un máximo de 40 mA y tiene una resistencia pull-up interna de 20-50 kOhms.
-	El Arduino Uno tiene un buen número de opciones para comunicarse con un ordenador, otro Arduino, u otros microcontroladores. El ATmega328 proporciona comunicación serie UART TTL, que está disponible en los pines digitales 0 (RX) y 1 (TX). 

## 5. DIAGRAMAS
### 5.1 DIAGRAMAS DE BLOQUES



