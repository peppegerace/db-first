 db-first
===

## cars
| id                     | INT          | NOT_NULL    | AUTO_INCREMENT | PRIMARY_KEY |
| casa_automobilistica   | VARCHAR(50)  | NOT_NULL    |                | 
| modello                | VARCHAR(50)  | NOT_NULL    |                | 
| versione               | VARCHAR(50)  | NOT_NULL    |                | 
| anno                   | YEAR         | NOT_NULL    |                | 
| anno_immatricolazione  | DATE         | NOT_NULL    |                | 
| classe_veicolo         | VARCHAR(20)  | NULL        |                | 
| chilometri             | FLOAT(8, 2)  | NOT_NULL    |                | 
| prezzo                 | FLOAT(8, 2)  | NOT_NULL    |                | 
| carburante             | VARCHAR(20)  | NOT_NULL    |                | 
| cambio                 | VARCHAR(20)  | NOT_NULL    |                | 
| potenza_cv             | SMALLINT     | NOT_NULL    |                | 
| cilindrata             | SMALLINT     | NOT_NULL    |                | 
| trazione               | VARCHAR(12)  | NULL        |                | 
| consumi                | VARCHAR(50)  | NULL        |                | 
| classe_emissioni       | VARCHAR(50)  | NOT_NULL    |                | 
| emissioni              | VARCHAR(20)  | NULL        |                | 
| paese_d_origine        | VARCHAR(50)  | NOT_NULL    |                | 
| motore_originale       | CHAR(2)      | NOT_NULL    |                | 
| proprietari_precedenti | TINYINT      | NULL        |                | 
| portiere               | TINYINT      | NOT_NULL    |                | 
| colore_auto            | VARCHAR(50)  | NOT_NULL    |                | 
| colore_interni         | VARCHAR(50)  | NULL        |                | 
| numero_chiavi          | TINYINT      | NULL        |                | 
| numero_telaio          | CHAR(17)     | NOT_NULL    | UNIQUE         | 
| targa                  | VARCHAR(12)  | NOT_NULL    | UNIQUE         | 
| autocarro              | CHAR(2)      | NULL        |                | 
| auto_incidentata       | CHAR(2)      | NOT_NULL    |                | 
| ultima_manutenzione    | DATE         | NULL        |                | 
| airbag                 | VARCHAR(50)  | NULL        |                | 
| climatizzatore         | CHAR(2)      | NULL        |                | 
| sedili riscaldabili    | CHAR(2)      | NULL        |                | 
| sensori_parcheggio     | CHAR(2)      | NULL        |                | 
| tetto_panoramico       | CHAR(2)      | NULL        |                | 
| autoradio              | CHAR(2)      | NULL        |                | 
| bluetooth              | CHAR(2)      | NULL        |                | 
| comandi_al_volante     | CHAR(2)      | NULL        |                | 
| boardcomputer          | CHAR(2)      | NULL        |                | 
| navigatore             | CHAR(2)      | NULL        |                | 
| tipo_di_fari           | CHAR(7)      | NULL        |                | 





