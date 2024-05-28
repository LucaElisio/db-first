# Tabella per Auto Usate


| Campo             | Tipo di Dato                                                                 | NOT NULL |
|-------------------|------------------------------------------------------------------------------|----------|
| id                | INT AUTO_INCREMENT PRIMARY KEY UNIQUE                                              | Sì       |
| marca             | VARCHAR(30)                                                                  | Sì       |
| modello           | VARCHAR(50)                                                                  | Sì       |
| anno              | YEAR                                                                         | Sì       |
| chilometraggio    | INT                                                                          | Sì       |
| carburante        | ENUM('Benzina', 'Diesel', 'GPL', 'Metano', 'Elettrico', 'Ibrido')            | Sì       |
| cambio            | ENUM('Manuale', 'Automatico')                                                | Sì       |
| colore            | VARCHAR(30)                                                                  | Sì       |
| prezzo            | DECIMAL(10, 2)                                                               | Sì       |
| data_inserimento  | DATE                                                                         | No       |
| descrizione       | TEXT                                                                         | No       |



- ENUM è un tipo di dato che consente di definire un elenco di valori possibili per un campo.
