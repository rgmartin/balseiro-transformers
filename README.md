# Talleres de Inteligencia Artificial

Links de interes:

- Curso de standford: https://web.stanford.edu/class/cs224n/
- Libro de transformers con HuggingFace: https://www.oreilly.com/library/view/natural-language-processing/9781098136789/
- Pytorch y machine learning book: https://sebastianraschka.com/blog/2022/ml-pytorch-book.html

---

### Resumen

El campo de la inteligencia artificial ha visto un crecimiento sin precedentes desde la introducción de la arquitectura de los Transformers con el paper fundacional “Attention is All You Need” en 2018. El impacto de este desarrollo fue tal que ni los autores originales predijeron el alcance que esta arquitectura tendría en multiples campos de la investigación y la industria. Aunque muchas fuentes cubren la teoría detrás de esta arquitectura, es muy difícil reemplazar el desarrollo de uno o dos ejemplos prácticos del uso de esta arquitectura y de las principales librerías que la implementan. Con estas charlas, pretendo darles las herramientas iniciales con las cuales pueden adaptar las librerías de PyTorch y Hugging Face a sus usos en la investigación y la industria, demostrando el poder y la flexibilidad de estas herramientas.

### Charla 1: Deep Learning práctico con PyTorch

En esta charla, nos enfocamos en los fundamentos de una de las dos librerías de Deep Learning más utilizadas actualmente y concluimos con un pequeño ejemplo de ‘análisis de sentimientos’ que puede ser rápidamente adaptado a cualquier tarea de clasificación.

### Charla 2: Implementando Transformers con Hugging Face

Hugging Face abstrae muchos de los pasos necesarios con PyTorch para permitirnos enfocarnos en los temas de entrenamiento, evaluación y “deployment” de modelos basados en la arquitectura de transformers. Con esta charla, te irás con el entendimiento básico de cómo usar esta librería y adaptarla a tus aplicaciones particulares.

### Requerimientos

Todos están invitados, pero se le podrá sacar mayor provecho a quienes:

- Dominen el uso del lenguaje Python, y en particular librerías de cálculo numérico como numpy (aunque si conoces Matlab o Mathematica, esto te resultará familiar).
- Buen entendimiento de conceptos de Machine Learning (en especial redes neuronales, backpropagation y optimización).
- Preparación del ambiente de desarrollo: Usaremos Jupyter Notebooks en Google Colab, deberías familiarizarte con estas dos herramientas antes de asistir a las charlas.

### Tiempo estimado: dos horas por charla.

---

### Viernes 22 Noviembre, 2024: Charla informativa

#### Fechas de las charlas:

- Pytorch (viernes 29 de noviembre, 14:00)
- HuggingFace (viernes 6 de diciembre, 14:00)

#### Para refrescar python, machine learning y obtener un primer vistazo a los transformers.

- Python: Puedes usar el notebook `python_tutorial.ipynb` que aparece en este repo.
- Machine Learning: http://ciml.info/ (échale un vistazo al menos a los primeros 5 capítulos)
- Transformers: http://jalammar.github.io/illustrated-transformer: manera didáctica de comprender su compleja estructura.

#### Infra

Asegurémonos de que la infraestructura necesaria y las instalaciones requeridas corren sin problemas en las computadoras que traeremos para las charlas.

- Logearte a https://colab.research.google.com
- En `Abrir Cuaderno` elige GitHub y escribe el siguiente url: https://github.com/rgmartin/balseiro-transformers
- Selecciona el notebook que usaremos en la charla, por ahora usa `python_tutorial.ipynb`
- En `Entorno de ejecucion` haz click en Cambiar tipo de entorno de ejecución y selecciona un GPU y Python3.
- Corre las celdas del cuaderno con Ctrl+Enter para asegurarte de que todo funciona correctamente.
