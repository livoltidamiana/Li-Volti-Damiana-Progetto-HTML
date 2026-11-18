# Progetto di introduzione alla linguistica computazionale

Sito web che documenta un progetto in Python realizzato per il corso di Introduzione alla linguistica computazionale e laboratorio (2025).

Il progetto analizza il primo capitolo della mia tesi triennale. Il testo viene letto da file, ripulito dalla punteggiatura, suddiviso in frasi e token e lemmatizzato. Poi si generano gli embedding di lemmi e frasi con il modello `distiluse-base-multilingual-cased-v1`, che servono a trovare parole semanticamente simili a un termine dato, frasi che contengono parole affini e frasi simili a una frase data. Alla fine queste funzioni sono raccolte in un piccolo chatbot.

Per ogni fase il sito mostra il codice usato e, dove c'è, un metodo alternativo per ottenere lo stesso risultato.

## Come vedere il sito

Apri `index.html` nel browser, oppure visita la versione online pubblicata con GitHub Pages.

## Struttura

- `index.html`: pagina iniziale con la descrizione del progetto
- `fasi.htm`: elenco delle dieci fasi, ognuna con la sua pagina
- `obiettivo.htm` e `risultato.htm`: obiettivo del progetto e video del programma in esecuzione

Progetto realizzato da Damiana Li Volti.
