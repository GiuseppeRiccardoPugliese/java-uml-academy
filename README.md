# java-uml-academy
Sviluppare una dashboard di gestione dei dati del personale dei corsi di una Academy tech.
Gli analisti funzionali ci hanno consegnato i seguenti 3 casi d’uso che rappresentano i requisiti funzionali di questa applicazione:

Disegnare il Domani Model (diagramma delle classi) dell’applicazione utilizzando lo strumento che preferite (diagrams o altre applicazioni) e consegnate su GitHub il file con l’immagine del diagramma.

UC1: Inserimento di un nuovo studente - Attore primario: Utente Amministratore

L’Utente seleziona l’attività “Inserisci nuovo studente”

L’Utente inserisce nome, cognome, sesso, numero di telefono e titolo di studio dello studente

L’Utente inserisce l’indirizzo dello studente, composto da città, provincia, cap, via e numero civico

L’Utente richiede la lista di tutti i corsi non conclusi

Il Sistema mostra il codice, il nome, la data inizio e la data fine di ciascun corso

L’Utente seleziona il codice del corso che frequenta lo studente

Il Sistema registra il nuovo studente

UC2: Visualizzazione dati singolo corso - Attore primario: Utente Amministratore

L’Utente seleziona l’attività “Statistiche”

Il Sistema mostra la lista di tutti i corsi

L’Utente seleziona il codice di un corso

Viene mostrato uno ScatterPlot con sesso, età e media dei voti di tutti gli studenti

UC3: Export dati insegnanti - Attore primario: Utente Amministratore

L’Utente seleziona l’attività “Export Insegnanti”

Il Sistema genera un file JSON contenente i seguenti dati per ogni insegnante: nome, cognome, sesso, data inizio collaborazione, materie insegnate
