# TABELLA AUTO USATE

- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## COMMENTI:

- VARCHAR : Ho utilizzato VARCHAR perché sto indicando la lunghezza massima della stringa.
- CHAR : Ho utilizzato CHAR perché sto indicando una lunghezza fissa della stringe (es. una targa italiana è formata da 7 caratteri).
- TEXT : Ho utilizzato TEXT per la descrizione della macchina usata perché è adatto per contenuti lunghi e variabili.
- NOT NULL : Ho utilizzato NOT NULL nei campi in cui è obbligatorio fornire il valore.
- NULL : Ho utilizzato NULL nei campi dove è facoltativo fornire un valore.
- DEFAULT: Ho utilizzato DEFAULT nel campo "disponibile" per assegnare un valore predefinito, ovvero che il valore non viene specificato all'inserimento.
- UNIQUE: Ho utilizzato UNIQUE nella targa della macchina perché è un valore non ripetuto.
