Guión
Trabaja como analista de riesgos en un banco. Además de otros servicios bancarios y de préstamos, el banco también ofrece servicios de tarjetas de crédito que son una fuente muy importante de ingresos para el banco. El banco desea comprender la demografía y otras características de sus clientes que aceptan una oferta de tarjeta de crédito y de los que no la aceptan.

Por lo general, los datos de observación para este tipo de problemas son algo limitados, ya que a menudo la empresa solo ve a aquellos que responden a una oferta. Para solucionar esto, el banco diseña un estudio de marketing enfocado, con 18.000 clientes actuales del banco. Este enfoque enfocado le permite al banco saber quién responde y quién no a la oferta, y utilizar los datos demográficos existentes que ya están disponibles sobre cada cliente.

Objetivo
Construya un modelo que proporcione información sobre por qué algunos clientes bancarios aceptan ofertas de tarjetas de crédito. También existen otras áreas potenciales de oportunidades que el banco desea comprender a partir de los datos.

Su alta dirección también ha publicado estas otras preguntas que les ayudarán a comprender mejor a sus clientes.

Conjunto de datos
Todos los archivos necesarios, así como el conjunto de datos, se pueden encontrar en el siguiente repositorio: Proyecto Mid-bootcamp - Clasificación .

El conjunto de datos consta de información sobre 18.000 clientes bancarios actuales del estudio. Estas son las definiciones de los puntos de datos proporcionados:

Número de cliente: un número secuencial asignado a los clientes (esta columna está oculta y excluida; este identificador único no se utilizará directamente).
Oferta aceptada: ¿El cliente aceptó (Sí) o rechazó (No) la oferta? Recompensa: El tipo de programa de recompensas que se ofrece para la tarjeta.
Tipo de correo: Carta o postal.
Nivel de ingresos: bajo, medio o alto.
Cuentas bancarias abiertas: cuántas cuentas que no son de tarjeta de crédito tiene el cliente.
Protección contra sobregiros: ¿Tiene el cliente protección contra sobregiros en su(s) cuenta(s) corriente(s) (Sí o No)?
Calificación crediticia: baja, media o alta.
Tarjetas de crédito retenidas: el número de tarjetas de crédito retenidas en el banco.
Viviendas propias: Número de viviendas que posee el cliente.
Tamaño del hogar: El número de personas en la familia.
Sea dueño de su casa: ¿El cliente es dueño de su casa? (Sí o No).
Saldo promedio: Saldo promedio de la cuenta (en todas las cuentas a lo largo del tiempo). T1, T2, T3 y T4
Saldo: El saldo promedio de cada trimestre del último año
Resultados esperados
Le recomendamos que comprenda completamente sus datos y tome las medidas necesarias para prepararlos para el modelado antes de construir modelos exploratorios o predictivos.

Dado que se trata de un modelo de clasificación, puede utilizar la regresión logística para la clasificación a fin de crear un modelo. También se recomienda utilizar otros modelos en su proyecto, incluidos los clasificadores KNN o los árboles de decisión.

1. Explorar los datos
Para explorar los datos , puede utilizar las técnicas que se han analizado en clase. Algunas de ellas incluyen el uso del método describe, la comprobación de valores nulos, el uso de Matplotlib y Seaborn para desarrollar visualizaciones.

Los datos tienen muchas variables categóricas y numéricas. Explore la naturaleza de los datos para estas variables antes de comenzar con el proceso de limpieza de datos y luego el preprocesamiento de datos (escalamiento de variables numéricas y codificación de variables categóricas).

Para la variable objetivo (Oferta aceptada – Sí/No), también es importante verificar el desequilibrio de datos, es decir, el número de personas que respondieron sí frente al número de personas que respondieron no.

2. Construye un modelo
Utilice diferentes modelos para comparar las precisiones y encontrar el modelo que mejor se ajuste a sus datos. Puede utilizar las medidas de precisión que se han analizado en clase. Tenga en cuenta que, al comparar diferentes modelos, asegúrese de utilizar la misma medida de precisión como referencia.

3. Visualizar
También utilizará Tableau para explorar visualmente los datos. Analizará en profundidad los datos de los clientes que aceptaron la oferta frente a los clientes que no lo hicieron y comprobará sus características. Por ejemplo, seleccionamos el Yesnivel en Oferta aceptada y luego examinamos la distribución de las ofertas aceptadas en las demás variables de nuestro conjunto de datos y, de manera similar, para las personas que no aceptaron la oferta.

Entregables
Una presentación de diapositivas : use slides.com para obtener plantillas simples pero efectivas.
Una presentación : Su presentación pública debe durar entre 5 y 7 minutos.
Consultas SQL : acceda al archivo de preguntas SQL y asegúrese de ejecutar estas consultas mediante SQL.
Un tablero de Tableau : siga las instrucciones de este archivo para crearlo en Tableau.
Código Python : se revisará tu código. Asegúrate de seguir las prácticas recomendadas explicadas en clase hasta el momento.
