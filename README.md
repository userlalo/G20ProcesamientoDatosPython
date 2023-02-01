PROCESAMIENTO DE DATOS CON PYTHON
I Identificación de Problema
II Planteamiento de Preguntas
III Colección de Datos
IV Analisis Exploratorio de Datos (EDA)
V Limpieza de Datos
VI Transformación de datos
VII Ordenamiento de Código (criterio 5,3,0)
VIII APIs (Opcional)
EQUIPO G20
Doníz Padilla Brenda Grisel
García Fragoso Nestor Abdy
Gudiño Ramirez Gustavo
Jimenez Rodriguez Paola Guadalupe
Medina Rodríguez Eduardo
Pando Barrón Jésus
I .- IDENTIFICACION DE PROBLEMA
Identificación y justificación

Incidencia Delicitiva en México (posibles causas, principales victimas y predicciones)
Se busca tener un conocimiento mas amplio sobre indices delictivos analizando las incidencias delictivas y sus posibles origenes, demografias de las victimas y predicciones como manera de tener un panorama actual y futuro de México .
Investigación preliminar

Existe información por País en el portal de United Nations Office of Drugs and Crimes /https://dataunodc.un.org/content/country-list que provee una vista general de indices delictivos
La página oficial de el gobierno de México ofrece datos públicos 2015-2022 en formato csv acerca de la incidencia delictiva por estado y municipio, asi como cifras (demografias) de victimas del fuero común /https://www.gob.mx/sesnsp/acciones-y-programas/datos-abiertos-de-incidencia-delictiva?state=published
La página oficial de el gobierno de México ofrece datos públicos en formato csv sobre las proyecciones de poblacion de los Municipios de México 2015-2030 /https://datos.gob.mx/busca/dataset/proyecciones-de-la-poblacion-de-mexico-y-de-las-entidades-federativas-2016-2050/resource/0e21e97e-1faf-4045-8dc2-06691e0379a8?inner_span=True
La página oficial de el gobierno de México a través de la CONAGUA ofrece datos públicos en formato csv sobre las temperaturas promedio por entidad federativa de México 2015-2022 /https://smn.conagua.gob.mx/es/climatologia/temperaturas-y-lluvias/resumenes-mensuales-de-temperaturas-y-lluvias
La CONEVAL ofrece indicadores de pobreza y rezago social Nacional y estatal 2016-2020 /https://datos.gob.mx/busca/dataset/indicadores-de-pobreza-nacional-y-estatal-2016-2020
Informacion previa sobre las soluciones anteriores al problema

Chicago Crime /https://www.kaggle.com/datasets/chicago/chicago-crime
Crimes in Boston /https://www.kaggle.com/datasets/AnalyzeBoston/crimes-in-boston
II .- PLANTEAMIENTO DE PREGUNTAS
5 Preguntas pertinentes sobre el tema (Sesion 2)

Cuales son los crímenes mas comunes ?
Cuales son los tipos de crímenes mas probables a ocurrir?
La fecuencia de los crímenes cambia con respecto al tiempo (día, semana, mes, año)
Que categorías de crímen exhiben el mayor crecimiento del 2015 al 2022
Como afecta la temperatura la tasa de incidencia de un crimen violento
Quienes son las principales victimas de los crimenes con mayor incidencia (Por protección a las victimas no daremos datos de ubicación precisos y nos limitaremos a presentar demografias generalizadas de las principales victimas)
III .- COLECCION DE DATOS
Obtener coleccion de datos completa y no previamente procesada
Los datos recopilados pueden responder completamente las preguntas planteadas
IV .- ANALISIS EXPLORATORIO DE DATOS (EDA)
Convertir de forma adecuada la coleccion de datos en un DataFrame de pandas as pd 😲
Realizar EDA a través del uso correcto de pandas
V .- LIMPIEZA DE DATOS
El nuevo DataFrame no contiene ningun NaN
El DataFrame esta correctamente indexado (en orden y sus índices coherentes)
Las columnas estan correctamente nombradas
Se aplicaron agregaciones al Dataset para poder comenzar a responder algunas de las preguntas planteadas
VI .- TRANSFORMACION DE DATOS
Todos los datos de cada columna tienen un valor correcto dependiento del tipo de dato (fechas, objetos, ints, floats)
Todas las coljumas de texto estan manipuladas para estar en formato correcto
Hay nuevas columnas con nuevos datos resultantes del procesamiento de una o mas colunnas originales
Se crearon otros Datasets -subconjuntos-series que presentan informacion relevante para una pregunta especifica o simplemente para exploraciones mas profundas
VII .- ORDENAMIENTO DE CODIGO (CRITERIO 5,3,0)
Se entrego un Jupyter Notebook ordenado y limpio que contiene todos los pasos llevados a cabo para el procesamiento de datos
El Notebook hace uso de las diversas técnicas aprendidas a través de las clases para la exploración y procesamiento de datos
El Notebook contiene el código (nombrado correctamente) de todas las sesiones pasadas
VIII .- APIs (Opcional)
Se entregó un Notebook extra que contiene el código para correctamente hacer un llamado a una API para su colección en un Data Frame
