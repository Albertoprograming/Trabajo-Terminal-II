# Análisis del habla imaginada en el espacio de características por medio de Transformers.

Este repositorio contiene el código y materiales acerca del **Trabajo Terminal** sobre clasificación de **habla imaginada** a partir de señales EEG.  
El pipeline completo incluye:

- Carga y exploración de un dataset de EEG de habla imaginada.
- Descomposición de las señales mediante **EMD (Empirical Mode Decomposition)** usando `PyEMD`.
- Extracción de características por canal e IMF.
- Dos enfoques basados en **Transformers** para clasificación.
- Comparación con **métodos tradicionales** de machine learning (MLP, SVM, KNN).

> ⚠️ El **dataset de EEG no se distribuye** en este repositorio por cuestiones de privacidad y tamaño. Solo se incluye su documentación.

---

## Tecnologías y dependencias

El proyecto está desarrollado en **Python 3** e incluye, entre otras, las siguientes librerías:

- `numpy`, `pandas`
- `scipy` (`scipy.io.loadmat` para leer `.mat`)
- `matplotlib`
- `PyEMD` (descomposición EMD)
- `torch` (PyTorch)
- `scikit-learn` (MLP, SVM, KNN, métricas)

Las dependencias están listadas en:

```text
requirements.txt
