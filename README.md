# Proyecto de Análisis de Datos: Reducción de Siniestros Viales en Buenos Aires

![Accidente de trafico](src/accidentes-de-tr%C3%A1fico.png)

## Descripción del Proyecto

Este proyecto tiene como objetivo utilizar análisis de datos para abordar el problema de los siniestros viales en la Ciudad Autónoma de Buenos Aires (CABA). Los siniestros viales son una preocupación importante debido al alto volumen de tráfico y la densidad poblacional en la ciudad, y este análisis busca proporcionar información valiosa para que las autoridades locales tomen medidas para reducir la cantidad de víctimas fatales en estos incidentes.

## Contenido del README

- [Contexto](#contexto)
- [Entidades Involucradas](#entidades-involucradas)
- [Metodología y Tecnologías](#metodología-y-tecnologías)
- [Estructura del Repositorio](#estructura-del-repositorio)
- [Cómo Usar el Dashboard](#cómo-usar-el-dashboard)
- [KPIs Calculados](#kpis-calculados)
- [Conclusiones](#conclusiones)
- [Desafíos Adicionales](#desafíos-adicionales)
- [Fuente de datos](#fuente-de-datos)
- [Repositorio](#repositorio)
- [Contacto](#contacto)

## Contexto

En Argentina, los siniestros viales siguen siendo la principal causa de muertes violentas, con miles de personas falleciendo cada año. Este análisis se basa en el dataset de Homicidios proporcionado por Buenos Aires Data y se centra en el periodo de 2016 a 2021, que es el periodo de datos que tenemos.

## Entidades Involucradas

- Observatorio de Movilidad y Seguridad Vial (OMSV), bajo la órbita de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires.

## Metodología y Tecnologías

- **Extraccion, Transformacion y carga de datos (ETL):** La estraccion y carga de datos, estan resueltas en Python y Pandas, en un notebook de Jupyter (ETL.ipynb), y la carga de datos, se hizo hacia nuestro dashboard en PowerBI.

- **Análisis Exploratorio de Datos (EDA):** Se exploraron los datos en un notebook de Jupyter. Se realizaron pasos documentados con claridad, incluyendo la búsqueda de valores faltantes, valores atípicos y registros duplicados, se hicieron analisis extras, para poder tener una comprension mayor sobre los datos que tenemos.

- **Dashboard Interactivo:** Se creó un dashboard interactivo que permite explorar los datos de manera detallada utilizando PowerBI, donde hubo unas modificaciones en PowerQuery, se creo una tabla Calendario, se incluyeron dos datasets, uno sobre el flujo vehicular en CABA, y otro sobre la poblacion anual en CABA.

- **KPIs:** Se calcularon y presentaron tres KPIs clave relacionados con la seguridad vial en CABA y se ubicarion junto con sus variables objetivo, en una tabla llamada 'Metricas_KPI'.

- **Repositorio de GitHub:** Se utilizó un repositorio de GitHub para almacenar y compartir el código y los resultados del proyecto.

## Estructura del Repositorio

- **Notebooks:** Carpeta que contiene el notebook de Jupyter utilizado para el EDA y el cálculo de KPIs.

- **Dashboard:** Carpeta que contiene el archivo pbix (PowerBI) con el dashboard interactivo.

- **Data:** Carpeta que almacena los datasets utilizados en el proyecto.

- **src:** Carpeta que contiene las imagenes utilizadas para este README.md.

- **README.md:** Este archivo, que proporciona información general sobre el proyecto.

## Cómo Usar el Dashboard

1. Clona o descarga este repositorio en tu computadora.

2. Navega a la carpeta "Dashboard" y ejecuta el archivo pbix del dashboard.

3. Debes tener instalada alguna variante de PowerBI.

3. El dashboard se abrirá en tu PowerBI y podrás interactuar con él para explorar los datos.

## KPIs Calculados

1. **Reducción en la Tasa de Homicidios:** Reduccion en un 10% de la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.

2. **Reducción en la Cantidad de Accidentes Mortales de Motociclistas:** Reduccion en un 7% de la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.

3. **Reducción en la Cantidad de Accidentes Mortales sucedidos en avenidas:** Reduccion en un 20% de la cantidad de accidentes mortales en avenidas (la arteria mas frecuente) en el último año, en CABA, respecto al año anterior.

## Conclusiones

Este proyecto, brindo mucha informacion sobre los accidentes y muertes en buenos aires, informacion que se ve detallada en el EDA, y informacion adicional, expresada en una presentacion del Dasboard.

## Desafíos Adicionales

En busca de un perfil Junior Advanced, se abordaron desafíos adicionales que incluyen la implementacion de dos datasets externos para obtener mas informacion relevante para explicar situaciones incapaces de explicar con nuestros datos bases. Ademas de 

## Fuente de Datos

- [Buenos Aires Data - Homicidios](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales)

## Repositorio

El código fuente de este proyecto se encuentra en el siguiente repositorio: [Enlace al Repositorio](https://github.com/Tototastico/Proyecto-Data-Analisys)

## Contacto

Si tienes alguna pregunta o comentario sobre este proyecto, contactame a través de [sirnetobias1@gmail.com].

## Developed by:
Tobias Ezequiel Sirne
