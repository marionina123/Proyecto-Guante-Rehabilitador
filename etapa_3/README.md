# Etapa 3: Mapeo y Control de Servomotores con Potenciómetros

Aquí se integra la lectura de potenciómetros con el control de servos para generar un sistema de entrada-salida dinámica.

## Objetivos

- Mapear correctamente el valor del potenciómetro al rango de ángulos del servo.
- Controlar un servo con un potenciómetro.
- Ampliar a control simultáneo de 5 servos con 5 potenciómetros.

## Subetapas

### 3.1 Mapeo de Valores
- Conversión del rango [0–1023] a [0–180] con `map()`.
- Verificación de ángulos calculados en Monitor Serial.

### 3.2 Control Individual
- Un potenciómetro controla un solo servo.
- Flujo: lectura → mapeo → escritura.

### 3.3 Control Total
- Lectura y escritura de los 5 canales de forma simultánea.
- Observación del tiempo de respuesta y posibles interferencias.

## Archivos

- `main.ino`: Control sincronizado de múltiples servos.
- `LecturaPotenciometro.h/.cpp`: Mapeo y suavizado de entradas.
- `ControlServo.h/.cpp`: Lógica de escritura de ángulos.

## Resultados Esperados

- Movimiento proporcional y suave de cada servo según el potenciómetro.
- Posibilidad de usar sistema para aplicaciones mecánicas precisas.


