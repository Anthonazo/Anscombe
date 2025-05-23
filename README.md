<p align="center">
  <img src="https://github.com/user-attachments/assets/fe0681e9-2f81-444a-b59a-0376e63ae6e4" alt="Logo_Universidad_Politécnica_Salesiana_del_Ecuador" width="200"/>
</p>

<h1 align="center">Universidad Politécnica Salesiana del Ecuador</h1>

<p align="center"><strong>Carrera:</strong> Ingeniería en Ciencias de la Computación</p>
<p align="center"><strong>Período:</strong> Octavo semestre, 2025</p>
<p align="center"><strong>Estudiante:</strong> Anthony Moya Ochoa</p>


<h2 align="center">Cuarteto de Anscombe</h2>

<div align="justify">

El Cuarteto de Anscombe es uno de los ejemplos más influyentes en la historia del análisis de datos. Fue diseñado por el estadístico Francis Anscombe con el propósito de resaltar cómo conjuntos de datos con estadísticas idénticas pueden mostrar patrones completamente diferentes al ser graficados.

<div align="center">
  <img src="https://github.com/user-attachments/assets/edcda574-4e5c-4877-99e6-afb4110cbe07" alt="anscombe" width="600"/>
</div

Este cuarteto está compuesto por cuatro conjuntos de datos (I, II, III y IV), cada uno de los cuales contiene once pares de valores \((x, y)\). A pesar de tener prácticamente la misma media, varianza, coeficiente de correlación \( r \) y ecuación de regresión lineal, sus distribuciones gráficas son radicalmente distintas.

El primer conjunto muestra una relación lineal clara entre las variables \(x\) y \(y\), siendo un ejemplo típico donde la regresión lineal se ajusta de manera adecuada. El segundo conjunto presenta una relación **curvilínea**, lo que evidencia que la regresión lineal no es apropiada en todos los contextos. El tercer conjunto, en cambio, contiene un **valor atípico** que distorsiona la regresión, mostrando cómo un solo punto puede tener un gran impacto en el análisis estadístico. Finalmente, el cuarto conjunto incluye un grupo de valores casi constantes en \(x\), con un **outlier extremo en \(y\)** que genera una regresión engañosa.

Este ejemplo subraya la importancia de la visualización de datos como una práctica esencial en la ciencia de datos. Limitarse únicamente a estadísticas numéricas puede llevar a interpretaciones erróneas, a modelos mal ajustados o incluso a decisiones incorrectas. En la actualidad, este principio sigue siendo válido, especialmente en contextos de análisis exploratorio de datos (EDA), donde visualizar patrones, relaciones, dispersión y valores atípicos es fundamental.

El Cuarteto de Anscombe es también un llamado de atención sobre la confianza excesiva en herramientas automáticas de análisis, recordándonos que el juicio humano y la interpretación visual siguen siendo componentes críticos en el proceso analítico. Además, ha servido como inspiración para otros conjuntos más complejos y modernos como los **Datasaurus Dozen**, que refuerzan el mismo principio con ejemplos aún más sorprendentes.

</div>


### Referencias

- Anscombe, F. J. (1973). *Graphs in statistical analysis*. The American Statistician, 27(1), 17-21. https://doi.org/10.1080/00031305.1973.10478966  
- Tufte, E. R. (2001). *The Visual Display of Quantitative Information*. Graphics Press.


<h2 align="center" style="color: #2c3e50; margin-bottom: 20px;">Estructura del Proyecto</h2>

<div style="font-family: Arial, sans-serif; color: #34495e; line-height: 1.6; max-width: 800px; margin: auto;">

<p><strong>El proyecto está organizado en dos carpetas principales que contienen los datos y el análisis realizado:</strong></p>

<h3 style="color: #2980b9;">Carpeta <code>data</code></h3>

<p>Esta carpeta contiene los conjuntos de datos utilizados para el análisis y la visualización:</p>

<ul>
  <li><code>df_anscombe.csv</code>: Dataset clásico del Cuarteto de Anscombe, utilizado para comprender y visualizar ejemplos estadísticos que muestran cómo conjuntos de datos con estadísticas idénticas pueden tener distribuciones muy diferentes.</li>
  <li><code>df_datasaurus_dozen.csv</code>: Dataset Datasaurus Dozen, empleado para realizar regresiones y visualizaciones que ejemplifican patrones complejos y sorprendentes en los datos.</li>
</ul>

<h3 style="color: #2980b9;">Carpeta <code>R</code></h3>

<p>Esta carpeta contiene los archivos relacionados con el análisis estadístico realizado en R:</p>

<ul>
  <li><code>Dino_Regression.Rmd</code>: Archivo Markdown de R donde se explica el análisis y la regresión realizada sobre el dataset Datasaurus Dozen.</li>
  <li><code>Dino_Regression.html</code>: Versión HTML generada automáticamente a partir del archivo R Markdown, que muestra el análisis de manera interactiva y visual.</li>
  <li><code>Visual_Dino_Regression.jpg</code>: Imagen generada durante el análisis que muestra la regresión aplicada al dataset Datasaurus Dozen, ilustrando visualmente los resultados obtenidos.</li>
</ul>

<hr style="border: 1px solid #ecf0f1; margin-top: 40px;"/>

<p style="font-style: italic; color: #7f8c8d;">Esta organización permite separar claramente los datos crudos del análisis y las visualizaciones generadas, facilitando la comprensión y replicación del estudio.</p>

</div>

