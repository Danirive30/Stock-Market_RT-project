# Stock Market Kafka Real-Time Data Engineering Project

## 📘 Introducción
Este proyecto implementa un pipeline de datos en tiempo real para datos del mercado de valores usando Kafka, con un enfoque en la ingeniería de datos de extremo a extremo. A través de este proyecto, exploramos el uso de diversas tecnologías y servicios de Amazon Web Services (AWS) para construir una arquitectura de datos en tiempo real que permite procesar, almacenar y consultar datos de manera eficiente.

## 🏗 Arquitectura
Este proyecto utiliza una arquitectura de datos basada en Kafka para la ingesta de datos en tiempo real, que posteriormente se almacena en S3 y se consulta con Athena y Glue. La arquitectura consta de las siguientes etapas:
1. **Ingesta de datos** en tiempo real con Apache Kafka.
2. **Almacenamiento de datos** en AWS S3.
3. **Catalogación y descubrimiento** de datos usando Glue Crawler y Glue Catalog.
4. **Consulta de datos** con AWS Athena.
5. **Orquestación y monitoreo** en una instancia de EC2 en AWS.

## 🛠️ Tecnologías Utilizadas
Este proyecto utiliza las siguientes tecnologías:
- **Lenguaje de programación**: Python
- **Amazon Web Services (AWS)**:
  - **S3**: para el almacenamiento de datos
  - **Athena**: para consultas y análisis de datos
  - **Glue Crawler y Glue Catalog**: para catalogar y descubrir datos en S3
  - **EC2**: para el entorno de orquestación y monitoreo
- **Apache Kafka**: para la ingesta de datos en tiempo real

## 📊 Dataset Utilizado
Para este proyecto, se puede utilizar cualquier dataset de mercado de valores, ya que el foco está en la construcción de un pipeline de datos en tiempo real. Aquí está el dataset usado como referencia en el tutorial: [indexProcessed.csv](https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/indexProcessed.csv).

## 📺 Tutorial Completo en Video
Para una guía paso a paso de la implementación de este proyecto, puedes ver el siguiente tutorial: [Video Tutorial](https://www.youtube.com/embed/KerNf0NANMo).

## 🚀 Cómo Empezar
1. **Configura Apache Kafka** en una instancia de EC2 para la ingesta de datos.
2. **Carga el dataset** en Kafka para su procesamiento en tiempo real.
3. **Configura S3** en AWS para almacenar los datos.
4. **Crea un Crawler y un catálogo de datos** en Glue para la organización y descubrimiento de datos.
5. **Ejecuta consultas en Athena** para analizar los datos almacenados en S3.
6. **Monitorea el pipeline** desde EC2 para asegurar la operación en tiempo real.

## 📄 Licencia
Este proyecto se distribuye bajo la licencia MIT. Para más información, consulta el archivo LICENSE en este repositorio.

## 🤝 Contribuciones
¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar este proyecto, no dudes en abrir un issue o enviar un pull request.


# Stock-Market_RT-project
