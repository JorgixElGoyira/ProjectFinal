# Identificación del gen BMP2 en especies pertenecientes al orden Squamata

* Jorge I. Jaramillo (jijaramillor@puce.edu.ec)
* Junio 26, 2025

## Objetivo del estudio

* En este proyecto nos centraremos en la identificación de especies del orden Squamata que presenten el gen BMP2, encargado del manteniemto óseo en el desarrollo embrionario, para conocer su posible coevolución entre estas especies.

## Requisitos para el desarrollo

* Nuestro grupo de estudio será las especies pertenecientes al orden Squamata (lagartijas, serpientes, etc) que posean este gen mediante la guía de la base de datos NCBI y el uso de la base de datos de genes ortólogos entregada en el curso.
* Adicional a la base de datos, es necesario utilizar diferentes programas para generar una filogenia mediante iqtree y figtree donde se presenten todos lo genes ortólogos de la base de datos entregada especificando las especies que poseen el gen BMP2.

* Ejemplo de Candoia aspera:

![Candoia aspera](https://inaturalist-open-data.s3.amazonaws.com/photos/118898268/original.jpeg)

## Programas a utilizar

* Los programas que se van a utilizar en este proyecto son:

* Muscle: Este programa lo utilizamos para generar secuencias de genes alineadas utilizando la base del gen ortólogo BMP2 obtenida de la base de datos de genes ortólogos entregadas al curso.
* IQtree: A este programa se lo activa tras obtener las secuencias alineadas, ya que nos permitirá generar un archivo de filogenia con las especies que poseen el gen BMP2 y organizadas con respecto a su aparición.
* Atom: Este programa utiliza archivos denominados rna.fna, los cuales nos permite identificar las especies que aparecen en la filogenia mediante su nombre científico y geneID.
* FigTree: Este programa utiliza archivos denominados .treefile, este tipo de archivos poseen la filogenia hecha en iqtree y la podremos visualizar en FigTree.

(<img width="1365" height="691" alt="image" src="https://github.com/user-attachments/assets/7474b980-059f-49ae-a477-93833fdf0790" />)

Aquí se observa el archivo muscleBMP2_rna.fna visualizado en el programa Atom, donde se presentan 14 registros del orden Squamata con el gen BMP2 donde se presentan las especies Candoia aspera, Python bivittatus, Protobothrops mucrosquamatus, Crotalus tigris, Pseudonaja textilis, Notechis scutatus, Erythrolamprus reginae, Thamnophis sirtalis, Thamnophis elegans, Ahaetulla prasina, Pituophis catenifer annectens, y Pantherophis guttatus.


(<img width="1137" height="598" alt="image" src="https://github.com/user-attachments/assets/7355e1fc-1460-4b0f-adf2-dcec9e0683c6" />
)

Aquí se observa el archivo muscleBMP2_rna.fna.treefile visualizado en el programa FigTree, donde se presentan los 14 registros mediante un código propio: XM_063316078.1 Candoia aspera; XM_063316086.1 Candoia aspera; XM_007427029.3 Python bivittatus; XM_015813549.2 Protobothrops mucrosquamatus; XM_039359446.1 Crotalus tigris; XM_0393559445.1 Crotalus tigris; XM_026710399.1 Pseudonaja textilis; XM_026668524.1 Notechis scutatus; XM_070732675.1 Erythrolamprus reginae; XM_014068423.1 Thamnophis sirtalis; XM_032214290.1 Thamnophis elegans; XM_058181271.1 Ahaetulla prasina; XM_070956260.1 Pituophis catenifer annectens;y XM_034432344.1 Pantherophis guttatus.

## Conclusiones

Gracias a esa filogenia podemos observar que la primera especie en presentar el gen BMP2 es Candoia aspera, y puede haber una posible coevolución entre las especies Pseudonaja textilis y Notechis scutatus, al igual que Thamnophis sirtalis con Thamnophis elegans, y Pituophis catenifer annectens con Pantherophis guttatus. Siendo el segundo caso el más propenso a ser excluído de ser tratado como una coevolución por el hecho de que ambas especies pertenecen al mismo género.
