# @Nos — chat documentale (profilo pubblico)

Pagina pubblica: **https://ecology-of-information-systems.github.io/-Nos/**

Questa repository ospita una **pagina singola** (`index.html`) che permette di interrogare i
documenti pubblici del progetto **@Nos — Assistente Personale Solidale**.

## Cos'è

Una ricerca documentale: si scrive una domanda e la pagina risponde **con passaggi tratti alla
lettera** dai documenti pubblici del progetto, indicando la fonte. Non è un modello linguistico:
nessuna generazione di testo, nessuna interpretazione. Solo i documenti, e il rimando a dove la
frase si trova.

## Come è fatta

- **un solo file** `index.html`: nessuna build, nessun backend, nessuna dipendenza esterna;
- le regole di ricerca e l'indice dei documenti stanno **dentro la pagina**;
- i documenti ammessi sono scelti **a monte, per elenco fisico**: la pagina non può leggere nulla
  che non sia in quell'elenco.

## Cosa non fa

- non invia le domande a nessun server: tutto avviene nel browser;
- non raccoglie dati — nessun analytics, nessun cookie di tracciamento, nessuna richiesta verso
  l'esterno;
- non inventa: se il documento non c'è, dice che non c'è.

## Aggiornare la pagina

GitHub Pages, ramo `main`, radice. Per aggiornare basta sostituire `index.html`.

---

*@Nos — Assistente Personale Solidale.*
