# Utilizando el microcontrolador ESP32, VS Code y PlatformIO
Este laboratorio consiste en que el estudiante, mediante el uso del entorno
PlarformIO, el framework de Arduino y el microcontrolador ESP32, practique el
uso de la pantalla LCD 16x2 de 8 bits.
El objetivo de este laboratorio es realizar un sistema que muestre, mediante una
pantalla LCD 16x2, los resultados de 2 mediciones. Las primeras 2 mediciones
simularán, con potenciómetros, sensores analógicos y deben mostrar el resultado
de la lectura del ADC. La tercera medición es un contador (de 8 bits) el cual puede
incrementar o decrementar mediante 2 pushbuttons.
# Parte A: Inicialización y Escritura en Pantalla (10pts)
Implemente una rutina para inicializar la pantalla y mostrar en ella el encabezado
de las 3 mediciones que se realizarán a continuación, como se muestra en el
diagrama de Circuito Sugerido. Esta debe mostrar el siguiente texto en la línea
superior de la pantalla:
Pot1: Pot2: Cont:

# Parte B: Lectura de 1 señal Analógica (30pts)
Implemente una rutina que permita leer en la pantalla el valor del ADC, generado
por un potenciómetro, este debe estar situado debajo del encabezado “Pot1:”.

# Parte C: Lectura de 2 señales Analógicas simultáneamente (30pts)
Implemente una segunda rutina que le permita leer en la pantalla el valor del
voltaje leído por el ADC, generado por el segundo potenciómetro y sitúelo debajo
del encabezado “Pot2:”.
*NOTA: En esta entrega deben funcionar las partes A, B y C de la guía de forma simultánea.

# Parte D: Lectura de 3 señales simultáneamente (30pts)
Finalmente, implemente una rutina para que con dos botones se pueda
incrementar y decrementar un contador de 8 bits, y luego despliegue el valor
actual en la LCD debajo del encabezado “Cont:”. *NOTA: En esta entrega deben funcionar
TODAS las partes de la guía de forma simultánea.
