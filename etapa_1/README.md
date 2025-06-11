# Etapa 1: Lectura de Señales de Potenciómetros

En esta etapa se implementa la lectura básica y múltiple de señales analógicas provenientes de potenciómetros conectados a un Arduino Uno.

## Objetivos

- Verificar conexiones de potenciómetros.
- Leer señales usando `analogRead()`.
- Mostrar valores en el Monitor Serial.
- Preparar el sistema para lectura simultánea de múltiples señales.

## Subetapas

### 1.1 Configuración Inicial
- Conexión de un solo potenciómetro al pin analógico A0.
- Verificación física del cableado.

### 1.2 Lectura Básica
- Uso de `analogRead()` para obtener valores del potenciómetro.
- Visualización en el Monitor Serial y Serial Plotter.
- Observación del rango [0–1023].

### 1.3 Lectura Múltiple
- Conexión de cinco potenciómetros a entradas A0–A4.
- Lectura secuencial con bucle `for`.
- Modularización inicial con clase `LecturaPotenciometro`.

## Archivos

- `main.ino`: Configura la lectura de múltiples potenciómetros.
- `LecturaPotenciometro.h/.cpp`: Implementación de clase para lectura y mapeo.

## Resultados Esperados

- Lecturas semi estables y consistentes de cada potenciómetro.
- Valores que varían con la rotación del eje del potenciómetro.
- Organización inicial del código usando clases y modularización.


