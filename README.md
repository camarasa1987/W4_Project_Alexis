# Project: ETL Alexis Camarasa

Extraigo, transformo y cargo datos.

¿ Como ?

- Extraigo datos de un archivo madre "d.cvs" extraído del portal kaggle.com sobre la temática de tipos de Dinosaurios

- Luego realizo un primer scrapping del porta "American Museum of Natural History" donde consigo agregar 50 nuevos nombres de especies de dinosaurios a mi data frame

- Vuelvo a utilizar la técnica de scrapping, pero esta vez, desde el portal de wikipedia que obtengo al realizar la siguiente búsqueda en Google: "European Dinosaurs". Es así como consigo, no solo agregar 200 nuevas especies de dinosaurios, sino que además agrego una columna más a mi df con los nombres de los países de la comunidad europea (UE) donde se han encontrado estas nuevas especies.

- Procuro presentar mi df final sin valores nulos y en forma homogénea.

- Cargo mi nuevo archivo .csv a una nueva base de datos que creo en MySQL Workbench

Espero puedan sacarle provecho a esta base de datos enriquecida la cual nos permite conocer gran parte de las distintas especies, por nombres de dinosaurios, que existieron :)



