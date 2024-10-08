# Introducción a los Grandes Modelos de Lenguaje

<center><i>Benjamin Eduardo Alvarez y F. Santiago Echeverría Perpetua

Universidad Nacional de Córdoba, Facultad de Matemática, Astronomía, Física y Computación</i></center>

## Abstract

<center>
<i>
Este proyecto presenta un itinerario educativo compuesto por tres colabs diseñados para guiar a los participantes en el uso de Grandes Modelos de Lenguaje (LLMs). Abarcamos desde la instalación y configuración de herramientas esenciales hasta el pre-entrenamiento y ajuste fino de modelos. Mediante prácticas guiadas y la participación en comunidades activas del campo, buscamos reducir las barreras técnicas que enfrentan los principiantes, facilitando el acceso a estas poderosas tecnologías. creemos que, con una estructura clara y el apoyo de una comunidad, los usuarios podrán no solo entender, sino también aplicar y personalizar los LLMs para resolver problemas específicos. Los participantes aprenderán a instalar y usar herramientas como Hugging Face y Google Colab, preparar datasets, entrenar modelos y aplicar técnicas de fine-tuning, con el objetivo de empoderar a más personas para aprovechar el potencial de los LLMs en sus proyectos.
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

- **Familiarizarse con los LLMs**: Proporcionar una comprensión básica sobre qué son los LLMs y cómo utilizarlos. Entender la configuración del entorno de trabajo para LLMs. Conectarse con las comunidades que desarrollan y colaboran en proyectos de LLMs.

- **Entrenamiento y fine tuning**: Enseñar cómo pre-entrenar y ajustar modelos para tareas específicas. Comprender cómo entrenar un LLM con datos sin procesar y preparar datasets para el entrenamiento.Aplicar técnicas de fine tuning para adaptar un LLM a problemas concretos y poder evaluar el rendimiento de los modelos ajustados.

- **Desarrollar comunidad**: Fomentar el trabajo colaborativo y la resolución de problemas en torno a los LLMs.

---

## Planificación
### Semana 1: Diseño General del Proyecto y Tareas
#### Objetivos:
- Definir con claridad el **alcance** del proyecto.
- Desarrollar el **índice detallado** de cada colab.
- Definir los **criterios de éxito** para cada colab y las expectativas de aprendizaje.
- Revisión de **recursos externos** (cursos, colabs similares) para inspiración.

### Semana 2: Desarrollo del Primer Colab (Instalación y Comunidad)

#### **Objetivos**:
- Desarrollar el **contenido del primer colab** centrado en la instalación y la conexión con la comunidad de LLMs.
- Definir ejercicios prácticos para los usuarios sobre la instalación de bibliotecas y modelos.
- Creación de ejercicios sencillos de exploración con **modelos preentrenados**.

#### **Descripción del Colab**:
- Enseñar cómo instalar y usar los entornos necesarios (Colab, Transformers).
- Introducción a la comunidad de LLMs (Hugging Face, repositorios, documentación).

#### **Temas**:
  - Instalación de bibliotecas clave (Transformers, Tokenizers).
  - Uso básico de modelos preentrenados.
  - Introducción a recursos comunitarios y cómo participar.

### Semana 3: Desarrollo del Segundo Colab (Pre-Training de un Modelo)
#### Objetivos:
- Crear el contenido detallado sobre **pre-entrenamiento** de modelos, desde la obtención de datos hasta la ejecución del pre-entrenamiento.
- Escribir el contenido teórico que explique el **pre-entrenamiento**.
- Preparar ejemplos de cómo obtener y procesar datasets.
- Pruebas de ejecución del colab para asegurar que funcione correctamente en distintos entornos.

#### **Descripción del Colab**: 
  Exploraremos el proceso de preentrenamiento de un modelo desde cero utilizando datasets y entenderemos la diferencia entre pre-training y fine tuning
  
#### **Temas**:
  - Obtención y procesamiento de datos.
  - Arquitectura de LLMs.
  - Ejecución del pre-entrenamiento en GPU.



### Semana 4: Desarrollo del Tercer Colab (Fine-Tuning de Modelos)
#### **Objetivos**:
- Desarrollar el colab de **fine-tuning** para adaptar un modelo preentrenado a tareas específicas.
- Escribir el contenido teórico sobre **fine-tuning**.
- Desarrollar ejercicios prácticos para tareas como clasificación de texto o análisis de sentimientos.
- Definir y documentar **métodos de evaluación** de modelos para medir el rendimiento post fine-tuning.

#### **Descripción del colab**: 
  Ajustaremos un modelo preentrenado para tareas específicas (de ahí el nombre "fine-tuning"), como clasificación de texto, generación de texto o análisis de sentimientos entre muchas otras posibilidades.

#### **Temas**:
  - Preparación de datasets específicos.
  - Métodos de fine-tuning.
  - Evaluación y optimización de resultados.

## Semana 5: Integración, Revisión Final y Documentación
**Objetivos**:
- Revisar los tres colabs, integrar los ajustes finales y preparar la **documentación** del proyecto completo.
- Revisión detallada de cada colab, asegurando coherencia y claridad en las instrucciones.
- Agregar **explicaciones adicionales** donde sea necesario, mejorar la fluidez del lenguaje.

---

## Requisitos

- Conocimientos básicos de Python.
- Familiaridad con el uso de Google Colab.
- Entusiasmo por aprender y colaborar en proyectos de IA.

--- 

## Recursos

Entornos y plataformas usados
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Documentación de Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)

Otros trabajos a chequear
- [1.0 Using pretrained LLM for text classification](https://colab.research.google.com/drive/1h3hQ8anuKjoWJXz12p-OgwduBpYQB7rI?usp=sharing)
- [Taller: Modelos de lenguaje a tu medida](https://github.com/nanom/llm_adaptation_workshop)
- [Curso de etica en IA](https://www.metadocencia.org/en/curso/etica_en_ia/)
<!-- - [Dataset](#) A buscar -->

---

¡Acompáñanos en esta aventura de aprendizaje para dominar el uso de los Grandes Modelos de Lenguaje!