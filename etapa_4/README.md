
# Etapa 4: Calibración y Mejora de Señal

Esta etapa introduce técnicas de procesamiento de señales aplicadas al sistema servo–potenciómetro, para aumentar precisión y estabilidad.

## Objetivos

- Calibrar el rango útil del potenciómetro.
- Suavizar la señal para evitar jitter.
- Evitar cambios innecesarios con umbral de histéresis.

## Subetapas

### 4.1 Calibración Fina
- Ajuste de mínimos y máximos del potenciómetro con `constrain()`.
- Mejora del rango útil mapeado al servo.

### 4.2 Suavizado de Movimiento
- Implementación de una media móvil (5 muestras).
- Reducción de oscilaciones visibles y movimiento errático.

### 4.3 Reducción de Ruido (Jitter)
- Introducción de histéresis: solo se actualiza el servo si hay un cambio mayor a X grados.
- Mejora en estabilidad visual y mecánica.

## Archivos

- `LecturaPotenciometro.cpp`: Media móvil y calibración.
- `ControlServo.cpp`: Control con histéresis y velocidad máxima.

## Resultados Esperados

- Señales limpias y control más estable.
- Eliminación de vibraciones pequeñas en servos.
- Mayor precisión al usar potenciómetros ruidosos o de baja calidad.

