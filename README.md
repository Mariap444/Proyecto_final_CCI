# Proyecto_final_CCI
# Generador de Letras de Taylor

Este proyecto tiene como objetivo desarrollar un generador de letras de canciones basado en las composiciones de la reconocida cantante Taylor Swift. 
Utilizando técnicas de procesamiento de lenguaje natural y modelos secuenciales, el sistema es capaz de generar letras originales que capturan el estilo
y la temática característica de Taylor Swift.

## Características

- Extracción y preprocesamiento de letras de Taylor Swift: Se han recolectado y procesado las letras de los álbumes "Taylor Swift",
  "Fearless", "Speak Now", "Red", "1989", "reputation" y "Lover" para ser utilizadas como datos de entrenamiento.
- Modelo secuencial: Se ha implementado un modelo secuencial utilizando la biblioteca Keras con TensorFlow backend. 
  El modelo se ha entrenado en las letras de Taylor Swift para aprender las estructuras y patrones de sus canciones.
- Generación de letras: Una vez entrenado el modelo, se puede generar texto nuevo a partir de una semilla inicial proporcionada por el usuario. 
  El generador utiliza el conocimiento adquirido del estilo de Taylor Swift para producir letras que se asemejan a su obra.
- Evaluación y refinamiento: Se ha evaluado el rendimiento del modelo y se ha identificado que se requiere un mayor procesamiento
  y ajuste de parámetros para lograr resultados más precisos. 

## Requisitos del sistema
- Python 3.7 o superior
- Bibliotecas requeridas: Keras, TensorFlow, Pandas
