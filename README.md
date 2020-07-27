# TRABAJO DE INVESTIGACIÓN N° 2
## 1. TEMA: INTRODUCCIÓN A LA PROGRAMACIÓN POR BLOQUES DE ARDUINO EN TINKERCAD
## 2. PLANTEAMIENTO DEL PROBLEMA
La utilización de Arduino hoy en día es muy demandada en proyectos de electrónica, ya que al ser una plataforma libre y de código abierto, los usuarios pueden modificar los requerimientos a sus necesidades, debido a que incorpora un microcontrolador y un entorno de desarrollo que permiten que todo esto sea posible.

En nuestro caso, al ser un entorno virtual en el cual vamos a trabajar, utilizaremos el Arduino UNO que incorpora Tinkercad, realizando la programación de un circuito mediante un entorno de desarrollo gráfico (Programación por bloques). El propósito de este trabajo de investigación es analizar los aspectos de hardware que ofrece un Arduino, haciendo énfasis en la entrada y salida de información. 
Esto se determinará a partir de la fundamentación correspondiente a los componentes que conforma un Arduino, su funcionalidad y aplicándolo a un circuito, en nuestro caso, a la operatividad de un sistema de semáforos, donde las entradas, corresponden al control de la modalidad en la que funcionan los mismos (modo habitual o modo precaución) y las salidas a los indicadores, los cuales ilustran que todo funcione correctamente. 

## 3. OBJETIVOS
### 3.1 OBJETIVO GENERAL
Implementar y analizar en base a la información de datos de entrada y salida de un Arduino, un circuito en el cual se muestre el funcionamiento del mismo, a través de la programación en un entorno gráfico y uso del Arduino en tinkercad, con el fin de entender el comportamiento del sistema de hardware que ofrece esta plataforma
### 3.2 OBJETIVOS ESPECÍFICOS
- Investigar la funcionalidad y la composición del hardware de un Arduino y el funcionamiento de cada componente que lo conforma, haciendo énfasis principalmente en las entradas y salidas de información
-	Desarrollar la programación, mediante un entorno gráfico en Tinkercad (Diagrama de bloques) para el circuito a implementar (Sistema de semáforos) observando su funcionalidad y como lo aplicamos dentro de nuestro circuito.
-	Entender el funcionamiento de la entrada y salida de datos que nos ofrece el uso del Arduino aplicado en el circuito implementado. Todo esto con el apoyo de la investigación que se habrá realizado y de los artículos de diferentes autores que permitan tener una idea mucho más clara y significativa de lo que está por realizarse, relacionándolos a su vez, con nuestro circuito/programa.
## 4. ESTADO DEL ARTE
### Influencia de Arduino en el desarrollo de cursos avanzados de microcontroladores
Fue desarrollado por Juan Carlos Martinez Santos, Oscar Acevedo Patino y Sonia H. y publicado el 29 de noviembre del 2017. [1].

En este artículo se nos describe el desarrollo de cursos en el campo del diseño digital que utilizan placas Arduino como sus principales plataformas. Arduino ofrece un entorno de desarrollo intuitivo y múltiples recursos de hardware y software que permiten el desarrollo rápido de proyectos basados en microcontroladores aquí se nos presenta una metodología que introduce el estudio de los microcontroladores que utilizan Arduino para desarrollar diferentes tipos de proyectos y procede a estudiar la arquitectura del sistema para obtener el control del dispositivo. 
Este tipo de enseñanza se ha utilizado en un curso de pregrado en microcontroladores y un curso de posgrado en técnicas avanzadas en diseño digital, gracias a esto las personas que participaron dentro de esta metodología presentaron mejoras en sus habilidades al momento de diseñar sus propios controladore.

La metodología de esta consiste en hacer uso del Arduino para desarrollar o diseñar nuestros propios microcontroladores en base a este, ya el Arduino presenta un hardware con el cual podemos conectar a la placa principal, las bibliotecas de código que se pueden usar con este las diferentes formas de programación que se pueden aplicar en este además de que existen gran cantidad de proyectos, videos tutoriales por si no encontramos o no entendemos cómo implementar una idea dentro de nuestro diseños.

