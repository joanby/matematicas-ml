# Fundamentos Matemáticos del Machine Learning

Este repositorio contiene el código que acompaña al plan de estudios *Fundamentos Matemáticos deMachine Learning Foundations* de Juan Gabriel Gomila, que proporciona una visión completa de todas las materias (matemáticas, estadística e informática) que subyacen a los enfoques contemporáneos del aprendizaje automático, incluido el aprendizaje profundo y otras técnicas de inteligencia artificial.

Hay ocho temas completos en el plan de estudios, organizadas en cuatro áreas temáticas. Consulta la sección «Machine Learning House» a continuación para obtener información detallada sobre por qué estas son las áreas temáticas fundamentales esenciales: 

* **Álgebra Lineal**
   * 1: [Introducción al Álgebra Lineal](https://github.com/joanby/matematicas-ml/blob/master/notebooks/1-intro-to-linear-algebra.ipynb)
   * 2: [Álgebra Lineal II: Operaciones Matriciales](https://github.com/joanby/matematicas-ml/blob/master/notebooks/2-linear-algebra-ii.ipynb)
* **Cálculo**
   * 3: [Cálculo I: Límites & Derivadas](https://github.com/joanby/matematicas-ml/blob/master/notebooks/3-calculus-i.ipynb)
   * 4: [Cálculo II: Derivadas Parciales e Integrales](https://github.com/joanby/matematicas-ml/blob/master/notebooks/4-calculus-ii.ipynb)
* **Probabilidad y Estadística**
   * 5: [Probabilidad & Teoría de la Información](https://github.com/joanby/matematicas-ml/blob/master/notebooks/5-probability.ipynb)
   * 6: [Introducción a la Estadística](https://github.com/joanby/matematicas-ml/blob/master/notebooks/6-statistics.ipynb)
* **Ciencias de la Computación**
   * 7: [Algoritmos y Estructuras de Datos](https://github.com/joanby/matematicas-ml/blob/master/notebooks/7-algos-and-data-structures.ipynb)
   * 8: [Optimización](https://github.com/joanby/matematicas-ml/blob/master/notebooks/8-optimization.ipynb)
   
Los temas posteriores se basan en los anteriores, por lo que se recomienda avanzar por los ocho temas en el orden indicado. No obstante, puede elegir los temas que más le interesen o con los que esté más familiarizado. En particular, cada una de las cuatro áreas temáticas es bastante independiente, por lo que puede abordarse por separado. 

### Donde y Cuando and When

Los ocho temas de *Fundamentos de ML* fueron ofrecidos inicialmente por [Jon Krohn](jonkrohn.com) como formaciones en línea en directo en la [plataforma de aprendizaje de O'Reilly](https://learning.oreilly.com/home/) de mayo a septiembre de 2020 (y se ofrecieron una segunda vez de julio a diciembre de 2021; consulta [aquí](https://www.jonkrohn.com/talks) para ver las fechas de las clases individuales). 

Para adaptarse a su modo preferido de aprendizaje, el contenido está ahora disponible a través de varios canales: 

* **YouTube**
    * Linear Algebra [complete playlist here](https://www.youtube.com/playlist?list=PLRDl2inPrWQW1QSWhBU0ki-jq_uElkh2a) and [detailed blog post here](https://www.jonkrohn.com/posts/2021/5/9/linear-algebra-for-machine-learning-complete-math-course-on-youtube)
    * Calculus [complete playlist here](https://www.youtube.com/playlist?list=PLRDl2inPrWQVu2OvnTvtkRpJ-wz-URMJx)
    * [Probability playlist](https://www.youtube.com/playlist?list=PLRDl2inPrWQWwJ1mh4tCUxlLfZ76C1zge) is in active development (sign up for my email newsletter at [jonkrohn.com](https://www.jonkrohn.com/) to be notified of new video releases)
    * In time, all of the subjects of my ML Foundations curriculum will be freely available on YouTube.
* **O'Reilly** (many employers and educational institutions provide free access to this platform; if you don't have access, you can get a 30-day free trial [via my special SDSPOD23 code](https://learning.oreilly.com/get-learning/?code=SDSPOD23))
    * [Linear Algebra videos](https://learning.oreilly.com/videos/linear-algebra-for/9780137398119/) published in Dec 2020 ([free hour-long lesson](https://www.youtube.com/watch?v=uG_wjmuigGg))
    * [Calculus videos](https://learning.oreilly.com/videos/calculus-for-machine/9780137398171/) published in Jan 2021 ([free hour-long lesson](https://youtu.be/ZDAX17OGMAM))
    * [Probability and Stats videos](https://learning.oreilly.com/videos/probability-and-statistics/9780137566273/) published in May 2021 ([free hour-long lesson](https://youtu.be/uJcGj-k50iE))
    * [Computer Science videos](https://learning.oreilly.com/videos/data-structures-algorithms/9780137644889/) published in Jun 2021 ([free hour-long lesson](https://youtu.be/yfKkMdndY-E))
    * (For convenience, this publisher compiled all 28 hours of the above four video series into a single playlist [here](https://learning.oreilly.com/videos/-/9780137903245/).)
* **Open Data Science Conference**: The entire series was taught live online from Dec 2020 to Jun 2021. On-demand recordings of all these trainings are now available in the [Ai+ Platform](https://aiplus.odsc.com/pages/mlbootcamp).
* **Book**: A book deal with Pearson is in place; eventually I'll have bandwidth to work on the manuscript and pre-release chapter drafts will be available via oreilly.com.

*(Tenga en cuenta que, si bien YouTube contiene el 100% del contenido enseñado, las opciones de pago -por ejemplo, O'Reilly y ODSC- contienen soluciones completas para los ejercicios que no están disponibles en YouTube. Algunas de las opciones de pago también incluyen funciones exclusivas y específicas de la plataforma, como pruebas interactivas, «hojas de trucos» y la concesión de un certificado por haber completado con éxito el curso)*.

### Push Notifications

Para mantenerse informado sobre futuras sesiones de formación en directo, nuevos vídeos y capítulos de libros, suscríbase al [boletín electrónico a través de su página web] de Jon Krohn (https://www.jonkrohn.com/).

### Notebooks

Todo el código se proporciona en cuadernos Jupyter [en este directorio](https://github.com/joanby/DLTFpT/blob/master/notebooks/). Estos cuadernos están pensados para su uso en el entorno en la nube (gratuito) [Colab](https://colab.research.google.com) y ese es el único entorno actualmente soportado de forma activa. 

Dicho esto, si usted está familiarizado con la ejecución de cuadernos Jupyter localmente, es bienvenido a hacerlo (tenga en cuenta que las versiones de la biblioteca en este repositorio [Dockerfile](https://github.com/jonkrohn/ML-foundations/blob/master/Dockerfile) no son necesariamente actuales, pero pueden proporcionar un punto de partida razonable para ejecutar Jupyter dentro de un contenedor Docker).

### The Machine Learning House

<p align="center">
  <img src="https://github.com/joanby/matematicas-ml/blob/master/img/ML-house.png" width="500" align="center">
</p>

Para ser un científico de datos o un ingeniero de ML sobresaliente, no basta con saber utilizar algoritmos de ML a través de las interfaces abstractas que ofrecen las bibliotecas más populares (por ejemplo, scikit-learn, Keras). Para entrenar modelos innovadores o desplegarlos para que funcionen de forma eficiente en producción, puede ser útil o esencial una apreciación en profundidad de la teoría del aprendizaje automático (representada como el suelo central de color púrpura de la «Casa del Aprendizaje Automático»). Y, para cultivar esa apreciación profunda del ML, uno debe poseer una comprensión práctica de los temas fundamentales.

Cuando los cimientos de la «Casa del Aprendizaje Automático» son firmes, también resulta mucho más fácil dar el salto de los principios generales del aprendizaje automático (piso morado) a los dominios especializados del aprendizaje automático (piso superior, mostrado en gris), como el aprendizaje profundo, el procesamiento del lenguaje natural, la visión artificial y el aprendizaje por refuerzo. Esto se debe a que, cuanto más especializada es la aplicación, más probable es que los detalles de su implementación sólo estén disponibles en artículos académicos o en libros de texto de posgrado, en los que normalmente se presupone un conocimiento de las materias básicas.

El contenido de esta serie puede ser especialmente relevante para usted si: 

* **Utilizas librerías de software de alto nivel** para entrenar o desplegar algoritmos de aprendizaje automático, y ahora te gustaría comprender los fundamentos subyacentes a las abstracciones, lo que te permitiría ampliar tus capacidades
* Eres un **científico de datos** que desea reforzar su comprensión de los temas en el núcleo de su disciplina profesional
* Eres un **desarrollador de software** al que le gustaría desarrollar una base firme para el despliegue de algoritmos de aprendizaje automático en sistemas de producción.
* Eres un **analista de datos** o un **entusiasta de la Inteligencia Artificial** al que le gustaría convertirse en un científico de datos o un ingeniero de datos/ML, por lo que estás deseando comprender en profundidad el campo en el que estás entrando desde el principio (¡muy sabio por tu parte!). 
* Simplemente quieres entender lo esencial del álgebra lineal, cálculo, probabilidad, estadística, algoritmos y/o estructuras de datos.

Las asignaturas básicas no han cambiado mucho en las últimas décadas y es probable que sigan así en las próximas, pero son fundamentales en todos los enfoques del aprendizaje automático y la ciencia de datos. Por lo tanto, los fundamentos proporcionan una base sólida para toda la carrera. 


### Enfoque pedagógico

El objetivo de esta serie es proporcionarle una comprensión práctica y funcional del contenido tratado. Se dará contexto a cada tema, destacando su relevancia para el aprendizaje automático. 

Al igual que con otros materiales creados por Jon Krohn (como el libro *[Deep Learning Illustrated](https://www.deeplearningillustrated.com/)* y su serie de vídeos de 18 horas *[Deep Learning with TensorFlow, Keras, and PyTorch](https://github.com/joanby/DLTFpT/))*, el contenido de la serie cobra vida gracias a la combinación de:

* Ilustraciones vívidas a todo color 
* Ejercicios de comprensión con lápiz y papel y soluciones prácticas
* Cientos de ejemplos sencillos de código Python en cuadernos Jupyter prácticos (con especial atención a las bibliotecas PyTorch y TensorFlow).
* Aplicaciones prácticas de ML
* Recursos para profundizar aún más en los temas que despiertan tu curiosidad

### Prerequisitos

**Programación**: Todas las demostraciones de código se harán en Python, por lo que será útil tener experiencia con este u otro lenguaje de programación orientado a objetos para seguir los ejemplos de código. Un buen recurso (¡y gratuito!) para iniciarse en Python es [Automate the Boring Stuff](https://automatetheboringstuff.com/) de Al Sweigart.

**Matemáticas**: Estar familiarizado con las matemáticas de secundaria facilitará el seguimiento de la clase. Si te sientes cómodo con la información cuantitativa, como la comprensión de gráficos y la reorganización de ecuaciones sencillas, entonces estarás bien preparado para seguir todas las matemáticas. Si descubres que tienes algunas lagunas matemáticas mientras trabajas en este plan de estudios *Fundamentos de ML*, te recomiendo la completa ruta de aprendizaje de [Frogames Formación](https://cursos.frogamesformacion.com/bundles/aprende-matematicas-desde-cero) para llenar esas lagunas.


### Oboe

Por último, he aquí una ilustración de Oboe, la mascota de *Machine Learning Foundations*, creada por el maravilloso artista [Aglaé Bassens](https://www.aglaebassens.com): 

<p align="center">
  <img src="https://github.com/joanby/matematicas-ml/blob/master/img/Oboe.jpg" width="400" align="center">
</p>
