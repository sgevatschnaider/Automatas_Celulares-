# Autómatas Celulares

Este repositorio contiene estudios y simulaciones sobre **autómatas celulares**, que son modelos matemáticos utilizados para simular sistemas complejos en los cuales las reglas simples generan patrones complejos. Los autómatas celulares han sido aplicados en áreas como la física, biología, matemáticas, y ciencias de la computación.

## Contenido

- [Descripción General](#descripción-general)
- [Archivos y Simulaciones](#archivos-y-simulaciones)
- [Cómo Usar los Notebooks](#cómo-usar-los-notebooks)
- [Recursos Adicionales](#recursos-adicionales)
- [Colaboración](#colaboración)
- [Licencia](#licencia)

## Descripción General

Un **autómata celular** es un modelo compuesto por una malla de celdas (una dimensión o más), donde cada celda puede tener un número finito de estados. El estado de cada celda cambia en pasos discretos de tiempo, de acuerdo con un conjunto de reglas que dependen del estado de las celdas vecinas.

Algunas aplicaciones comunes de los autómatas celulares incluyen:

- Simulaciones físicas: Modelado de fenómenos como el flujo de fluidos o la propagación de incendios.
- Vida artificial: Simulaciones de comportamiento en organismos simples, como el famoso **Juego de la Vida** de Conway.
- Sistemas autoorganizados: Estudio de patrones emergentes en sistemas complejos y dinámicos.

Este repositorio incluye notebooks interactivos que exploran estos conceptos y permiten realizar simulaciones para comprender mejor su funcionamiento.

## Archivos y Simulaciones

Aquí tienes una descripción de los archivos clave que puedes encontrar en este repositorio:

- **`docs/introduccion.md`**: Un documento que explica los fundamentos teóricos de los autómatas celulares, cubriendo su historia, las reglas básicas y ejemplos comunes.
  
- **`simulaciones/autómata_unidimensional.ipynb`**: Este notebook explora autómatas unidimensionales, incluyendo la implementación y análisis de la **Regla 110**.

- **`simulaciones/autómata_bidimensional.ipynb`**: Simulación de autómatas celulares en dos dimensiones, explorando patrones emergentes.

- **`ejemplos/juego_de_la_vida.ipynb`**: Simulación interactiva del famoso **Juego de la Vida de Conway**, uno de los ejemplos más conocidos de autómatas celulares.

## Cómo Usar los Notebooks

### Opción 1: Abrir en Google Colab

Puedes ejecutar los notebooks directamente en la nube usando [Google Colab](https://colab.research.google.com/), sin necesidad de instalar nada. Para hacerlo:
1. Haz clic en el botón "Open in Colab" que aparece en la parte superior del notebook.
2. Ejecuta cada celda de código para ver las simulaciones.

### Opción 2: Ejecutar localmente con Jupyter

Si prefieres ejecutar los notebooks en tu máquina local, sigue estos pasos:

1. Clona este repositorio en tu computadora:
   ```bash
   git clone https://github.com/tuusuario/Automatas_Celulares.git
   cd Automatas_Celulares
Instala las dependencias necesarias utilizando pip:

bash
Copiar código
pip install -r requirements.txt
Ejecuta Jupyter Notebook:

bash
Copiar código
jupyter notebook
Abre los notebooks deseados desde la interfaz de Jupyter y ejecuta cada celda de código.

Recursos Adicionales
Si quieres aprender más sobre autómatas celulares y sus aplicaciones, aquí tienes algunos recursos útiles:

The Nature of Code - Autómatas Celulares
Autómata Regla 110 en Wikipedia
Video introductorio al Juego de la Vida - John Conway
Colaboración
Nos encantaría contar con tus aportes. Si tienes ideas o mejoras para este proyecto, no dudes en colaborar. Puedes hacerlo abriendo un issue o enviando un pull request.

Abre un issue si encuentras un error o quieres sugerir una mejora.
Envía un pull request con tus cambios.
Para más detalles sobre cómo contribuir, revisa el archivo CONTRIBUTING.md.
