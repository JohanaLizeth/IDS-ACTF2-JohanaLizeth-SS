# Simulación y Análisis de Señales con la Transformada de Fourier

Este repositorio contiene el desarrollo práctico y computacional de la **Actividad Formativa 2**. El objetivo del proyecto es analizar el comportamiento de señales elementales tanto en el dominio del tiempo como en el dominio de la frecuencia mediante el uso del algoritmo de la Transformada Rápida de Fourier (FFT).

## Contenido del Repositorio
El código se ha modularizado en archivos independientes para facilitar su ejecución y auditoría:
* `Pulso_rectangular.py`: Modelado del pulso cuadrado y su espectro de magnitud (Función Sinc).
* `Funcion_escalon.py`: Simulación de la función escalón unitario y su componente de corriente directa (CD).
* `Funion_senoidal.py`: Representación de una oscilación armónica pura y sus deltas espectrales.
* `Desplazamiento_temporal.py`: Verificación del impacto del desfase temporal en el espectro de fase.
* `Linealidad.py`: Comprobación de la superposición lineal de frecuencias mezcladas.
* `Escalamiento_frecuencia.py`: Demostración del efecto de compresión temporal y expansión frecuencial.

## Tecnologías Utilizadas
* Python 3
* NumPy (Procesamiento numérico y cálculo de la FFT)
* Matplotlib (Generación de gráficos vectoriales)
* Google Colab (Entorno de ejecución en la nube)
