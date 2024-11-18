# Introducción a los Grandes Modelos de Lenguaje

<center><i>Fabio Santiago Echeverría Perpetua

Universidad Nacional de Córdoba, Facultad de Matemática, Astronomía, Física y Computación</i></center>

## Abstract

<center>
<i>
Este proyecto presenta un itinerario educativo compuesto por tres colabs diseñados para guiar a los participantes en el uso de Grandes Modelos de Lenguaje (LLMs por su sigla en inglés). Abarcamos desde la instalación y configuración de herramientas esenciales hasta el pre-entrenamiento y ajuste fino de modelos. Mediante prácticas guiadas y la participación en comunidades activas del campo, buscamos reducir las barreras técnicas que enfrentan los principiantes, facilitando el acceso a estas poderosas tecnologías. creemos que, con una estructura clara y el apoyo de una comunidad, los usuarios podrán no solo entender, sino también aplicar y personalizar los LLMs para resolver problemas específicos. Los participantes aprenderán a instalar y usar herramientas como Hugging Face y Google Colab, preparar datasets, entrenar modelos y aplicar técnicas de fine-tuning, con el objetivo de empoderar a más personas para aprovechar el potencial de los LLMs en sus proyectos.
</i>
</center>

## Descripción

En este proyecto, enseñaremos a trabajar con Modelos de Lenguaje a través de tres colabs secuenciales. Durante este itinerario, aprenderás desde la instalación y configuración básica de las herramientas hasta técnicas avanzadas como el pre-entrenamiento y ajuste fino de modelos.

---

## Hipótesis de Trabajo

Nuestra hipótesis central es que, a través de un enfoque guiado y estructurado, es posible simplificar el proceso de adopción y personalización de Grandes Modelos de Lenguaje (LLMs) para usuarios con conocimientos básicos de programación. 

Específicamente, creemos que:

1. **La instalación y configuración accesible** es clave para democratizar el uso de LLMs. Proporcionando herramientas y recursos sencillos de implementar, podemos reducir las barreras técnicas que muchos enfrentan al comenzar a explorar el mundo de los modelos de lenguaje.

2. **El pre-entrenamiento y ajuste de modelos**, cuando se enseña en pasos claros y prácticos, puede ser comprendido y aplicado incluso por aquellos sin experiencia profunda en el uso de estos modelos. El acceso a datos, ejemplos y plataformas como Google Colab o Hugging Face permitirá que los participantes reproduzcan y adapten estos procesos para casos de uso específicos.

3. **La comunidad y el soporte continuo** juegan un rol fundamental para el aprendizaje eficaz. La participación en comunidades activas, el intercambio de conocimientos y la colaboración acelerarán el proceso de aprendizaje y ayudarán a superar los obstáculos técnicos.

En resumen, creemos que al facilitar el acceso, la práctica y el soporte comunitario, los participantes podrán desarrollar habilidades fundamentales para trabajar con LLMs y aplicar estas tecnologías a proyectos propios, personalizando los modelos a sus necesidades con éxito.

---

## Objetivos

En base a cada una de nuestras hipotesis, hemos planteado los objetivos correspondientes:

1. **Familiarizarse con los LLMs**: Proporcionar una comprensión básica sobre qué son los LLMs y cómo utilizarlos. Entender la configuración del entorno de trabajo para LLMs. Conectarse con las comunidades que desarrollan y colaboran en proyectos de LLMs.

2. **Entrenamiento y fine tuning**: Enseñar cómo pre-entrenar y ajustar modelos para tareas específicas. Comprender cómo entrenar un LLM y preparar datasets para el entrenamiento. Aplicar técnicas de fine-tuning para adaptar un LLM a problemas concretos.

3. **Desarrollar comunidad**: Fomentar el trabajo colaborativo y la resolución de problemas en torno a los LLMs.

---

## Estado final

### Colab 1: [Introducción](https://colab.research.google.com/drive/1g21Ib4liopkIyQcU2qdgZpMFizXcW5aw?usp=sharing)

En la introducción se presenta todo el planteamiento necesario para familiarizarse con los LLMs; cumpliendo el primer objetivo planteado. Aunque explicamos conceptos más técnicos cómo lo son los transformers con los decoders y encoders, tratamos de no sobrecargar al usuario de información y sólo ayudarles a razonar cómo funcionan concptualmente sin abordar en lo que son las redes neuronales o temas más complejos.