JC Martínez-Santos, O. Acevedo-Patino y SH Contreras-Ortiz, "Influencia de Arduino en el desarrollo de cursos avanzados de microcontroladores", en IEEE Revista Iberoamericana de Tecnologías del Aprendizaje, vol. 12, no. 4, pp. 208-217, noviembre de 2017.

Este artículo nos da una idea sobre el funcionamiento del Arduino, sus usos y aplicaciones y de esta manera poder implementarlo en el diseño de un proyecto, incluso en crear y desarrollar nuestros propios microcontroladores, en base al mencionado Arduino. 

### API para la comunicación entre LabVIEW y Arduino UNO
Fue desarrollado por F. J. Jiménez, F. R. Lara y M. D. Redel y publicado el 08 de septiembre de 2014. [2]

En este documento presenta una API para la comunicación entre las plataformas Arduino y LabVIEW, proponiendo una estructura flexible para la programación que sirva como plantilla para cualquier proyecto que desee realizar y optimice el tiempo de desarrollo de estas. 

Propone el uso de la plataforma Arduino UNO, que es hardware abierto y de bajo costo, siendo su software de desarrollo de código abierto y gratuito. Los proyectos que pueden abordarse con la estructura propuesta pueden ser de varios tipos, adquisición de datos, control, hardware en bucle, monitoreo de procesos, creación rápida de prototipos, tanto para educación como para investigación.

Para optimizar el tiempo de desarrollo de aplicaciones entre estas plataformas, se ha desarrollado una estructura inicial en los códigos de ambas, que se traducen en una API de comunicación de propósito general, flexible y de cómoda implementación, facilitando la interconexión y transmisión de datos, con independencia del tipo de aplicación o proyecto en el que se integre, se muestra el contenido y estructura de la API desarrollada facilitando de este modo la labor de todos aquellos desarrolladores que deseen trabajar con ambas plataformas de forma conjunta.

F. Javier Jiménez, F. Ramón Lara y M. Dolores Redel, "API para la comunicación entre LabVIEW y Arduino UNO", en IEEE Latin America Transactions, vol. 12, no. 6, págs. 971-976, septiembre de 2014

Como podemos observar, aquí tenemos un ejemplo de cómo el Arduino puede ser utilizado junto a otra plataforma programable, también usada para la toma de datos, cuyas versatilidades son una ventaja para aplicaciones que solventen necesidades enfocadas a un determinado propósito.

### Sincronización de tiempo en redes de sensores inalámbricos basados en Arduino
En este artículo se nos presentan como las redes de sensores inalámbricos han atraído mucha atención debido a su amplia variedad de aplicaciones, que van desde la gestión de inventario hasta la vigilancia en el campo de batalla. En la mayoría de los casos, una sincronización de tiempo precisa de los nodos es esencial para proporcionar una referencia de tiempo común y facilitar acciones coordinadas. 

Sin embargo, surgen desafíos importantes cuando los nodos de la red se sincronizan con osciladores de bajo costo y baja estabilidad, además de sufrir un fuerte consumo de energía y limitaciones de capacidad computacional. Además, los protocolos de comunicación inalámbrica utilizados por esos nodos simples a menudo tienen desventajas funcionales y de rendimiento. En base a eso, este documento presenta una técnica de sincronización para redes de sensores basadas en Bluetooth pobladas por nodos de detección altamente limitados de recursos. En este papel, Los principales factores que influyen en la sincronización horaria se caracterizan y validan experimentalmente en un sistema real, incluidos los canales de comunicación Bluetooth. Al final, la técnica de sincronización propuesta se implementa y evalúa en una red inalámbrica de sensores basada en Arduino, cuya aplicación motivadora es la localización de eventos acústicos. [3]

MS Perez y E. Carrera, "Sincronización de tiempo en redes inalámbricas de sensores basadas en Arduino", en IEEE Latin America Transactions , vol. 13, no. 2, págs. 455-461, febrero de 2015

En esta aplicación de Arduino vemos su uso para la toma de datos, dado su fácil manejo de hardware, en el cual se presentan diferentes usos que puede tener y a su vez ver cuán versátil es el hardware en el que se puede trabajar, que no solo se basa en una simple programación para un circuito pequeño si no que puede llegar a ser usado a mayores escalas, como en este caso en comunicación de redes inalámbricas.

