# Práctica NLP

Clasificación binaria de sentimientos en reviews de libros de Amazon.

## Estructura del repositorio
```
proyecto/
├── nlp_practica_ejercicio_1.ipynb     ← Descarga, balanceo de datos y EDA
├── nlp_practica_ejercicio_2.ipynb     ← Preprocesamiento con Spacy
├── nlp_practica_ejercicio_3.ipynb     ← Entrenamiento
├── nlp_practica_ejercicio_4.ipynb     ← Métricas y Conclusiones
├── README.md                          ← Estás aquí
├── data_para_ejecutar_ejercicio2.pkl  ← Generado por ejercicio 1
├── data_para_ejecutar_ejercicio3.pkl  ← Generado por ejercicio 2
└── data_para_ejecutar_ejercicio4.pkl  ← Generado por ejercicio 3
```

## Dataset

* Fuente: [Amazon Review Data](https://cseweb.ucsd.edu/~jmcauley/datasets.html#amazon_reviews)
* Tamaño: 5000 reviews balanceadas (1000 por cada rating de 1 a 5)
* Clasificación: Positivo (>= 3) / Negativo (< 3)

## Modelos entrenados

* [Logistic Regression](https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression): 82.4% accuracy
* [SVM LinearSVC](https://scikit-learn.org/stable/modules/svm.html): 81.1% accuracy
* [BERT DistilBERT](https://huggingface.co/distilbert/distilbert-base-uncased): 80.7% accuracy

**⚠️ Nota:** El entrenamiento de DistilBERT puede ser lento.
