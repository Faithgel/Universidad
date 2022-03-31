## Arquitecturas Antiguas
 Los primeros computadores no contaban con una arquitectura estándar definida, por lo tanto, los programas se escribían cada vez que se necesitara ejecutarlos. Debido a esto no existía el concepto de programa almacenado y estos mismos eran registrados como una sucesión de conexiones eléctricas.
	![[Eniac1.jpg]]

## Arquitectura Clásica de Von Neumann

Von Neumann introdujo el concepto de programa almacenado que permitió la ejecución de las instrucciones sin volver a escribir el código, la primera maquinaria en usar este concepto fue el Computador Automático Electrónico de Variable Discreta, también conocido como EDVAC por sus siglas en inglés.

Esto mismo permitió a los computadores tener más flexibilidad y confiabilidad a la hora de ejecutar instrucciones, siendo mucho menos propensos a errores que los mecanicos, dando así inicio a la era moderna de los computadores.

## Problemas de la Arquitectura Clásica de Von Neumann

Las principales desventajas de esta arquitectura: 
- La longitud de instrucciones está limitada por la longitud de los datos, por lo cual el procesador está obligado a hacer varios accesos a memoria para buscar instrucciones complejas, además de que la velocidad es limitada causada por el efecto cuello de botella, donde un bus de datos e instrucciones impide superponer ambos tipos de acceso.

## Arquitectura Moderna-Harvard

Se es referido a este tipo de arquitectura cuando se es utilizadas memorias físicamente separas para las instrucciones y los datos, suelen utilizarse en Procesadores de señal digital o DSP por sus siglas en inglés que habitualmente son encontrados en productos para el procesamiento de audio y video.

- El término proviene del computador Harvard Mark I, que almacenaba las instrucciones en cintas perforadas y los datos en interruptores.

## Arquitectura Moderna - Hoy

Actualmente, no se emplean estas arquitecturas de manera exacta, puesto que existen mejoras que originan diseños con modificaciones, siendo un ejemplo de esto los procesadores Pentium de Intel.

![[Pentium Architecture.excalidraw]]
Esta posee dos buses de comunicación con la memoria principal que amacena datos e instrucciones, además de dos cachés que permiten acelerar el acceso a la memoria.

![[Caché]]