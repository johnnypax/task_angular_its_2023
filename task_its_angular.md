# ESAME DI PROGRAMMAZIONE 

### NodeJS, Express, Angular e MongoDB 

##### Recupero - V1.0

#### Parte A: Sviluppo

Hai il compito di sviluppare un'applicazione web utilizzando NodeJS con Express per il backend, Angular per il frontend e MongoDB come database che gestisca l'informazione su film e registi.

**Requisiti del database:**

Collezione Registi:

- Nome
- Cognome
- DataDiNascita (tipo data)

Collezione Film:

- Titolo
- DataUscita (tipo data)

**Requisiti dell'applicazione:**

- Una pagina che permetta l'aggiunta di un nuovo regista.
- Una pagina che permetta l'aggiunta di un nuovo film e l'associazione di questo film a un regista esistente.
- Una pagina che elenchi tutti i registi e i film associati a ciascun regista.
- Gestione di errori (es. tentativo di cancellare un regista che ha film associati).

#### Parte B: Domande sulle Query

**Utilizzando MongoDB e il linguaggio di query di MongoDB, esegui le seguenti operazioni:**

1. Scrivi una query per selezionare tutti i registi che non hanno diretto nessun film.

```
db.registi.find({ ... })
```

1. Scrivi una query per trovare il film con la data di uscita più recente.

```
db.film.find({ ... })
```

1. Scrivi una query per contare quanti film ha diretto ciascun regista e ordina il risultato in ordine decrescente basato sul numero dei film. ``

```
db.film.aggregate([ ... ])
```

1. Scrivi una query per selezionare i registi che hanno diretto più di 3 film.

```
db.film.aggregate([ ... ])
```

1. Scrivi una query per aggiornare la DataUscita di un film specifico (ad es. ID_Film = 5) a una nuova data (ad es. '2023-09-28').

```
db.film.updateOne({ ... })
```

Nota: La sintassi delle query in MongoDB potrebbe variare leggermente in base alla versione e alle impostazioni specifiche del database.

**Come consegnare il compito:**

- Carica il progetto su GitHub e condividi la repository con "johnnypax" utente.

#### **DEADLINE:** 15/10/2023.