# Generatore di Codice Fiscale

## Descrizione

Sviluppare un programma in python che genera il codice fiscale di una persona
a partire dai seguenti dati in input:

- nome
- cognome
- data di nascita
- comune di nascita
- sesso

Il codice è suddiviso in classi:

- la classe StringaDiTesto gestisce nome e cognome
- la classe DataDiNascita gestisce la data di nascita
- la classe ComuneDiNascita gestisce il comune di nascita

La classe StringaDiTesto dovrà gestire
- la separazione tra vocali e consonanti
- la generazione della stringa di tre lettere relativa al nome
- la generazione della stringa di tre lettere relativa al cognome

La classe DataDiNascita dovrà gestire
- la separazione della stringa inserita in input in giorno, mese e anno
- la generazione del numero a 2 cifre che identifica l'anno di nascita
- la conversione del mese di nascita in lettera dell'alfabeto
- il calcolo del giorno di nascita in base al sesso

La classe ComuneDiNascita dovrà gestire
- la generazione del codice catastale in base alla corrispondenza inserita
in un dizionario ("comune" : "codice catastale")

Terminata la prima parte dell'esercizio, sarà possibile usare la stringa
fin qui generata per calcolare il carattere di controllo, la cui logica
dovrebbe essere inserita in una ulteriore classe CarattereDiControllo

## Funzionalità

* Generazione automatica del codice fiscale

* Verifica di un codice fiscale esistente

* Supporto per caratteri speciali nei nomi e nei cognomi

* Gestione delle omocodie

## Contributi

Sono benvenuti contributi per migliorare il progetto! Puoi aprire una issue o inviare una pull request.
