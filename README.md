# Universidad de Guadalajara
## Centro Universitario de Ciencias Exactas e Ingenierías
### Ing. Biomédica
#### Materia: Métodos biomédicos de IA
Profesor: Daniel Farfán

### Caso Práctico 4 - GAN: Generación de Imágenes de Tumores Cerebrales
##### Integrantes del equipo:
  * Héctor Manuel Godínez Lozano
  * José de Jesús González Hernández
  * Diana Romina Miranda Grijalva

Este proyecto está inspirado en el repositorio de GitHub [BrainTumor](https://github.com/KSH0660/BrainTumor.git). Nuestro objetivo es construir y entrenar una Generative Adversarial Network (GAN) para generar imágenes de tumores cerebrales.

## Objetivos

- **Construir un modelo GAN**: Definir y compilar un modelo GAN utilizando PyTorch.
- **Entrenar el modelo**: Utilizar conjuntos de datos de entrenamiento para entrenar el modelo.
- **Evaluar el rendimiento**: Evaluar el rendimiento del modelo durante el entrenamiento.
- **Generar imágenes**: Utilizar el modelo entrenado para generar nuevas imágenes de tumores cerebrales.
- **Visualizar resultados**: Visualizar las imágenes generadas por el modelo.

## Estructura del Proyecto

1. **Preparación del Entorno y los Datos**: Configuración del entorno de CUDA y definición de las transformaciones necesarias para las imágenes.
2. **Definición del Modelo GAN**: Implementación de las clases para el generador y el discriminador.
3. **Entrenamiento del Modelo**: Configuración de los optimizadores, la función de pérdida y entrenamiento de la GAN utilizando un bucle de entrenamiento.
4. **Generación de Imágenes Falsas**: Utilización del generador entrenado para crear y visualizar imágenes de tumores cerebrales.

## Instalación

### Requisitos

- Python 3.6 o superior
- PyTorch
- torchvision
- PIL
- IPython

### Instalación usando Conda

```bash
# Crear un nuevo entorno virtual
conda create -n gan_env python=3.8

# Activar el entorno virtual
conda activate gan_env

# Instalar las dependencias
conda install pytorch torchvision pillow ipython
```

## Referencias
Inspirado en el repositorio de GitHub [BrainTumor](https://github.com/KSH0660/BrainTumor.git).
