# mySmartHome — Database relazionale per una casa intelligente

Progetto di gruppo sviluppato per il corso di **Basi di dati, A.A. 2020–2021**, dedicato alla progettazione e implementazione in **MySQL** di un database per la gestione di una smart home.

Il progetto comprende modellazione concettuale, progettazione logica, analisi delle prestazioni e implementazione delle operazioni e delle funzionalità di analisi dei dati.

## Ambito del progetto

Il database gestisce informazioni relative a:

- utenti, account e struttura dell’abitazione;
- dispositivi, smart plug e registri di utilizzo;
- produzione e consumo di energia;
- climatizzazione e illuminazione;
- accessi, intrusioni e apertura dei serramenti.

## Implementazione

Gli script SQL comprendono:

- **44 tabelle** per rappresentare le diverse aree della smart home;
- vincoli di integrità e trigger per le regole applicative;
- ridondanze aggiornate tramite trigger;
- **9 operazioni** implementate mediante stored procedure;
- dati di popolamento ed esempi di chiamata delle procedure.

## Analisi dei dati

Sono presenti tre funzionalità principali:

1. **Regole associative** — analisi delle associazioni tra i punti luce attraverso itemset, supporto e confidenza.
2. **Gestione energetica** — suggerimenti di accensione e spegnimento basati sui dati di consumo e produzione.
3. **Comfort e riduzione degli sprechi** — suggerimenti per spegnere le luci nelle stanze vuote e aprire le finestre in presenza di livelli elevati di CO₂.

## Contenuto del repository

La cartella [Implementazione](Implementazione/) contiene gli script numerati dalla definizione dello schema alle tre funzionalità di analisi.

Il file [Test Chiamate Funzioni.sql](Implementazione/Test%20Chiamate%20Funzioni.sql) raccoglie esempi di invocazione delle procedure.

## Documentazione

- [Relazione di progetto](DOCUMENTAZIONE%20-%20DEVINE%20GRASSI%20MEINI%20-%202020_2021.pdf)
- [Diagramma E-R](ER%20-%20DEVINE%20GRASSI%20MEINI%20-%202020_2021.pdf)
- [Diagramma E-R ristrutturato](ER_RISTRUTTURATO%20-%20DEVINE%20GRASSI%20MEINI%20-%202020_2021.pdf)

## Autori

Progetto realizzato dal gruppo **Devine, Grassi e Meini**.
