# README Open Data Project
## Introducción
El siguiente código busca almacenar los datos principales acerca de los productos, en este caso juguetes para niñas.
El objetivo es tener estos datos a mano, para luego poder realizar comparaciones entre precios, ver tendencias en precios, disponibilidad de los productos u otro tipo de información relevante.

## Pre-requisitos:
1. - Aplicaciones de procesado de texto y planillas (tales como Microsoft Office o G Suite)
2.  - IDE (o similar) compatible con las librerías utilizadas.

## Instalación:
Se puede ejecutar directamente desde google Colab sin necesidad de instalar nada, ó bien desde un IDE de preferencia.

## Environment:
Language : Python

Libraries : 
- pandas 
- bs4
- nltk
- requests
- csv

## Resultado:
Una vez ejecutado el script, el output debería ser un archivo csv con los datos de los objetos de la página scrapeada.
Datos extraídos:
En el archivo csv se guardan los datos en tres columnas:
1. - *Producto:* Esta columna contiene el nombre de los productos recolectados.
2. - *Precio:* El precio de cada producto, en formato string.
3. - *Fecha:* Se registra la fecha en el que se realiza el scraping, para que, en caso de que existan variaciones de precios o de productos, tener estos datos. 

## Autores:
- Karen Noemí Riveros Genes | UPA - TIE| Cohorte 2019 
- Pablo Daniel Pedrozo Ramírez | UPA - TIE| Cohorte 2019 

## Fecha:
Junio, 2021

## Permisos:
Para la realización de este trabajo, se hizo un web scraping de los datos públicos del supermercado stock. El mismo no especifica ninguna licencia acerca del uso de los datos, pero en sus condiciones de uso aclara que los datos están disponibles sólo para uso comercial del retail. Por esta razón, como autores del trabajo, declaramos estar bajo nuestro propio riesgo al momento de realizar el web scraping.

### *End*
