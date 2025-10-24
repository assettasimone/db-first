# Used Car Dealer Db Example
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table Name: (cars)

- id: NUMBER INT PRIMARY_KEY AI UNIQUE 
- type: STRING VARCHAR(13) NULL
- name: STRING VARCHAR(35) NOT-NULL
- brand: STRING VARCHAR(25) NOT-NULL
- motor-CC: NUMBER FLOAT(2, 1) NOT-NULL
- transmission: STRING CHAR(3) NULL
- gear: NUMBER TINYINT NOT-NULL
- fuel: STRING VARCHAR(10) NOT-NULL
- km: NUMBER MEDIUMINT UNSIGNED NOT-NULL
- PRICE: NUMBER MEDIUMINT UNSIGNED NOT-NULL
- year: YEAR NOT-NULL
- color: STRING VARCHAR(25) NOT-NULL
- interior-color: STRING VARCHAR(15) NULL
- interior-material: STRING VARCHAR(15) NULL
- seat: NUMBER TINYINT NULL
- doors-number: NUMBER TINYINT NOT-NULL
- past-owners: NUMBER TINYINT NULL
- optionals: STRING TEXT NULL
- note: STRING TEXT NULL
 

