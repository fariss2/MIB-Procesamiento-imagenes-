# MIB-Procesamiento de Imágenes FISH para Conteo y Clasificación Celular
Repositorio correspondiente a la práctica final de procesamiento de imágenes biomédicas basada en imágenes de Hibridación Fluorescente in Situ (FISH).

El trabajo aborda el conteo de sondas fluorescentes por célula y la posterior clasificación celular mediante un enfoque baseline tradicional y métodos de aprendizaje automático / deep learning.

---
## Descripción del problema

Se dispone de un conjunto de **25 imágenes FISH** con:
- Un número indeterminado de células por imagen
- Sondas fluorescentes de dos tipos:
  - Sondas de control (verde/azul)
  - Sondas del gen de interés (rojo)

El objetivo ideal es estimar el porcentaje de células de cada tipo:
- **Célula normal**: 2 sondas de control + 2 sondas del gen
- **Deleción de un brazo**: 2 sondas de control + 1 sonda del gen
- **Deleción de ambos brazos**: 2 sondas de control

Dado que el objetivo completo es muy ambicioso, el trabajo se centra en probar y comparar distintas técnicas.
