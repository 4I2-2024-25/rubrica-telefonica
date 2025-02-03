# Esercizio - Rubrica Telefonica
## Obiettivo
Realizzare un'applicazione Java che permetta di gestire una rubrica telefonica attraverso un file di testo chiamato _agenda.txt_.
Il programma deve consentire di cercare un numero di telefono o aggiungere nuovi contatti alla rubrica.

## Funzionalità richieste
### Cerca un numero di telefono:
- L'utente inserisce un nome.
- Il sistema legge il file _agenda.txt_, cerca il nome e, se lo trova, restituisce il numero di telefono associato.
- Se il nome non è presente, il programma deve visualizzare il messaggio: _"Nessun contatto trovato con questo nome!"_.
### Aggiungi un nuovo contatto:
- L'utente inserisce un nome e un numero di telefono.
- Il sistema aggiunge il nuovo contatto al file agenda.txt, rispettando il formato: nome;numero.
### Esci dal programma:
- Termina l'esecuzione del programma.

## Vincoli
Utilizzare le seguenti classi e metodi:
- FileReader, BufferedReader per leggere dal file.
- FileWriter, BufferedWriter per scrivere nel file.
- StringTokenizer o il metodo split() per dividere le righe del file in nome e numero.

## Esempio di file di testo _agenda.txt_
```
Mario;02672727
Bianca;068382928
Francesca;33877778899
Valerio;33911112222
```
