# Predicción de abandono de clientes bancarios

## Descripción

Modelo para **Beta Bank** que predice qué clientes dejarán el banco, para enfocar las campañas de retención. Solo el 20 % de los clientes del histórico se había ido, así que el reto principal es el desequilibrio de clases.

## Resultados principales

- Codifiqué variables categóricas e imputé valores ausentes con la mediana del entrenamiento.
- Comparé sobremuestreo y submuestreo; corregir el desequilibrio subió el F1 de 0.53 a 0.61 en validación.
- En prueba, el modelo obtuvo F1 de 0.56 y **AUC-ROC de 0.82**: ordena bien a los clientes según su riesgo de abandono.

## Herramientas

Python, pandas, NumPy, scikit-learn

## Cómo ejecutarlo

```bash
pip install -r requirements.txt
jupyter notebook 05_abandono_clientes_banco.ipynb
```

Los datos provienen del programa de formación en ciencia de datos y no se incluyen en este repositorio. El notebook se puede revisar con todas sus salidas directamente en GitHub.

## Autor

Diego Parra · [LinkedIn](https://www.linkedin.com/in/diegoparragar)