## 4. MARCO TEÓRICO
### Arduino
Arduino es una plataforma de creación de electrónica de código abierto, la cual está basada en hardware y software libre, flexible y fácil de utilizar para los creadores y desarrolladores. (F, 2018).

En este caso nos enfocaremos en el Arduino UNO, una placa electrónica basada en el chip de Atmel ATmega328 que tiene 14 pines digitales de entrada / salida, es el Arduino Pinout de los cuales 6 los puede utilizar como salidas PWM, 6 entradas analógicas, un oscilador de cristal de 16 MHz, una conexión USB, un conector de alimentación, una cabecera ICSP y un botón de reset. (Anónimo, 2016).

Los Arduino tienen puertos de entrada y salida y puertos de comunicación. 
-	Pines digitales: Se pueden configurar como entrada para leer o como salida. 
-	Pines analógicos de entrada: Usan un conversor analógico/digital y sirven para leer sensores analógicos como sondas de temperatura.
-	Pines analógicos de salida (PWM): La mayoría de Arduino no tienen conversor digital/analógico y para tener salidas analógicas se usa la técnica PWM. No todos los pines digitales soportan PWM.
-	La técnica PWN es: La modulación de ancho de pulso, o PWM, es una técnica para obtener resultados analógicos con medios digitales. 

El control digital se utiliza para crear una onda cuadrada, una señal conmutada entre encendido y apagado. Este patrón de encendido y apagado puede simular voltajes entre encendido y apagado al cambiar la parte del tiempo que la señal pasa en comparación con el tiempo que la señal pasa.

-	Puertos de comunicación: USB, serie, I2C y SPI.

### Tipos de memoria dentro del Arduino
- SRAM: Donde Arduino crea y manipula las variables cuando se ejecuta. Es un recurso limitado y debemos supervisar su uso para evitar agotarlo.
- EEPROM: Memoria no volátil para mantener datos después de un reset o apagado. Las EEPROMs tienen un número limitado de lecturas/escrituras, tener en cuenta a la hora de usarla.
- Flash: Memoria de programa. Usualmente desde 1 Kb a 4 Mb, donde se guarda el sketch (programa realizado).

### Composición de la placa de Arduino
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

