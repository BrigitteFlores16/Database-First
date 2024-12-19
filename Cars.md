# Cars table

| name             | type          | attributes                         | key     | note                                           |
| ---------------- | ------------- | ---------------------------------- | ------- | ---------------------------------------------- |
| id               | BIGINT (20)   | NOT NULL - AUTOINCREMENT- UNSIGNED | Primary |                                                |
| vin              | CHAR(14)      | NOT NULL - UNIQUE                  |         | Vehicle Identification                         |
| make             | VARCHAR(50)   | NOT NULL                           |         | Marca dell'auto                                |
| model            | VARCHAR(50)   | NOT NULL                           |         | Modello dell'auto                              |
| manufacture_year | YEAR          | NOT NULL                           |         | Anno di produzione                             |
| color            | VARCHAR(10)   |                                    |         | Colore dell'auto                               |
| mileage          | INT           | NOT NULL                           |         | Chilometraggio                                 |
| fuel_type        | VARCHAR(4)    | NOT NULL                           |         | Tipo di carburante                             |
| transmission     | VARCHAR(2)    | NOT NULL                           |         | Tipo di trasmissione                           |
| price            | DECIMAL(10,2) | NOT NULL                           |         | Prezzo dell'auto                               |
| condition        | CHAR(1)       |                                    |         | "n" -> nuovo, "u" -> usato, "d" -> danneggiato |
| dealer_name      | VARCHAR(50)   |                                    |         | Nome del concessionario                        |
| dealer_location  | VARCHAR(100)  |                                    |         | indirizzo del concessionario                   |
| listed_at        | DATE          | NOT NULL                           |         | Data di inserimento                            |
