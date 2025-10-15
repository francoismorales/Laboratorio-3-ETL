# Laboratorio 3 - Desarrollo de ETL en Google Cloud Platform

## Objetivos
- Entender con un ejercicio práctico los fundamentos y componentes básicos de un proceso ETL.
- Extender y desplegar un proceso ETL encargado de extraer información transaccional para ser cargada en un modelo multidimensional en una bodega de datos.
- Familiarizarse con algunas herramientas del proveedor de nube GCP para el desarrollo y despliegue de ETLs como son Google Storage, Google Cloud DataPrep y BigQuery.

## Herramientas
- [GCP Storage](https://cloud.google.com/storage?hl=es): Servicio nativo de data lake proporcionado por GCP para almacenar datos no estructurados.
- [GCP DataPrep](https://cloud.google.com/bigquery?hl=es): Servicio de datos que permite extraer, limpiar y preparar datos de forma gráfica.
- [GCP BigQuery](https://cloud.google.com/bigquery?hl=es): Plataforma de analítica de datos provista por GCP que va a desempeñar el rol de bodega de datos Data warehouse.

## Importante: Antes de la sesión de laboratorio
Redimir los créditos de forma individual a partir del correo que debe llegarles a sus cuentas. También está disponible en la sección noticas del curso unificado. En esta modalidad no se deben generar gastos de tarjeta de crédito.

Tenga en cuenta que el presente laboratorio se debe desarrollar y entregar en grupos. Sin embargo, el acceso a GCP es individual y cada estudiante contará con USD$50 para propósitos de experimentación. Estos créditos son más que suficientes para la realización del laboratorio. Además, deben reservar créditos para desarrollar el proyecto 2.

## Caso de estudio
**WWI (Wide World Importers)** es una empresa distribuidora que ofrece productos variados a clientes retail y naturales al mayor y al detal en diferentes ciudades de Estados Unidos.

Actualmente, la empresa se encuentra contratando un servicio de consultoría de BI con el propósito de construir herramientas analíticas para la toma decisiones basadas en datos.
Como proyecto piloto, con el objetivo de tener mayor visibilidad de sus procesos de inventario y ventas, WWI desea construir una bodega de datos en donde se incluya información histórica de las órdenes, con el detalle de los productos y tipos de empaque, agregadas por día. Adicionalmente, para WWI también es importante conocer cuanto generan las órdenes por dia en Valor Bruto de la Mercancía (GMV) .

Dado lo anterior, WWI contrata a su equipo de trabajo para que realice la implementación y despliegue de una bodega de datos y un proceso ETL que cumpla con el requerimiento planteado.

Más detalles del caso de estudio se pueden encontrar [aquí](https://learn.microsoft.com/en-us/sql/samples/wide-world-importers-what-is?view=sql-server-ver16).