A su vez, en este colab enseñamos cómo crearse cuentas en las plataformas de HuggingFace y Weights&Biases, y generar los tokens de acceso que le permitirán vincular su cuenta a los siguientes colabs. Esto con el fin de arrimar al lector a iniciarse en la comunidad, aunque el objetivo correpondiente no se completa en un colab concreto; sino que a lo largo de los tres colabs el beneficio de la comunidad se hace presente al bajar y subir modelos y datasets de HuggingFace.

### Colab 2: [Pre-training](https://colab.research.google.com/drive/14WAuWa-fBBM2tT93QtuwSAJZ2PgdU-8o?usp=sharing)

Aunque en un principio teníamos empezado realizar un entrenamiento desde cero, notamos que la cantidad de tiempo requerida era demasiado alta para el lector del curso. A su vez, esto requería un mayor entendimiento de lo que estamos haciendo de parte del lector, aumentando la dificultad del curso y limitando a los posibles interesados.

Debido a esto, se decidio optar por enseñar al usuario cómo interactuar con los modelos ya pre-entrenados. Ya que cómo lo planteamos en nuestra primer hipotesis, queremos que el proceso de instalación y configuración sea accesible. Por lo que mientras el colab 1 ayuda al usuario a entender lo que son los LLMs, en el colab 2 se le permite al usuario experimentar con ellos y usarlos (Particularmente con GPT-2 y BERT)

A su vez, se sigue mostrando al lector la importancia de la comunidad de una manera implicita. Pues los modelos y datasers utilizados fueron traídos desde la comunidad (HuggingFace).

Eso sí, aunque el desarrollo de la comunidad y mostrar su utilidad tiene un eje central en este proyecto. También se le proporciona al usuario el conocimiento para descargar y subir modelos de manera local, teniendo el LLM cómo un archivo en el sistema. Esto es porque aunque queremos que el lector se acerque a la comunidad, no buscamos que dependa de esta; sino que tenga presente que no es obligatorio y siempre puede trabajar de manera local sobre sus modelos.

### Colab 3: [Fine-tuning](https://colab.research.google.com/drive/1mZKYgpJ9tM-1_8FTLKwkFjpuv9hNGlnS?usp=sharing)

El tercer colab fue el más complicado de acercar al lector. Cómo este curso busca ser accesible, tuvimos que buscar un fino equilibrio entre cuanta información meter y cómo simplificarla para no saturar al lector y que deje el curso. Es por eso que optamos por dos estrategias para que la información sea lo más digerible posible:

1. Memes: ¡Sí, memes! Sabemos que la curva de aprendizaje puede ser intensa, así que decidimos aligerarla con humor. Aunque no quisimos saturar el colab de memes, sabemos que una forma de retener la atención del lector es darle una pequeña dosis de humor por aquí y por alla que lo mantengan interesados en el contenido.Además, relacionando el humor con los temas especificos del colab, no solo arrancan una sonrisa, sino que refuerzan los conceptos de forma memorable. La propuesta fue tal, que los memes se incluyeron en el primer y segundo colab también. Al final, si algo te hace reír, es mucho más difícil olvidarlo.
2. Mantener la información técina al mínimo: Por ejemplo sin abordar mucho en los hiperparametros de entrenamiento, buscamos que el lector pueda realizar el fine-tuning entendiendo 2 o 3 parametros claves y que no se sature, dejando el curso por la cantidad de opciones. A su vez, limitamos la información de este colab solo a lo necesario, es por eso que la división de un dataset en datos de entrenamiento y evaluación se realizó previamente. Sin embargo, tampoco podemos no explicar nada al lector, por lo que damos una breve explicación del resto de hiperparametros por si el usuario está interesado en aprender su cuenta, y enseñarmos de una manera visual a reconocer si el dataset es optimo para el fine-tuning, o cómo aplicarle un pequeño filtro rápido.

Todo esto con el sólo proposito de hacer tan fácil de entender cómo sea posible el proceso de fine-tuning.

### Sobre los objetivos y las hipotesis planteados...

El colab 1 cumple con nuesto primer objetivo (**Familiarizarse con los LLMs**) a un nivel conceptual, mientras que el colab 2 lo hace a un nivel más practico y permitiendo que el usuario lo replique con su propio código. El colab 3 (y el colab 2 en menor medida al hacer la división del dataset) cumpliría con el segundo objetivo (**Entrenamiento y fine tuning**). Y el último objetivo (**Desarrollar comunidad**) sería completado a lo largo de los 3 colabs de diferentes maneras.

