# Etapa 2: Control Básico de Servomotores

Esta etapa establece el control fundamental de servomotores conectados al Arduino, primero de forma individual y luego en paralelo.

## Objetivos

- Conectar servomotores de forma segura.
- Realizar pruebas básicas de movimiento con valores fijos.
- Validar fuentes de alimentación para múltiples servos.

## Subetapas

### 2.1 Prueba Individual
- Conexión de un servomotor a un pin PWM.
- Uso de la librería `Servo.h`.
- Prueba de funcionamiento con `.write(90)`.

### 2.2 Movimiento Manual
- Escritura de ángulos fijos: 0°, 90°, 180°.
- Observación de respuesta del servo y comportamiento mecánico.

### 2.3 Prueba de los 5 Servomotores
- Conexión de los 5 servos a pines PWM.
- Control manual e independiente de cada servo.

### 2.4 Fuente de Alimentación Externa
- Uso de baterías externas para evitar sobrecarga del pin 5V del Arduino.
- Conexión del GND de baterías al GND del Arduino (referencia común).

## Archivos

- `main.ino`: Código para mover servos individual y colectivamente.
- `ControlServo.h/.cpp`: Clase para encapsular el control de un servo motor.

## Resultados Esperados

- Movimiento fluido en todos los servos.
- Comportamiento estable con alimentación adecuada.
- Código modular para facilitar pruebas posteriores.


