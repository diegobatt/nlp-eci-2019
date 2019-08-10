# Procesamiento del lenguaje natural ECI 2019

El objetivo de este repositorio es depositar el jupyter-notebook utilizado durante la resolución
del trabajo práctico final del curso de NLP dictado en el marco de la ECI 2019 en la Facultad de Ciencias
Exactas de la UBA

El objetivo del trabajo práctico fue reproducir el resultado obtenido en [Gururangan et al., 2018](https://www.aclweb.org/anthology/N18-2017) en el área del _Natural Language Inference_ obtenido sobre el dataset [SNLI](https://nlp.stanford.edu/projects/snli/).
En esta tarea se debe responder, dadas dos frases A y B, si B es implicación de A ("entailment"), B es contradictorio con A ("contradiction") o si lo que enuncia B es neutral respecto de A ("neutral"). Se dice que A es la premisa y B es la hipótesis. En este trabajo práctico entonces se intentó predecir a qué clase pertenece cada una de las hipótesis sin observar la premisa.

## Desarrollo

Para replicar los resultados obtenidos en [Gururangan et al., 2018](https://www.aclweb.org/anthology/N18-2017) se hizo uso de un clasificador lineal generalizado implementado en la librería [FastText](https://fasttext.cc/).
La implementación del clasificador completo y el desarrollo del trabajo se encuentran en el notebook llamado `tp_nlp_fasttext.ipynb` de este repositorio.
