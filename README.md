# Codigos_de-_Arduino
Reportes de Arduino hechos en clase
Arduino con sensor ultrasónico:  
Este código emplea un sensor ultrasónico para medir la distancia a un objeto. El sensor emite una señal sonora y calcula la distancia en función del tiempo que tarda en rebotar en el objeto y regresar. La distancia medida puede mostrarse en el monitor serial o usarse para activar LEDs y otros componentes, dependiendo de la proximidad del objeto.

Arduino con sensor LDR y pantalla LCD: 
Este archivo configura un sensor LDR (fotorresistor) y una pantalla LCD. El LDR detecta la intensidad de luz ambiental, y el valor capturado se muestra en tiempo real en la pantalla LCD. Esto resulta ideal para sistemas que controlan o monitorean la iluminación del entorno.

Arduino con sensor LDR: 
Este código utiliza un sensor LDR para medir la luz ambiental y, a partir de su lectura, el Arduino puede controlar otros dispositivos, como encender o apagar LEDs según el nivel de luz. Es una configuración práctica para proyectos de ahorro de energía o sistemas de alarma de luz.

Arduino con sensor DHT11:  
En este archivo, un sensor DHT11 mide temperatura y humedad en tiempo real. El sensor envía los datos al Arduino, que pueden mostrarse en el monitor serial o almacenarse para análisis. Este sistema es útil para monitoreo ambiental en proyectos de domótica o climáticos.

Arduino con comunicación serial: 
Este código configura la comunicación serial del Arduino para intercambiar datos con una computadora u otro dispositivo. La comunicación serial facilita el monitoreo de variables, la depuración del código y el control del Arduino desde software externo, siendo muy útil para enviar datos de sensores y recibir comandos.

Arduino con sensor ultrasónico y pantalla LCD:  
En esta configuración, el Arduino mide distancias con un sensor ultrasónico y muestra el resultado en una pantalla LCD. Es especialmente útil en proyectos donde visualizar la distancia es esencial, como sistemas de aparcamiento o robots de evitación de obstáculos.

Arduinos3erParcial----------------------------------------------------------------------------------------------------------------------------------------------------------------
Display de 7 segmentos:
Este código controla un dado electrónico con un pulsador y un display de 7 segmentos utilizando un Arduino. Al presionar el botón, el dado alterna entre dos estados: rodando números aleatorios del 1 al 6 a intervalos regulares, o detenido mostrando el último número generado. Los números se representan en el display de 7 segmentos mediante patrones de encendido y apagado de los pines correspondientes.

Teclado matricial de 4x4: 
Este código implementa un sistema de autenticación con un teclado matricial de 4x4 conectado a un Arduino. Permite ingresar una clave de 6 dígitos que se compara con una clave maestra predefinida. Si la clave es correcta, enciende un LED verde; si es incorrecta, enciende un LED rojo. Además, muestra en el monitor serial las teclas presionadas y si la clave ingresada fue aceptada o rechazada.

Joystick:
Este código controla un joystick conectado a un Arduino para encender LEDs que representan las direcciones arriba, abajo, izquierda y derecha, según el movimiento del joystick. Además, enciende un LED adicional cuando se presiona el botón del joystick. Los valores del joystick y el estado del botón se leen continuamente, y también se muestran en el monitor serial para depuración.

Botones con LEDs: Combinan la funcionalidad de un botón para entradas digitales con retroalimentación visual mediante el LED incorporado, facilitando la interacción del usuario y mejorando la experiencia en sistemas de control.
