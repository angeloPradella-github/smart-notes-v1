# App per la gestione delle note con React, TypeScript e Markdown

Questo progetto è una Note Taking App avanzata che utilizza React e TypeScript. L'app supporta il Markdown e permette di organizzare e ricercare le note in categorie tramite l'utilizzo di tags e titoli.

## Caratteristiche principali

- Creazione e gestione di note in formato Markdown
- Organizzazione delle note utilizzando tags
- Creazione di nuovi tags al volo durante la selezione
- Visualizzazione del Markdown formattato in tempo reale

## Tecnologie utilizzate

- React.js: libreria JavaScript per la creazione di interfacce utente
- TypeScript: linguaggio di programmazione basato su JavaScript che introduce il sistema di tipi statici
- react-select: libreria per la creazione di select personalizzate e avanzate
- react-markdown: libreria per la conversione del Markdown in elementi React

## Come iniziare

Per iniziare a utilizzare questa app per la gestione delle note, segui questi passaggi:

1. Clona la repository:

```bash
git clone https://github.com/angeloPradella-github/note-taking-app.git
```

2. Installa le dipendenze:

```bash
cd note-taking-app
npm install
```

3. Avvia l'app in locale:

```bash
npm run dev
```

L'app dovrebbe ora essere in esecuzione all'indirizzo [http://localhost:3000](http://localhost:3000) nel tuo browser.

## Librerie aggiuntive

### CreatableReactSelect

Questa app utilizza il componente `CreatableReactSelect` dalla libreria `react-select` per creare una select avanzata con la funzionalità di creazione di nuovi tags al volo. Inoltre, il componente permette di selezionare più tags per organizzare le note.

### React Markdown

La libreria `react-markdown` è utilizzata per convertire il testo in formato Markdown delle note in elementi React, permettendo la visualizzazione del testo formattato direttamente nell'app.
