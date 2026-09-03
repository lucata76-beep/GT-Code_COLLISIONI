# Piazzamenti e Controllo Collisioni — Mikron Mill P 900

Web app monofile (HTML+CSS+JS, nessuna dipendenza) per la pre-verifica geometrica di
piazzamenti su tavola: piano magnetico, morsa, origini G54–G59, pezzi, controllo statico
di collisioni/margini/superamento corse.

**Versione:** v0.4.0 — statico + dinamico (utensile, portautensile, mandrino) + viste XZ/YZ + origini attrezzatura.

## ⚠️ Avviso

Strumento di **pre-verifica geometrica**. Non è un simulatore CNC certificato e non
sostituisce simulazione CAM, simulazione del controllo, Single Block, Dry Run, prova con
avanzamento ridotto, procedure di sicurezza macchina. Vedi il menu **AIUTO** nell'app per
l'elenco completo di cosa è e non è ancora coperto in questa versione (in particolare:
nessun controllo dinamico utensile/percorso).

## Uso

- **Online:** apri `index.html` pubblicato con GitHub Pages (link nelle impostazioni del
  repository, sezione *Pages*), aggiungibile alla schermata Home su iPhone.
- **Offline/locale:** scarica `index.html` e aprilo con doppio clic — funziona anche senza
  connessione, i dati restano salvati solo nel browser usato (localStorage).
- Nessun dato viene inviato altrove: tutto il calcolo e il salvataggio avvengono nel
  browser dell'utente.

## Struttura del repository

- `index.html` — l'intera applicazione.
- `README.md` — questo file.
