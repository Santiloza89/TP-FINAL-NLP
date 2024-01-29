# TP-FINAL-NLP


# Trabajo Práctico Final Procesamiento del Lenguaje Natural

En este repo encontraremos el trabajo práctico final de la asignatura Procesamiento del Lenguaje Natural, de la Tecnicatura Univesitaria en Inteligencia Artificial.

El mismo consta de 2 ejercicios los cuales son:

#### **Ejercicio 1 - RAG**

Crear un chatbot experto en un tema a elección, usando la técnica RAG (Retrieval Augmented Generation). Como fuentes de conocimiento se utilizarán al menos las siguientes fuentes:

*   Documentos de texto
*   Datos numéricos en formato tabular (por ej., Dataframes, CSV, sqlite, etc.)
*   Base de datos de grafos (Online o local)

El sistema debe poder llevar a cabo una conversación en lenguaje español. El usuario podrá hacer preguntas, que el chatbot intentará responder a partir de datos de algunas de sus fuentes. El asistente debe poder clasificar las preguntas, para saber qué fuentes de datos utilizar como contexto para generar una respuesta.



**Requerimientos generales:**


*   Realizar todo el proyecto en un entorno Google Colab

*   El conjunto de datos debe tener al menos 100 páginas de texto y un mínimo de 3 documentos.

*   Realizar split de textos usando Langchain (RecursiveTextSearch, u otros métodos disponibles). Limpiar el texto según sea conveniente.

*   Realizar los embeddings que permitan vectorizar el texto y almacenarlo en una base de datos ChromaDB

*   Los modelos de embeddings y LLM para generación de texto son a elección

*   Para el desarrollo del “Clasificador” es posible utilizar diversas técnicas aprendidas en la materia, por ejemplo en Unidad 3 y Unidad 6


#### **Ejercicio 2 - Agentes**

Realice una investigación respecto al estado del arte de las aplicaciones actuales de agentes inteligentes usando modelos LLM libres.

Plantee una problemática a solucionar con un sistema multiagente. Defina cada uno de los agentes involucrados en la tarea. Es importante destacar con ejemplos de conversación, la interacción entre los agentes.

Realice un informe con los resultados de la investigación y con el esquema del sistema multiagente, no olvide incluir fuentes de información.

Opcional: Resolución con código de dicho escenario.


El repositorio contiene 3 archivos:
 - `COPA DE LA LIGA 2023.pdf` : Información que ulilizaremos para realizar una base de datos de grafos.
 - `Resultados Mundial.xlsx` : Información que ulilizaremos como fuente de datos tabulares.
 - `TP FINAL NLP.ipynb` : Colab con el codigo python y explicacion del proyecto.
