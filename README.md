# VM Elasticic Server y Cluster Hadoop en Google Cloud

## Descripción

Este repositorio contiene un notebook que documenta una práctica realizada utilizando Elasticsearch y Hadoop en Google Cloud. El objetivo de esta práctica fue analizar y visualizar datos sobre trenes españoles, aprovechando las capacidades de búsqueda y análisis de Elasticsearch junto con la infraestructura de Hadoop.

## Tecnologías Utilizadas

- **Google Cloud Platform (GCP)**
  - Maquina Virtual ----> Elastic Server
  - Cluster Hadoop -----> Cluster 1 máster 2 slaves
  - Google Cloud Storage (Buckets) ----> Data Lake
- **Elasticsearch**
- **Kibana**
- **Hadoop**
- **Python (Jupyter Notebook)**

## Fuente de Datos

Los datos utilizados en esta práctica provienen de la siguiente fuente:
- [Datos.gob.es - Transporte](https://datos.gob.es/en/catalogo?theme_id=transporte&res_format_label=JSON)

### Detalles de los Datos

Se recopilaron datos sobre trenes españoles, incluyendo información sobre ingresos, plazas ofertadas, y más.

## Pasos Realizados

1. **Configuración de la Maquina Virtual en GCP**: Se creó una instancia de VM para hacer un server con Elasticsearch y Kibana
2. **Implementación de un Cluster Hadoop**: Se configuró un cluster Hadoop para el procesamiento de datos.
3. **Carga de Datos**: Se almacenaron los datos en un bucket de Google Cloud Storage.
4. **Indexación en Elasticsearch**: Los datos se indexaron en un clúster de Elasticsearch para facilitar la búsqueda y análisis.
5. **Visualización en Kibana**: Se creó un dashboard en Kibana para visualizar los datos de los trenes españoles.

**Author: Fernando Beneytez.**

**Tutor/Mentor: Alex Saez.**
