<!-- Create un file di testo per descrivere un database di un negozio di videogiochi.
Strutturate il file come fatto oggi in classe.  Specificate: il nome del database, la tabella e le potenziali colonne con i tipi di dato. -->

# database name : GameFlop
# nome tabella : Games

- id BIGINT PRIMARYKEY NOTNULL AUTO_INCREMENT
- isbn string VARCHAR(10) NOTNULL UNIQUE
- title string VARCHAR(255) NOTNULL
- author string VARCHAR(22) NULL
- availability int TINYINT NULL DEFAULT(0)
- quantity int SMALLINT NULL DEFAULT(0)
- year release date YEAR NULL
- cover binary data BLOB NULL
- price int FLOAT(5,2)  NULL
- game_house string VARCHAR(21) NULL



- topic VARCHAR(30) NOTNULL
- language string VARCHAR(20) NOTNULL
- edition string VARCHAR(20) NULL

- size string VARCHAR (25) NULL
- editor string VARCHAR(25) NULL
- cover_material string VARCHAR(25) NULL
- created_at_date date DATETIME NOTNULL
- edited_in date DATETIME NULL
- description string TEXT(65535) NULL
- genre string VARCHAR(21) NOTNULL