### Entrada y salida, Comunicación
![Captura pines digitales](https://user-images.githubusercontent.com/68835261/88509037-d21eaa80-cfa5-11ea-83d0-26cd44f25c41.JPG)
-	Cada uno de los 14 pines digitales de la Uno puede utilizarse como entrada o salida, utilizando las funciones pinMode(), digitalWrite() y digitalRead(). (En nuestro caso esto último se lo realizaría mediante interfaz gráfica).
-	Funcionan a 5 voltios. 
-	Cada clavija puede proporcionar o recibir un máximo de 40 mA y tiene una resistencia pull-up interna de 20-50 kOhms.
-	El Arduino Uno tiene un buen número de opciones para comunicarse con un ordenador, otro Arduino, u otros microcontroladores. El ATmega328 proporciona comunicación serie UART TTL, que está disponible en los pines digitales 0 (RX) y 1 (TX). 

## 5. DIAGRAMAS
### 5.1 DIAGRAMA DE BLOQUES
![Diagrama 1 1](https://user-images.githubusercontent.com/68835261/88509374-89b3bc80-cfa6-11ea-8997-1676c2785505.JPG)
### 5.2 DIAGRAMA UML (CASO DE USO - CLASE)
![Diagrama 1 2](https://user-images.githubusercontent.com/68835261/88509696-3ee67480-cfa7-11ea-9a2c-ade8d45d317b.JPG)
### 5.3 DIAGRAMA ELÉCTRICO
![Diagrama 1 3](https://user-images.githubusercontent.com/68835261/88510477-acdf6b80-cfa8-11ea-9d0d-b5785377c841.JPG)
### 5.4 DIAGRAMA DE FLUJO
![Diagrama 1 4](https://user-images.githubusercontent.com/68835261/88510457-a650f400-cfa8-11ea-9210-b9224f3dffcb.JPG)

## 6. LISTA DE COMPONENTES
![Tabla 1 1](https://user-images.githubusercontent.com/68835261/88509717-4d349080-cfa7-11ea-88fa-363d8eff20e3.JPG)

## 7. MAPAS DE VARIABLES
### •	Variables utilizadas para el funcionamiento del circuito (Semáforo)
![Figura 1 1](https://user-images.githubusercontent.com/68835261/88512142-ad2d3600-cfab-11ea-8c1f-9ecd9c854610.JPG)
### •	Interfaz de usuario
![Figura 1 2](https://user-images.githubusercontent.com/68835261/88512155-b0c0bd00-cfab-11ea-8d1e-671f58b99825.JPG)
### •	Tabla de variables visibles o no visibles
![Tabla 1 2](https://user-images.githubusercontent.com/68835261/88512178-b74f3480-cfab-11ea-89cd-a7b8f6e6acc0.JPG)

Donde:
- S1 --> Switch 1 (Semáforos en "modo habitual")
- S2 --> Switch 2 (Semáforos en "modo precaución")
- L.V.1 --> Luz Verde (Semáforo vehicular)
- L.A.1 --> Luz amarilla (Semáforo vehicular)
- L.R.1 --> Luz Roja (Semáforo vehicular)
- L.V.2 -->  Luz Verde (Semáforo peatonal)
- L.R.2 --> Luz Roja (Semáforo peatonal)

Ahora bien, necesitamos saber el tipo de cada variable que se ha utilizado, además de la función que realiza cada una en el programa. Esto se ilustra en la tabla 1.3.
![Tabla 1 3](https://user-images.githubusercontent.com/68835261/88512185-bc13e880-cfab-11ea-9229-a0675213ae70.JPG)

## 8. EXPLICACIÓN DEL CÓDIGO FUENTE
### Programación de un Arduino en Tinkercad mediante bloques

El funcionamiento del programa básicamente consiste de estructuras condicionales “If-Else” anidadas, en las que se postulan las diferentes condiciones para que los semáforos funcionen en “modo habitual” o “modo precaución”. (Figura 1.3)
![Figura 1 3 1](https://user-images.githubusercontent.com/68835261/88513659-4e1cf080-cfae-11ea-8a8e-7cd682b366e5.JPG)
![Figura 1 3 2](https://user-images.githubusercontent.com/68835261/88513671-5543fe80-cfae-11ea-9dd3-701fec67655c.JPG)

### - Presionando S1 (Switch 1) 
La primera estructura condicional nos estipula que al momento de presionar el switch 1, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 1.3 – Llave de color rojo), en la que se resuelve todo el algoritmo correspondiente al funcionamiento de un semáforo vehicular y peatonal en su “modo habitual”. Esto quiere decir que la luz verde del semáforo vehicular se encenderá durante dos segundos, debido a que el pasador (pin digital) 13 se encuentra en estado lógico “ALTO” con una espera de 2 segundos. Finalizado el transcurso de este tiempo se apagará y a su vez se encenderá la luz amarilla (pin digital 12) durante 1 segundo. Simultáneamente la luz roja del semáforo peatonal (pin digital 9) se enciende hasta que transcurran los tres segundos, en los cuales ocurrió la primera parte del proceso.

Finalmente, la luz amarilla del semáforo vehicular (pin digital 12) y la luz roja del semáforo peatonal (pin digital 9) se posicionan en el estado lógico “BAJO”. Y la luz roja del semáforo vehicular (pin digital 11) junto con la luz verde del semáforo peatonal cambian su estado lógico a “ALTO” durante 2 segundos. Acabado este proceso, el programa se repetirá hasta cambiar el estado lógico del switch 1.

### - Presionando S2 (Switch 2)
La segunda estructura condicional nos estipula que al momento de presionar el switch 2, el programa ejecutará la secuencia de bloques (Ilustrada en la figura 1.3 – Llave de color celeste), en la que se resuelve el algoritmo correspondiente al funcionamiento de un semáforo vehicular en “modo precaución” que consiste de un total de 4 bloques de código; en el cual, el primer bloque coloca al pin digital 12 (luz amarilla del semáforo vehicular) en estado lógico “ALTO” durante 1 segundo (segundo bloque) y posterior a ello el mismo pin digital cambia al estado lógico “BAJO” (tercer bloque) durante 1 segundo (cuarto bloque). Acabado este proceso, esta secuencia se repetirá hasta cambiar el estado lógico del switch 2. 

###  - Switch 1 y 2 en “ALTO” o en “BAJO”
Si no se cumple ninguna de las combinaciones anteriores, se ejecutarán los tres últimos bloques de código (Figura 1.3 – Llave de color azul). Los cuales representan al apagado de todo el sistema de semáforos, ya que los pines digitales 11, 12 y 13 cambian a estado lógico “BAJO”.

Una de las ventajas de programar un Arduino en Tinkercad, es que además de elaborar el programa mediante bloques podemos visualizar el mismo código de manera “textual”. Y de esta manera tener dos opciones de realización para el programador, dependiendo de cual le resulte más intuitiva, A continuación, mostramos el código que se generó de manera automática en Tinkercad (Figura 1.4).  
![Figura 1 4](https://user-images.githubusercontent.com/68835261/88513763-845a7000-cfae-11ea-993a-17745c8f8a38.JPG)

## 9. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN
En lo que corresponde a la utilización de aplicaciones secundarias para que el programa funcione correctamente, podemos decir que no se ha necesitado de ninguna que influya directamente sobre su programación, ya que Tinkercad ofrece formatos de programación tanto en un entorno textual como gráfico. 

Ahora bien, necesitamos saber cuales son los pasos para poder programar un Arduino en una interfaz gráfica (mediante bloques) en Tinkercad. Para lo cual, debemos:

1.	Seleccionar en la sección de componentes, todos los elementos que se utilizarán en el circuito, entre ellos, el Arduino UNO R3 que incorpora Tinkercad
![DPC 1](https://user-images.githubusercontent.com/68835261/88514524-e071c400-cfaf-11ea-9121-a277e02393f3.JPG)

2.	Conectar todos los componentes electrónicos de entrada y salida en los pines digitales del Arduino, se recomienda utilizar un protoboard para mayor facilidad al momento de realizar las conexiones.
![DCP 2](https://user-images.githubusercontent.com/68835261/88514533-e49de180-cfaf-11ea-9ade-fc630f820a06.JPG)

3.	Dirigirse a la barra de control y seleccionar la opción “Código”
![DCP 3](https://user-images.githubusercontent.com/68835261/88514540-e7003b80-cfaf-11ea-817c-f868ed2d9af5.JPG)

4.	Nos encontraremos con la siguiente interfaz y seleccionaremos la opción de programación mediante “Bloques”. Por default el programa incorpora 4 bloques de código con instrucciones variadas. Entonces procedemos a borrar y a programar nuestro circuito![DCP 4](https://user-images.githubusercontent.com/68835261/88514544-e8c9ff00-cfaf-11ea-8312-736b623b9d66.JPG)

5.	En la siguiente figura se encuentran todos los bloques categorizados (bloques de salida, entrada, notación, control, matemáticas, variables). Entonces seleccionamos, los que sean necesarios y de esta manera dar las instrucciones para que nuestro circuito funcione a nuestra necesidad. En este caso un sistema de semáforos controlados por dos switch de entrada
![DCP 5](https://user-images.githubusercontent.com/68835261/88514553-eb2c5900-cfaf-11ea-8a49-26f272fdd517.JPG)

6.	Una vez que ya se ha realizado la programación (ilustrada en la sección 8. Explicación del código fuente) procedemos a dar clic en “Iniciar simulación” y verificar que el circuito funcione correctamente (Sección 9. Aportaciones)
![DCP 6](https://user-images.githubusercontent.com/68835261/88514582-f8494800-cfaf-11ea-807b-d5dc40d3d765.JPG)

Por otro lado, para el correcto funcionamiento del circuito, hay que tener en cuenta varios puntos específicos. Los cuales son indispensables para no tener ningún inconveniente al momento de ejecutar el circuito. 
-	Los semáforos en “modo habitual” solamente funcionan cuando la entrada (switch 1) se encuentre en estado lógico “ALTO”.
-	El semáforo vehicular en “modo precaución” solamente funciona cuando la entrada (Switch 2) se encuentre en estado lógico “ALTO”.
-	Si los dos switch se encuentran en estado lógico “ALTO o “BAJO” 
(S1=1 && S2=1) || (S1=0 && S2=0) las salidas permanecerán en estado lógico “BAJO”.

Nota: Para programar en Arduino mediante Tinkercad, se requiere de la familiarización con fundamentos básicos de programación (Principalmente sobre estructuras condicionales, lógica booleana) y conocimientos sobre la constitución, funcionalidad y partes de un Arduino.

## 10. APORTACIONES
### Características principales del Arduino UNO
-	Microcontrolador: ATmega328 
-	Voltaje de operación: 5V 
-	Voltaje de entrada (recomendado): 7-12V 
-	Voltaje de entrada (límites): 6-20V 
-	Pines de E/S digitales: 14 (de los cuales 6 proporcionan salida PWM) 
-	Pines de entrada analógica: 6 
-	Corriente DC por pin de E/S: 40 mA 
-	Corriente DC para 3.3V Pin: 50 mA 
-	Memoria Flash: 32 KB de los cuales 0,5 KB utilizados por el bootloader 
-	SRAM: 2 KB (ATmega328) 
-	EEPROM: 1 KB (ATmega328) Velocidad de reloj: 16 MHz

### Fuente de alimentación
Si se implementa un circuito con Arduino de manera física, debemos conocer que hay 3 formas de alimentar el Arduino Uno y son:
-	Barrel Jack.- El Barrel Jack, o DC Power Jack puede ser usado para alimentar tu placa Arduino. El conector cilíndrico suele estar conectado a un adaptador de pared. La tarjeta puede ser alimentada por 5-20 voltios, pero se recomienda mantenerla entre 7-12 voltios. Por encima de 12 voltios, los reguladores podrían sobrecalentarse, y por debajo de 7 voltios, podrían no ser suficientes. 
-	VIN Pin. - Este pin se utiliza para alimentar la placa Arduino Uno utilizando una fuente de alimentación externa. El voltaje debe estar dentro del rango mencionado anteriormente. 
-	Cable USB. - cuando se conecta a la computadora, proporciona 5 voltios a 500mA.

### Analog IN
Si se requiere de la utilización de señales análogas y utilizarlas como datos de información de entrada, debemos conocer, lo siguiente:

-	La placa Arduino Uno tiene 6 pines analógicos, que utilizan ADC (Convertidor de Analógico a Digital). Estos pines sirven como entradas analógicas, pero también pueden funcionar como entradas o salidas digitales.
![Figura 1 5](https://user-images.githubusercontent.com/68835261/88514603-01d2b000-cfb0-11ea-9391-2edbe7cd282a.JPG)
-	El ADC es un circuito electrónico utilizado para convertir señales analógicas en señales digitales. Esta representación digital de señales analógicas permite al procesador, que es un dispositivo digital, medir la señal analógica y utilizarla durante su funcionamiento.
-	Los pines Arduino A0-A5 son capaces de leer tensiones analógicas. En Arduino el ADC tiene una resolución de 10 bits, lo que significa que puede representar una tensión analógica de 1.024 niveles digitales. El ADC convierte el voltaje en bits que el microprocesador puede entender.

### Digial Pins
En nuestro caso, hemos utilizado los pines digitales como entrada y salida de información, para lo cual se necesitó conocer:
-	Los pines 0-13 del Arduino Uno sirven como pines de entrada/salida digital.
-	El pin 13 del Arduino Uno está conectado al LED incorporado. 
-	En el Arduino Uno – los pines 3,5,6,9,10,11 tienen capacidad PWM. 
-	Cada clavija puede proporcionar hasta 40 mA máx. Pero la corriente recomendada es de 20 mA. 
-	La corriente máxima absoluta proporcionada de todos los pines juntos es de 200 mA.

### Ejemplo del encendido y apagado de un LED en Tinkercad
![Figura 1 6](https://user-images.githubusercontent.com/68835261/88514618-0ac38180-cfb0-11ea-99c0-1209806a4047.JPG)

### Ejemplo del encendido y apagado de un LED tres veces consecutivas, mediante un pulsador en Tinkercad
![Figura 1 7](https://user-images.githubusercontent.com/68835261/88514622-0e570880-cfb0-11ea-8ac0-6f0e57374500.JPG)

### Ejemplo del uso y funcionamiento del circuito de semáforos implementado
##### -	Presionando Switch 1 (Semáforos en “Modo habitual”)
![Figura 1 8](https://user-images.githubusercontent.com/68835261/88514631-11ea8f80-cfb0-11ea-877c-55100c5a1c58.JPG)

##### -	Presionando Switch 2 (Semáforo en “Modo Precaución”)
![Figura 1 9](https://user-images.githubusercontent.com/68835261/88514643-1616ad00-cfb0-11ea-9321-c2597d05d3e2.JPG)

##### -	Switch 1 y 2 en “ALTO” o “BAJO” (Semáforos en “Modo Inactivo”)![Figura 2 1](https://user-images.githubusercontent.com/68835261/88514660-1adb6100-cfb0-11ea-92c0-3f15c8843bf9.JPG)

## 11. CONCLUSIONES
-	La implementación del circuito de la operatividad de un sistema de semáforos, se lo ha realizado de tal manera que los datos de entrada y salida que se utilizaron se relacionen entre sí por medio de las instrucciones que se establecieron en el programa elaborado en un entorno gráfico, en el cual se implementaron principalmente estructuras condicionales para cumplir el funcionamiento de dichos semáforos en “modo habitual “ o “modo precaución”, dependiendo del estado lógico en el que se encuentren las entradas (Interruptores) y también de un “delay”, el cual nos permite realizar ciertas instrucciones en lapsos determinados de tiempo. Y de esta manera visualizar que los semáforos interactúen simultáneamente.
-	La familiarización con la funcionalidad de cada componente que conforma a un Arduino (Hardware), en este caso el Arduino UNO, fueron muy importantes para lograr realizar nuestro circuito y entender cómo interactúan, mediante el programa para con los componentes del circuito implementado. Básicamente el cerebro de esta plataforma electrónica es el microcontrolador ATMEGA 328, el cual contiene un total de 28 pines o puertos, y 7 de ellos (correspondientes a los pines digitales) hemos utilizado para la entrada y salida de información, es decir, los correspondientes a los interruptores y LED´s respectivamente. Hay que tener en cuenta que el reloj oscilador del Arduino es fundamental, ya que gracias a él las instrucciones se realizan con respecto a los tiempos que impusimos en las instrucciones del programa. 
Y cuya información se guarda en cada una de las memorias que incorpora esta plataforma (SRAM, EEPROM, FLASH).
-	La realización del programa e implementación del circuito se la realizó en base a todo lo investigado, lo cual tiene que ver con las funcionalidades que ofrece el microcontrolador Arduino, principalmente con lo correspondiente a su Hardware. Y es muy importante saber que la utilización de Arduino hoy en día es muy demandada en proyectos de electrónica, ya que tiene varias ventajas como, por ejemplo: su bajo coste, y su versatilidad, ya que los usuarios pueden modificar los requerimientos a sus necesidades, además que, en nuestro caso, la programación se la realizó en Tinkercad con un entorno de desarrollo gráfico, lo que implica que es muy intuitiva y fácil de utilizar para cualquier tipo de usuario, incluso para los aprendices. 
De hecho, al momento de realizar la investigación con los artículos de los autores investigados, podemos darnos cuenta de la gran cantidad de aplicaciones que tiene un Arduino y que de cierta manera se relaciona con nuestra investigación en cuestión.

## 12. RECOMENDACIONES
-	Se recomienda realizar la investigación única y exclusivamente de los temas a ser tratados durante la ejecución y realización del informe que a su vez sustenten los fundamentos para la elaboración del algoritmo y su programación. 
-	Implementar y declarar correctamente las variables necesarias del programa, de tal manera que permitan realizar el código de programación sin que exista ningún tipo de error al momento de ejecutar y compilar el programa.
-	Si no existe familiarización con la programación mediante interfaz textual, recomendamos realizar el algoritmo de programación en una interfaz gráfica, pues una de las ventajas que tiene Tinkercad es que podemos visualizar las dos interfaces al mismo tiempo. Y de esta manera comprender de manera intuitiva la realización del programa. Incluso, exportar el código generado, para implementarlo en un Arduino físico.

## 13. CRONOGRAMA
![Diagrama 1 5](https://user-images.githubusercontent.com/68835261/88514700-26c72300-cfb0-11ea-8120-5b5da86fb199.JPG)

## 14. BIBLIOGRAFÍA
[1] JC Martinez-Santos, O.Acevedo Patiño y SH Contreras-Ortiz, «Sci-Hub IEEEXplore,» 29 Noviembre 2017. Available:
 https://sci-hub.tw/https://ieeexplore.ieee.org/document/8123929

[2] F. J. Jiménez, F. R. Lara y M. D. Redel, «Sci-Hub IEEExplore,» 08 Septiembre 2014. Available: https://sci-hub.tw/https://ieeexplore.ieee.org/document/6893988

[3] M.S. Perez y E. Carrera, «Sci-Hub IEEEXplore,» 21 Febrero 2015. Available: 
https://sci-hub.tw/https://ieeexplore.ieee.org/document/7055564

Anónimo. (12 de Febrero de 2016). descubrearduino.com. Recuperado el 25 de Julio de 2020, de descubrearduino.com: https://descubrearduino.com/arduino-uno/

F, Y. (3 de Agosto de 2018). Xataka. Obtenido de Xataka: https://www.xataka.com/basics/que-arduino-como-funciona-que-puedes-hacer-uno

## 15. ANEXOS
### 15.1 MANUAL DE USUARIO
El presente manual está diseñado para facilitar el uso del circuito que nos permite simular el funcionamiento de un sistema de semáforos (vehicular y peatonal) en “modo habitual” o “modo precaución”, dependiendo de lo que el usuario desee. 

1. Cuenta en Tinkercad
Si no se ha registrado en Tinkercad, lo primero que debe hacer es crearse una cuenta introduciendo sus datos personales, correo electrónico y contraseña. Tal como se muestra, a continuación:
![MU1](https://user-images.githubusercontent.com/68835261/88514723-2fb7f480-cfb0-11ea-8c17-e17f9ee0633b.JPG)
2.	Una vez creada la cuenta, lo que debe realizar es proceder a ingresar al siguiente enlace: https://www.tinkercad.com/things/47SR1Du4WC6-amazing-turing-amberis/editel?tenant=circuits?sharecode=X6G2rnDSu9DkpmLkTWdmxS-6pCIF9ErHrJYIy8NRPF4
3.	El enlace le llevará a la dirección web en el que podrá ejecutar y simular el circuito en una interfaz de laboratorio virtual que ofrece Tinkercad. Le aparecerá una pestaña en la que tendrá que presionar el botón Iniciar Simulación, tal como se muestra a continuación. 
![MU2](https://user-images.githubusercontent.com/68835261/88514760-3a728980-cfb0-11ea-9fd3-1eae38ebb394.JPG)
4.	Escoja una opción
En este punto tendrá que activar uno de los dos interruptores, y dependiendo de lo que desee se ejecutará y se mostrará mediante los LEDs. El interruptor de la izquierda (Switch 1) controla el funcionamiento de un sistema de semáforos en su “Modo habitual”, mientras que el interruptor de la derecha (Switch 2) controla el funcionamiento del semáforo vehicular en “Modo precaución” (Luz amarilla intermitente). Si usted activa los 2 interruptores al mismo tiempo, los semáforos pasarán a “Modo inactivo” (Semáforos apagados), lo mismo ocurre si desactiva los dos interruptores.

-	Semáforos en “Modo habitual”

![MU4](https://user-images.githubusercontent.com/68835261/88514776-41999780-cfb0-11ea-83cb-7637df125fb8.JPG)

-	Semáforos en “Modo precaución”

![MU5](https://user-images.githubusercontent.com/68835261/88514784-44948800-cfb0-11ea-85f2-6b9072281aa2.JPG)

-	Semáforos en “Modo inactivo”

![MU6](https://user-images.githubusercontent.com/68835261/88514795-48280f00-cfb0-11ea-9b92-98c13a9fabb3.JPG)

## 15. HOJAS TÉCNICAS
![Datasheet Arduino](https://user-images.githubusercontent.com/68835261/88514890-70b00900-cfb0-11ea-817f-e7172293b3b9.JPG)
