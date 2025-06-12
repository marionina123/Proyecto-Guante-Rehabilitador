# Etapa 5: Organización del Código

Etapa dedicada a estructurar, modularizar y escalar el proyecto de forma profesional, manteniendo el código limpio y eficiente.

## Objetivos

- Usar arrays y bucles para evitar duplicación de código.
- Aplicar principios de modularización con `.h` y `.cpp`.
- Aumentar la mantenibilidad y escalabilidad del sistema.

## Subetapas

### 5.1 Modularización
- Separación de funciones en clases `LecturaPotenciometro` y `ControlServo`.
- Encapsulamiento de lógica de lectura y escritura.

### 5.2 Uso de Arrays
- Definición de arrays de pines y objetos para automatizar bucles.
- Reducción de líneas repetidas.

### 5.3 Comentado Extensivo
- Documentación de cada función.
- Explicaciones claras en el código principal (`main.ino`).

## Archivos

- `main.ino`: Control completo de 5 servos con 5 potenciómetros.
- `LecturaPotenciometro.h/.cpp`: Lectura con calibración y suavizado.
- `ControlServo.h/.cpp`: Escritura con histéresis y velocidad limitada.

## Resultados Esperados

- Código compacto y legible.
- Fácil de expandir a más canales si se requiere.


