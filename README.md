# Used Car Dealer Db Example
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table Name: (cars)

- id: NUMBER INT PRIMARY_KEY AI UNIQUE 
- type: STRING VARCHAR(13) NULL
- name: STRING VARCHAR(50) NOT-NULL INDEX
- brand: STRING VARCHAR(50) NOT-NULL
- motor-CC: NUMBER FLOAT(2, 1) NULL
- transmission: STRING CHAR(3) NULL
- gear: NUMBER TINYINT NULL
- fuel: STRING VARCHAR(10) NULL
- km: NUMBER FLOAT(8,2) UNSIGNED NULL
- PRICE: NUMBER MEDIUMINT UNSIGNED NULL
- year: YEAR NULL
- color: STRING VARCHAR(25) NULL
- interior-color: STRING VARCHAR(15) NULL
- interior-material: STRING VARCHAR(15) NULL
- seat: NUMBER TINYINT NULL
- doors-number: NUMBER TINYINT NULL
- past-owners: NUMBER TINYINT NULL
- optionals: STRING TEXT NULL
- note: STRING TEXT NULL
- is_available: NUMBER TINYINT NULL
- vin: char(17) UNIQUE NULL
 