En cuanto a las hipótesis planteadas, estas sirvieron como brújula para el diseño y la estructura del proyecto. La idea de que la instalación y configuración accesible es clave para democratizar el uso de LLMs se integró directamente en el colab 1, donde priorizamos guías paso a paso para configurar herramientas como Hugging Face y Weights&Biases, asegurándonos de que incluso usuarios con conocimientos básicos pudieran seguir el proceso sin frustraciones técnicas. Esto también motivó la inclusión de ejemplos prácticos descargables y una aproximación más visual que textual.

La hipótesis de que el pre-entrenamiento y ajuste de modelos podría ser comprendido con pasos claros y prácticos fue el eje central del segundo y tercer colab. Reducimos la cantidad de conceptos avanzados para mantener la atención del lector, limitando las explicaciones técnicas a lo estrictamente necesario, como los parámetros esenciales del fine-tuning. A la vez, optamos por una narrativa más amigable, apoyada por ejemplos específicos y memes, para reforzar la retención y hacer más llevadero el aprendizaje.

Finalmente, la hipótesis sobre la importancia de la comunidad quedó reflejada en cómo estructuramos la interacción con plataformas como Hugging Face, no solo para descargar y usar modelos, sino también para mostrar el valor de la colaboración y el intercambio de conocimientos. Aunque no podemos aún medir directamente el impacto en los usuarios, la integración de estas ideas en cada colab buscó maximizar el potencial de aprendizaje y aplicación de los participantes.

### Feedback de otros grupos

A partir del feedback recibido de otros grupos, hemos implementado varias mejoras clave en nuestro proyecto. Una de las principales fue el ajuste de un modelo paso a paso con fines didácticos, disponible en el colab 3, diseñado para facilitar el aprendizaje práctico del proceso de fine-tuning. Además, incluimos tres cuestionarios —uno al final de cada colab— para que los usuarios puedan autoevaluar su comprensión y progreso en los temas tratados.

Sin embargo, algunas sugerencias, como definir claramente el propósito del modelo ajustado y abordar aplicaciones más realistas de los modelos, no fueron implementadas en su totalidad debido a desafíos logísticos. Originalmente, planeamos utilizar el dataset [Twitter Genderbias](https://huggingface.co/datasets/argilla/twitter-genderbias) para ajustar GPT-2 y abordar la problemática de género en respuestas automáticas. Esto habría cumplido ambos objetivos: un enfoque práctico y una aplicación concreta.

Lamentablemente, la salida inesperada de un integrante y la falta de tiempo nos llevaron a priorizar un enfoque más general. Optamos por mostrar el proceso de ajuste como un ejemplo replicable, dejando abierta la posibilidad de que los usuarios apliquen los conceptos aprendidos a sus propios casos de uso. Si bien esta decisión limitó la profundidad en la aplicación específica, se alineó con el propósito central del proyecto: facilitar el aprendizaje práctico y permitir que los usuarios comprendan y adapten los modelos según sus necesidades.

---

## Requisitos

- Conocimientos básicos de Python.
- Familiaridad con el uso de Google Colab.
- Entusiasmo por aprender y colaborar en proyectos de IA.

---

## Recursos

Entornos y plataformas usados
- [Hugging Face](https://huggingface.co/)
- [Documentación de Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)
- [Weights & Biases](https://wandb.ai/)

Trabajos previos y recomendables: Todos fueron utilizados cómo referencia para ayudar a armar este proyecto.
- [1.0 Using pretrained LLM for text classification](https://colab.research.google.com/drive/1h3hQ8anuKjoWJXz12p-OgwduBpYQB7rI?usp=sharing) (está en inglés)
- [Taller: Modelos de lenguaje a tu medida](https://github.com/nanom/llm_adaptation_workshop)
- [Curso de etica en IA](https://www.metadocencia.org/en/curso/etica_en_ia/) (inglés)
- Hands-On Large Language Models, J. Alammar & M. Grootendor. (libro)

Modelos
- [BERT](https://huggingface.co/google-bert/bert-base-uncased): Modelo para explicar el decoder.
- [GPT-2](https://huggingface.co/openai-community/gpt2): Modelo base para luego ser reemplazado por una versión en español, en un afán de animar al usuario a buscar modelos según las necesidades.
- [GPT-2 Español](https://huggingface.co/DeepESP/gpt2-spanish): Modelo principalmente usado.

Datasets
- [Twitter Genderbias](https://huggingface.co/datasets/argilla/twitter-genderbias): Usado en el colab 2 para demostrar cómo manejar datasets.
- [Oscar small](https://huggingface.co/datasets/nthngdy/oscar-small): Usado en el colab 3 para el fine-tuning.

---

¡Acompáñanos en esta aventura de aprendizaje para dominar el uso de los Grandes Modelos de Lenguaje!
