# Automatización de controles de calidad en Python

Automatización de controles de calidad de un acelerador lineal de Radioterapia por medio de procesamiento de imágenes en Python, usando como base e inspiración la librería [Pylinac](https://pylinac.readthedocs.io/en/latest/).

Se desarrollaron los siguientes módulos durante unas prácticas profesionales supervisadas en Fundación INTECNUS, Bariloche:

- `hemicampos.py`
- `picket_fence.py`
- `campo_radiante_vs_luminoso.py`

## Abstract

En Radioterapia, los aceleradores lineales utilizados para administrar los tratamientos están incluidos en un programa de garantía de calidad. Por lo tanto, es necesario realizar controles periódicos que aseguren su correcto funcionamiento.

Este trabajo presenta la **automatización de una parte esencial de cualquier control de calidad**: el análisis cuantitativo de los resultados, de forma objetiva e independiente del ojo del observador.

Utilizando herramientas propias desarrolladas en Python, así como la librería [Pylinac](https://pylinac.readthedocs.io/en/latest/) y otras librerías auxiliares, se automatizaron los siguientes controles:

- **Picket-Fence**: basado en la implementación ya desarrollada en Pylinac.
- **Hemicampos**: desarrollado de forma propia, tomando inspiración y propiedades de Pylinac.
- **Coincidencia de campo radiante con campo luminoso**: desarrollado de forma propia, utilizando funcionalidades de Pylinac y otras bibliotecas.

Para validar los scripts, se introdujeron errores intencionales y se ajustaron algunas pruebas con el fin de establecer **límites de acción y tolerancias**.

Los resultados obtenidos tras el procesamiento automatizado fueron presentados al staff de Física de Radioterapia de INTECNUS, con el objetivo de ser incorporados al sistema de gestión de calidad y fomentar la retroalimentación para futuras mejoras.

---

# Integrantes

## **Autores:**
**Anna Nuñez**
Universidad Nacional de Córdoba, Córdoba, Argentina.


**Roy Maximiliano Lápera**
Fundación INTECNUS de San Carlos de Bariloche , Río Negro, Argentina.

### **Director:** **Sebastián Bianchini**
Fundación INTECNUS de San Carlos de Bariloche , Río Negro, Argentina.
Centro Atómico (CNEA), San Carlos de Bariloche, Argentina. 
