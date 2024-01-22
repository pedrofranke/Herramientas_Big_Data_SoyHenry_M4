# Integrador-M4

En este documento se describe brevemente lo realizado en el proyecto integrador del modulo 4 del curso de Data Science en SoyHenry. Este proyecto trata sobre las principales aptitudes para ser Data Engineer, aplicando numerosas herramientas del ecosistema apache en diversos contenedores del servicio docker.

Para ver los detalles paso a paso de la resolucion, por favor guiarse mediante el archivo Resuelto.ipynb.

## Proyecto integrador Henry - Evidencia

### Paso 0: Resizing VM

Para incrementar el espacio de almacenamiento de la maquina virtual dada en el curso, debemos seguir los pasos mencionados en este [archivo] (/Resizing.ipynb).

### Paso 1: Hadoop

Hadoop y, principalmente hdfs, es una herramienta que permite la accesibilidad y consistencia de la informacion dentro de un conjunto de servidores.

### Paso 2: Hive

Hive es una herramienta que permite la gestion de bases de datos relacionales dentro del entorno de hadoop y archivos particionados.

En este paso aprenderemos a ejecutar un script Hive dentro de un contenedor, cuyo objetivo es crear tablas a partir de nuestros Datasets DENTRO DEL ENTORNO HDFS y trabajar sobre ellas.

### Paso 3: Formatos de Almacenamiento

En este punto se trabajara sobre los distintos formatos de almacenamiento, desde .csv hasta .parquet para poder optimizar los espacios de memoria en los contenedores.

### Paso 4: SQL

Aprenderemos a ejecutar consultas y gestiones de bases de datos relacionales dentro del ecosistema Apache con Apache Hive.

### Paso 5: NoSQL

#### Hbase

Uso de Hbase, un sistema de gestion de bases de datos no relacional con un sistema de almacenamiento orientada en columnas, es decir, cada elemento tiene los atributos sobre los que haya informacion. Muy utilizada la gestion de datos de atributos tales como las redes sociales.

#### Mongodb

Es un sistema de gestion de bases de datos no relacional, muy potente por admitir diferentes tipos de elementos, tales como archivos de audio, documentos, etc.

#### Neo4j

Es un sistema de gestion de bases de datos que almacena la informacion en nodos y relaciones entre nodos.

#### Zeppelin

Es un web notebook en donde podremos trabajar de manera unificada en los distintos lenguajes de programacion vistos anteriormente, esto facilita la gestion general de los scripts.

### Paso 6: Spark

#### Spark y Scala

Apache Spark es un sistema de procesamiento distribuido de código abierto que se utiliza para cargas de trabajo de macrodatos. Utiliza el almacenamiento en caché de memoria y una ejecución de consulta optimizada para consultas rápidas de análisis de cualquier tamaño.
 
#### Kafka

Apache Kafka es una popular plataforma de streaming de eventos que sirve para recoger, procesar y almacenar datos de eventos de streaming o datos sin principio ni final concretos.


