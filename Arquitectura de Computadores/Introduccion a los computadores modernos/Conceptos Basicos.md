###### Conceptos Basicos
## Sistema computacional 
Un sistema computacional es conocido como la suma de varios componentes: 

![[Sistema Computacional.excalidraw]]
1. Software 
	- Conjunto de programas y rutinas que permiten a la computadora realizar determinadas tareas.
2. Hardware: 
	- Conjunto de elementos físicos o materiales que constituyen una computadora o un sistema informático.
3. Firmware: 
	- Programa informático que establece la lógica de más bajo nivel que controla los circuitos electrónicos de un dispositivo de cualquier tipo.
## ¿Que es la arquitectura de un computador?

> *“La apariencia funcional que presenta a sus usuarios inmediatos”. (Amdahl,1964)*
- Son los atributos o cracteristicas de un sistema visibles al programador.

- La arquitectura de un "procesador" viene dada por su juego de instrucciones máquina.

## Problemas relativos a la Arquitectura
1. El diseño se convierte en un "arte" más que en una disciplina de ingenieria muy compleja con una metodologia base muy clara.
2. Antiguamente, el diseño estaba guiado sólo por los avances en microelectrónica y la rígida arquitectura de Von Neumann.

4. Hoy en dia, el diseño es basado en el factor tiempo y la ley de Moore

![[Ley de Moore]]

5. El alcance de limites dificilmente superables de la tecnologia hardware: 

	- La búsqueda de mayor rendimiento, se basará en nuevas arquitecturas que exploten en mayor grado las posibilidades del hardware. Un ejemplo es la utilización de tecnologías que aumenten el paralelismo dentro del microprocesador.

6. Límite de costos y ventas

	- La compatibilidad con equipos de tecnología anterior disminuye la potencia de los nuevos equipos. 
		 Ejemplo: familia de procesadores 80x86 de Intel. Ó Pentium corriendo el antiguo sistema DOS.
## Arquitecturas antiguas
 Los primeros computadoress no contabn con una arquitectura estndar definada, por lo tanto los porgramas se escribian cada vez que se necesitara ejecutarlos. Debido a esto no existia el concepto de programa almacenado y estos mismos eran registrados como una sucesion de conexiones electricas 
	![[Eniac1.jpg]]

 ## Arquitectura Clasica de Von Neumann

Von Neuman introdujo el concepto de programa almacenado que permitio la ejecucion de las instrucciones sin volver a escribir el codigo, la primera maquinaria en usar este concepto fue el Computador Automatico Electronico de Variable Discreta tambien conocido como EDVAC por sus siglas en ingles.

Esto mismo permitio a los computadores tener más flexibilidad y confiabilidad a la hora de ejecutar instrucciones siendos mucho menos propensos a errores que los mecanicos dando asi inicio a la era moderna de los computadores.

##Problemas de la Arquitectura Clasica de Von Neumann

Las principales desventajas de esta arquitectura: 
- La longitud de instrucciones esta limitada por la longitud de los datos, por lo cual el procesador esta obligado a ahcer varios accesos a memoria para buscar instrucciones complejas ademas de que la velocidad es limitada causada por el efecto cuello de botella, donde un bus de datos e instrucciones impide superponer ambos tipos de acceso.

## Arquitectura Moderna-Harvard

Se es referido a este tipo de arquitectura cuando se es utilizadas memorias fisicamentes separas para las instrucciones y los datos, suelen usarse en Procesadores de señal digital o DSP por sus siglas en ingles que habitualmente son encontrados en productos para el procesamiento de audio y video.

- El termino proviene del computador Harvard Mark I, que almacenaba las instrucciones en cintas perforadas y los datos en interruptores.

## Arquitectura Moderna - Hoy

Actualmente no se usan estas arquitecturas de manera exacta pusto que existen mejoras que originan diseños con modificaciones sinedo un ejemplo de esto los procesadores Pentium de Intel.

![[Pentium Architecture.excalidraw]]
Esta posee dos buses de comunicacion con la memoria principal que amacena datos e instrucciones ademas de dos cachés que mermiten acelerar el acceso a la memoria.

## ¿Que es la Organizacion de Computadores?
