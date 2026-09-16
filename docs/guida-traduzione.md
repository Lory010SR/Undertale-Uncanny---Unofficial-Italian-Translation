# Guida alla traduzione

## Flusso di lavoro

1. Il file sorgente è `en.json`.
2. Le traduzioni vengono effettuate e revisionate su Crowdin.
3. Crowdin esporta la lingua italiana in `it.json`.
4. Prima di usare il file nel gioco, verificare che JSON, placeholder e codici di formattazione siano validi.

## Regole essenziali

- Tradurre solo il testo visibile al giocatore.
- Non modificare identificatori, nomi tecnici o struttura del file.
- Conservare placeholder come `{0}`, `{1}` e simili.
- Conservare tag, codici colore, sequenze `\\n` e caratteri speciali.
- Controllare la lunghezza delle battute nei dialoghi.
- Segnalare i dubbi usando commenti o discussioni su Crowdin.
