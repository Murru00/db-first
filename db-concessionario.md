# TABELLA CONCESSIONARIO


Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


| FIELD            | TYPE           | ATTRIBUTES             |
| --               |:---:           |---:                    |
| id               |INT             |AUTO_INCREMENTO UNIQUE  |
| marca            |VARCHAR(20)     |NOT NULL                |
| modello          |VARCHAR(20)     |NOT NULL                |
| immatricolazione |YEAR            |NOT NULL                |
| km               |MEDIUMINT       |NOT NULL, UNSIGNED      |
| posti            |TINYINT         |NULL, UNSIGNED          |
| porte            |TINYINT         |NOT NULL, UNSIGNED      |
| alimentazione    |VARCHAR(10)     |NULL                    |
| targa            |CHAR(7)         |NOT NULL                |
| cilindrata       |MEDIUMINT       |NOT NULL, UNSIGNED      |
| cavalli          |SMALLINT        |NULL, UNSIGNED          |
| telaio           |CHAR(17)        |NOT NULL                |
|ruota di scorta   |TINYINT         |NULL                    |
| condizioni       |TEXT            |NULL                    |
| prezzo           |DOUBLE(12,2)    |NOT NULL, UNSIGNED      |
| colore           |VARCHAR(20)     |NULL                    |
