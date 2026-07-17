![imagen no encontrada](https://centros-investigacion.s3.sa-east-1.amazonaws.com/wp-content/uploads/sites/14/2020/11/logo-itba-site.png)
# **Trabajos Prácticos de Senales e Imagenes Biomédicas** 

*Análisis de Datos en Señales e Imágenes Biomédicas* 

## **16.63 - Procesamiento de Señales e Imágenes Biomédicas** - *2° cuatrimestre 2024* 

### Alumnos:
Costa de Carvalho, Mateus

Jackson, Delfina

Gonzalez, Imanol

Porjolovsky, Martín

**Resumen** 

Este proyecto implementa un pipeline completo de procesamiento de señales de electroencefalografía (EEG) en estado de reposo para la identificación de biomarcadores cuantitativos vinculados a la enfermedad de Parkinson (PD). 
El objetivo principal fue diferenciar pacientes en estadios tempranos de sujetos sanos mediante el análisis de la potencia de ritmos cerebrales en condiciones de ojos cerrados (EC), ojos abiertos (EO) y su reactividad (REO).

Se desarrolló un sistema automatizado en Python para el preprocesamiento, segmentación y extracción de características de señales biomédicas. 
La solución aborda la variabilidad y el ruido inherente a los registros de EEG mediante un algoritmo de segmentación basado en coeficientes de disimilitud, garantizando la estacionariedad de las señales para un análisis espectral preciso. 
Se pudo validar biomarcadores específicos, como el aumento de la potencia relativa Theta y la reducción del ratio Alpha/Theta, como indicadores consistentes de Parkinson temprano.

**Tecnologías Utilizadas** 

Lenguaje: Python
Librerías Especializadas: MNE (procesamiento de EEG), NeuroKit2 (señales biomédicas), SciPy (análisis de señales y filtros), NumPy y Pandas
Visualización: Matplotlib (espectrogramas y PSD)
