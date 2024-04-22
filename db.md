<!--Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.-->

DB_NAME: dealership

Table name: seconhandCars

- ID | INDEX | INT | PK | NOTNULL | UNIQUE | AI
- brand | VARCHART(10) | NOTNULL
- model | VARCHART(50)| NOTNULL
- fuel | VARCHART(10) | NULL
- mileage_reading | MEDIUMINT| NOTNULL 
- capacity | TINYINT | NULL 
- registration_date | DATE | NULL 
- color | VARCHART(15) | NULL 
- gearbox | VARCHART(20) | NULL
- trasmission | VARCHART(20) | NULL 
- horsepower |VARCHART (5)| NULL 
- certificate_available | TINYINT | NULL
- price | MEDIUMINT | NULL
- condition | VARCHART(20) | NULL
- note | TEXT | NULL

## TABLE

| ID | brand | model | fuel | mileage_reading | capacity | registration_date | color | gearbox | horsepower | certificate_available | price | condition | note |
|:--:|:-----:|:-----:|:----:|:---------------:|:--------:|:-----------------:|:-----:|:-------:|:----------:|:---------------------:|:-----:|:----------|:----:|
|1   |       |       |      |                 |          |                   |        |        |            |                       |       |           |      |
|2   |       |       |      |                 |          |                   |        |        |            |                       |       |           |      |
|3   |       |       |      |                 |          |                   |        |        |            |                       |       |           |      |