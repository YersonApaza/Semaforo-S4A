# Semaforo-S4A
Educación Especialidad de Informatica - 2021 
Semáforo programable con Arduino
y S4A
Materiales
• Arduino UNO R3
• 3 Leds de colores (Amarillo, Rojo, Verde)
• 2 pulsadores
• Conectores Macho Macho.
• Resistencia
• Software S4A versión 1.6
• Firmware “S4AFirmware16.ino” en Arduino
Programación
La programación se basa en la construcción de objetos y variables de tipo entero,
Las luces del semáforo que tiene propiedades como disfraces que indica si esta encendido la luz o
apagado,
la representación de un reloj esta construido en un bucle “while” que en S4A es el bloque de control
“por siempre” que espera 1 segundo para continuar la siguiente secuencia de luces.
El objeto interruptor esta representado en un bloque de control “repetir hasta que” que verifica si el
interruptor  es presionado y deja de ser presionado para enviar una señal al objeto luz para que se
pueda encender 1 segundo y  sume mas 1 al contador temporal para asignarle el tiempo de esa luz,
el bucle se repetirá hasta que el segundo pulsador es presionado para continuar con la siguiente luz.
Las variables son “Tiempo Temporal” que se suma al terminar de hacer una pulsación al interruptor
pulsador 1.


<img src="https://github.com/YersonApaza/Semaforo-S4A/blob/main/WhatsApp%20Image%202021-06-22%20at%207.19.33%20PM.jpeg" width="250">
yapazat@unsa.edu.pe - https://www.facebook.com/Club-de-genios-113412387648600
