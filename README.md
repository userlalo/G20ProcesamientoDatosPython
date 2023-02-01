{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "mount_file_id": "1juye3PzPdcKh0MY0uYyu25b-7uMiMSxL",
      "authorship_tag": "ABX9TyOl3+armkStywQbM65efNlA",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/userlalo/G20ProcesamientoDatosPython/blob/main/G20PDP.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "#PROCESAMIENTO DE DATOS CON PYTHON\n",
        "\n",
        "*   I Identificación de Problema\n",
        "*   II Planteamiento de Preguntas\n",
        "*   III Colección de Datos\n",
        "*   IV Analisis Exploratorio de Datos (EDA)\n",
        "*   V Limpieza de Datos\n",
        "*   VI Transformación de datos\n",
        "*   VII Ordenamiento de Código (criterio 5,3,0)\n",
        "*   VIII APIs (Opcional)"
      ],
      "metadata": {
        "id": "1uT6sEM9VmNQ"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "##EQUIPO G20\n",
        "*   Doníz Padilla Brenda Grisel\n",
        "*   García Fragoso Nestor Abdy\n",
        "*   Gudiño Ramirez Gustavo\n",
        "*   Jimenez Rodriguez Paola Guadalupe\n",
        "*   Medina Rodríguez Eduardo\n",
        "*   Pando Barrón Jésus"
      ],
      "metadata": {
        "id": "55COYgPunKcx"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "### I .- IDENTIFICACION DE PROBLEMA\n",
        "*   Identificación y justificación\n",
        "  *   Incidencia Delicitiva en México (posibles causas, principales victimas y predicciones)\n",
        "  *   Se busca tener un conocimiento mas amplio sobre indices delictivos analizando las incidencias delictivas y sus posibles origenes, demografias de las victimas y predicciones como manera de tener un panorama actual y futuro de México . \n",
        "\n",
        "\n",
        "*   Investigación preliminar\n",
        "  *   Existe información por País en el portal de United Nations Office of Drugs and Crimes /https://dataunodc.un.org/content/country-list que provee una vista general de indices delictivos \n",
        "  *   La página oficial de el gobierno de México ofrece datos públicos 2015-2022 en formato csv acerca de la incidencia delictiva por estado y municipio, asi como cifras (demografias) de victimas del fuero común /https://www.gob.mx/sesnsp/acciones-y-programas/datos-abiertos-de-incidencia-delictiva?state=published\n",
        "  *   La página oficial de el gobierno de México ofrece datos públicos en formato csv sobre las proyecciones de poblacion de los Municipios de México 2015-2030 /https://datos.gob.mx/busca/dataset/proyecciones-de-la-poblacion-de-mexico-y-de-las-entidades-federativas-2016-2050/resource/0e21e97e-1faf-4045-8dc2-06691e0379a8?inner_span=True\n",
        "    *   La página oficial de el gobierno de México  a través de la CONAGUA ofrece datos públicos en formato csv sobre las temperaturas promedio por entidad federativa de México 2015-2022 /https://smn.conagua.gob.mx/es/climatologia/temperaturas-y-lluvias/resumenes-mensuales-de-temperaturas-y-lluvias\n",
        "  *   La CONEVAL ofrece indicadores de pobreza y rezago social Nacional y estatal 2016-2020  /https://datos.gob.mx/busca/dataset/indicadores-de-pobreza-nacional-y-estatal-2016-2020\n",
        "\n",
        "*   Informacion previa  sobre las soluciones anteriores al problema\n",
        " \n",
        "  *   Chicago Crime /https://www.kaggle.com/datasets/chicago/chicago-crime\n",
        "  *   Crimes in Boston /https://www.kaggle.com/datasets/AnalyzeBoston/crimes-in-boston\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "HrCb16FbZvnV"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "###II .- PLANTEAMIENTO DE PREGUNTAS\n",
        "\n",
        "*   5 Preguntas pertinentes sobre el tema (Sesion 2)\n",
        "\n",
        "  *   Cuales son los crímenes mas comunes ?\n",
        "  *   Cuales son los tipos de crímenes mas probables a ocurrir?\n",
        "  *   La fecuencia de los crímenes cambia con respecto al tiempo (día, semana, mes, año)\n",
        "  *   Que categorías de crímen exhiben el mayor crecimiento del 2015 al 2022\n",
        "  *   Como afecta la temperatura la tasa de incidencia de un crimen violento\n",
        "  *   Quienes son las principales victimas de los crimenes con mayor incidencia (Por protección a las victimas no daremos datos de ubicación precisos y nos limitaremos a presentar demografias generalizadas de las principales victimas)\n"
      ],
      "metadata": {
        "id": "duTHniNga_S7"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "###III .- COLECCION DE DATOS\n",
        "\n",
        "*   Obtener coleccion de datos completa y no previamente procesada\n",
        "*   Los datos recopilados pueden responder completamente las preguntas planteadas"
      ],
      "metadata": {
        "id": "JQKHvgpfbR04"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "###IV .- ANALISIS EXPLORATORIO DE DATOS (EDA)\n",
        "\n",
        "*   Convertir de forma adecuada la coleccion de datos en un DataFrame de pandas as pd 😲\n",
        "*   Realizar EDA a través del uso correcto de pandas"
      ],
      "metadata": {
        "id": "1dqmoQyvbS3T"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "###V .- LIMPIEZA DE DATOS\n",
        "\n",
        "*   El nuevo DataFrame no contiene ningun NaN\n",
        "*   El DataFrame esta correctamente indexado (en orden y sus índices coherentes)\n",
        "*   Las columnas estan correctamente nombradas\n",
        "*   Se aplicaron agregaciones al Dataset para poder comenzar a responder algunas de las preguntas planteadas"
      ],
      "metadata": {
        "id": "Yh47yxhCbT13"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "###VI .- TRANSFORMACION DE DATOS\n",
        "\n",
        "*   Todos los datos de cada columna tienen un valor correcto dependiento del tipo de dato (fechas, objetos, ints, floats)\n",
        "*   Todas las coljumas de texto estan manipuladas para estar en formato correcto\n",
        "*   Hay nuevas columnas con nuevos datos resultantes del procesamiento de una o mas colunnas originales\n",
        "*   Se crearon otros Datasets -subconjuntos-series que presentan informacion relevante para una pregunta especifica o simplemente para exploraciones mas profundas"
      ],
      "metadata": {
        "id": "4lVUSVaQbUsV"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "### VII .- ORDENAMIENTO DE CODIGO (CRITERIO 5,3,0)\n",
        "\n",
        "*   Se entrego un Jupyter Notebook ordenado y limpio que contiene todos los pasos llevados a cabo para el procesamiento de datos\n",
        "*   El Notebook hace uso de las diversas técnicas aprendidas a través de las clases para la exploración y procesamiento de datos\n",
        "*   El Notebook contiene el código (nombrado correctamente) de todas las sesiones pasadas"
      ],
      "metadata": {
        "id": "zwtI8PcjbVjp"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "###VIII .- APIs (Opcional)\n",
        "\n",
        "*   Se entregó un Notebook extra que contiene el código para correctamente hacer un llamado a una API para su colección en un Data Frame"
      ],
      "metadata": {
        "id": "61r-nbpvm8Pj"
      }
    }
  ]
}
