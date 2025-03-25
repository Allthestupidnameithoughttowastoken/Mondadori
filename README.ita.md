# Progetto: Estrazione Titoli e Autori - Mondadori

Questo programma effettua lo scraping della pagina Mondadori dedicata alle novità editoriali del 2024, estraendo titoli e autori di libri.

## Funzionalità principali

- Accesso al sito Mondadori tramite richiesta HTTP
- Analisi del contenuto HTML con BeautifulSoup
- Estrazione dei dati strutturati dai tag `<h3 class="box-title">`
- Creazione di un dizionario `titolo: autore`
- Esportazione in formato JSON

## Librerie utilizzate

- `requests`
- `bs4 (BeautifulSoup)`
- `json`

## Come eseguire il programma

1. Assicurati di avere Python installato (consigliata versione 3.8 o superiore)
2. Installa le dipendenze (se non presenti):

```bash
pip install requests beautifulsoup4

#NOTE
Il progetto è dimostrativo e potrebbe non funzionare se la struttura del sito web viene modificata.

I dati raccolti sono pubblici e utilizzati esclusivamente a scopo educativo.

Il programma è progettato per essere semplice e leggibile: eventuali estensioni possono includere salvataggio in CSV, filtri personalizzati o gestione di più pagine.

L'obiettivo principale è mostrare capacità tecniche su web scraping, manipolazione di stringhe e dizionari in Python.
