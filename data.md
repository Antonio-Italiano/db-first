struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario!

 CARS                | TYPES        | INDICI      | ATTRIBUTI            |
 ------------------- | ------------ | ----------- | -------------------- |
 ID                  |              | PRIMARY KEY | NOT NULL, UNIQUE, AUTO INCREMENT |
 LICENSE PLATE       | CHAR(7)      |             | NOT NULL, UNIQUE     |
 FRAME NUMBER        | CHAR(17)     |             | NOT NULL, UNIQUE     |
 BRAND NAME          | VARCHAR(50)  |             | NOT NULL             |
 REGISTRATION YEAR   | YEAR         |             | NOT NULL             | 
 CAR DISPLACEMENT    | SMALLINT     |             | NOT NULL             |
 ALIMENTATION        | VARCHAR(5)   |             | NOT NULL             |
 KM                  | MEDIUMINT    |             | NOT NULL             |
 COLOR               | CHAR(3)      |             | NOT NULL             |
 CONDITION           | VARCHAR(255) |             | NOT NULL             | 
 OPTIONAL            | VARCHAR(255) |             | NOT NULL             |
 EMISSIONS           | TINYINT      |             | NOT NULL             |
 AS_CABRIOLET        | TINYINT(1)   |             | NOT NULL, DEFAULT(0) |
 DOORS               | CHAR(1)      |             | NOT NULL, DEFAULT(5) |
 PURCHASE PRICE      | MEDIUMINT    |             | NOT NULL             | 
 SELLING PRICE       | MEDIUMINT    |             | NOT NULL             |
 AS_AVAILABILITY'    | TINYINT(1)   |             | NOT NULL             | 
 NOTE                | VARCHAR(255) |             | NULL                 |
 PASSENGERS          | CHAR(2       |             | NOT NULL             |    
 PHOTO               | VARCHAR(255  |             | NULL                 | 