# **Generación Automática de Resúmenes con ML-NLP**
En este proyecto se utiliza aprendizaje automático (ML) y procesamiento del lenguaje natural (NLP) para generar resúmenes automáticos de noticias.

## **Requisitos**
* Python 3.x
* TensorFlow
* NLTK
* SentencePiece
* Rouge
## **Instalación de librerías**
Se pueden instalar las librerías necesarias ejecutando el siguiente código:
!pip install -q tensorflow
!pip install -q nltk
!pip install -q sentencepiece
!pip install -q rouge

## **Dataset**
El dataset utilizado es el BBC News Dataset. Este dataset contiene 2225 noticias de la BBC divididas en 5 categorías: negocios, entretenimiento, política, deportes y tecnología.

## **Análisis exploratorio de datos**
Antes de empezar con el procesamiento de datos, se realiza un análisis exploratorio de los mismos. Se muestran diferentes gráficos para visualizar la longitud de las noticias, la longitud de los resúmenes, la cantidad de palabras en cada categoría, entre otros.

## **Preprocesamiento de los datos**
Se realizan varias técnicas de preprocesamiento de los datos, como la eliminación de stopwords, la lematización, la extracción de frases importantes y la tokenización.

## **Modelo de aprendizaje automático**
Se utiliza un modelo de red neuronal LSTM bidireccional para generar resúmenes de noticias. Se implementa una red neuronal que aprende a generar resúmenes de noticias en función de las noticias completas.

## **Generación de resúmenes**
Se desarrolla una función que genera resúmenes de noticias utilizando el modelo de red neuronal LSTM bidireccional. Se muestra un ejemplo de la función aplicada a una noticia.

## **Evaluación de resúmenes**
Se utiliza la métrica ROUGE (Recall-Oriented Understudy for Gisting Evaluation) para evaluar los resúmenes generados. La métrica ROUGE se utiliza para evaluar la calidad de los resúmenes en función de la semejanza entre el resumen generado y el resumen original de la noticia.

## **Conclusiones**
Este proyecto demuestra cómo se pueden utilizar técnicas de aprendizaje automático y procesamiento del lenguaje natural para generar resúmenes automáticos de noticias.

## **Referencias**
Datasets: 
* BBC News https://www.kaggle.com/datasets/hgultekin/bbcnewsarchive https://www.kaggle.com/datasets/pariza/bbc-news-summary 
* English News https://www.kaggle.com/datasets/qusaybtoush1990/english-news
Se agradece a los autores del conjunto de datos y a la plataforma Kaggle por poner a disposición estos recursos para la comunidad.

## **Autor**
Este proyecto fue realizado por Juan Carlos Peralta Olivera como proyecto final de la materia de *MACHINE LEARNING*.

## **Licencia**
Este proyecto se encuentra bajo la licencia MIT.
