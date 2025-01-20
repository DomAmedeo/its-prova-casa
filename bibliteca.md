# Doc. req sistema di gestione biblioteca 

## Stakeholders


- biblioteca di vasto è il cliente e per questo è un ente integrato nel progetto 
- biblioteca vacri s.r.l.
## requisiti funzinali 
1. il cliente deve poter effettuare il login inserendo i seguenti dati:
- Username 
- Password

2. Il cliente deve poter effettuare ricerche nel catalogo dei libri secondo questi criteri: 
- titolo libro 
- nome autore
- genere libro
- anno di pubblicazione libro
- codice identificativo libro 
- disponibilità del libro

3. il cliente deve poter:
- visualizzare stato disponibile del libro 
- ricevere notica scadenza prestito 
- prenotare libro
- restituire il libro tramite portale 
- creare una lista dei desideri con libri che vorrebbe prendere in futuro
- in caso di smarrimento o danno di un libro, gli utenti dovranno poter comunicare la problematica direttamente al sistema, che genererà una notifica per il bibliotecario

## La biblioteca deve poter:

- aggiungere nuovi libri 
- modificare i dettagli dei libri 
- rimuovere dettagli obsoleti 
- visualizzare report statistici sull'andamento di: 
1. prestiti 
2. preferenze utenti 
3. utilizzo complessivo della biblioteca, su base settimanale e mensile 

## Il sistema:
- deve essere accessibile anche tramite dispositivi mobili, con un'interfaccia che si adatti automaticamente alla dimensione dello schermo.
- può essere interessante aggiungere una funzionalità di suggerimento dei libri, basata sulle preferenze lette dagli utenti o sulle loro scelte precedenti. Sebbene questo non sia richiesto per la prima versione del sistema, sarebbe una funzionalità ben gradita in futuro.
- il sistema deve supportare almeno 500 utenti simultanei
- il design del portale dovrà essere semplice ma moderno, seguendo le linee guida WCAG per garantire che sia utilizzabile anche da persone con disabilità.

## requisiti non funzionali 

- il sistema deve essere sicuro 
- deve rispettare le normative della privacy degli utenti 
- Inoltre, si prevede che il sistema debba garantire una performance ottimale, con tempi di risposta inferiori a 2 secondi per qualsiasi operazione.
- È inoltre importante che venga implementato un sistema di backup giornaliero per prevenire la perdita di dati, e che le informazioni degli utenti siano criptate durante il trattamento