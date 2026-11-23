# Prácticas con Arduino

Repositorio de ejercicios introductorios de electrónica y programación con Arduino. Cada práctica es independiente y combina un sketch, cuando está disponible, con archivos gráficos del circuito.

## Stack y tecnologías

- **Plataforma:** Arduino y su entorno Arduino IDE.
- **Lenguaje:** sketches `.ino` escritos en C++ y basados en las funciones de Arduino (`setup()` y `loop()`).
- **Entradas y salidas:** lectura digital y analógica, control de salidas, comunicación serial y generación de tonos.
- **Librerías utilizadas:** `Servo`, `Keypad`, `LiquidCrystal`, `IRremote`, `Adafruit NeoPixel`, `DHT11` y `SoftwareSerial`. La práctica de relé y motor también muestra acceso directo a registros AVR con `avr/io.h`.
- **Recursos de hardware:** imágenes `.png`, archivos de placas `.brd` y un proyecto `.fzz` para consultar el montaje de los componentes.

No hay un único proyecto compilable desde la raíz: cada carpeta se trabaja por separado. Abrí el archivo `.ino` de la práctica en Arduino IDE, seleccioná la placa correspondiente y agregá las librerías externas que esa práctica incluya.

## Prácticas y funcionalidades

### Componentes y salidas

- [Adding Components](adding_components1/), [Wiring Components](wiring_components1/) y [Start Simulating](start_simulating1/): recursos de circuito para las prácticas de incorporación de componentes, cableado y simulación.
- [Editing Components](editing_components1/): secuencia de luces tipo semáforo con tres LED.
- [Pulsador y LED](pulsador_led1/): lectura de un pulsador para controlar un LED.
- [Interruptor](interruptor1/) y [Slide Switch](slide_switch1/): prácticas de entradas con interruptor; la segunda cambia la combinación de colores de un LED RGB.
- [LED RGB](rgb_led1/): control de los canales rojo, verde y azul.
- [Display de 7 segmentos](display_de_7_segmentos1/): control de los segmentos para mostrar dígitos.

### Sensores y lecturas

- [Fotoresistor](fotoresistor1/): lectura de luz y control de un LED según el valor medido.
- [Sensor de gas](gas_sensor1/): lectura del sensor, aviso por puerto serial y señal acústica al detectar gas.
- [Humedad y temperatura](humedad_y_temperatura1/): lectura de un sensor DHT11 y salida de datos por serial.
- [PIR](pir1/): detección de movimiento combinada con una lectura de luz para controlar una lámpara.
- [Potenciómetro](potenci_metro1/): lectura analógica y visualización del valor por serial.
- [Alarma ultrasónica](ultras_nico_alarma1/): medición de distancia, reporte serial y señalización con LED y buzzer al acercarse un objeto.

### Actuadores y sonido

- [Microservo](microservo1/): barrido del servo entre 0° y 180°.
- [Relé y motor DC](relay_y_motor_dc1/): ejemplo de control de salida mediante registros AVR.
- [Piezo buzzer](piezo_buzzer1/): generación de tonos.
- [Marcha Imperial](marcha_imperial1/) y [Star Wars con piezo buzzer](star_wars_piezo_buzzer1/): reproducción de melodías con un buzzer.
- [NeoPixels](neopixels1/): control de una tira o conjunto de LED direccionables.

### Interfaces y comunicación

- [LCD](lcd1/): escritura de texto en una pantalla LCD de 16×2.
- [Teclado](teclado1/): lectura de teclas de un keypad matricial y envío por serial.
- [Control remoto IR](ir_remoto1/): recepción de comandos infrarrojos para controlar LED.
- [Módulo Bluetooth](bluetooth_module1/): comunicación serial entre el módulo Bluetooth y el monitor serial.
