PROYECTO 3 - BIGDATA

Curso ST0263 Tópicos Especiales en Telematica

Universidad EAFIT

2018-2

Estudiantes:

Maria Camila Calle Agudeo
Juan Esteban Henao Muñoz

a. Contexto

La minería o analítica de texto, son un conjunto de modelos, técnicas, algoritmos y tecnologías que permiten procesar texto de naturaleza NO ESTRUCTURADA. La minería de texto (text mining) permite transformar el texto en una forma estructurada, de tal forma que facilite una serie de aplicaciones como Búsqueda en texto, relevancia de documentos, entendimiento natural del lenguaje (NLP), traducción automática entre idiomas, análisis de sentimientos, detección de tópicos entre muchas otras aplicaciones. Quizás el procesamiento más sencillo de todos, sea el wordcount, el cual consiste en determinar la frecuencia de la palabra por documento o por todo el dataset.

b. Problema a resolver

Se tiene un conjunto de noticias en texto libre, sobre el cual se desea calcular: Índice Invertido, donde por cada palabra que se ingrese por teclado, se liste en orden descendente por frecuencia de palabra en el contenido de la noticia, las noticias más relevantes. Listar máx 10 <frec,doc_id,title>. frec = frecuencia de la palabra en la noticia id = id de la noticia title = título de la noticia.


c. Almacenamiento de los datos + tecnologías a utilizar

En este caso se utlizara DataFrames para la representación de los datos haciendo uso de Spark

d. Análisis de datos + tecnologías a utilizar

En analisis de datos se hará a partir de Apache Spark, este un procesador de codigo abierto basado en la velocidad, facilidad y en el analisis para grandes cantidades de datos, el principal motivo de usar esta tecnologia se debe a que spark permite y esta diseñado pra realizar cálculos iterativos y para visulizar de forma interactiva.
