# Regole del progetto

Questo repository contiene un piccolo sito statico pubblicato con GitHub Pages.
Il proprietario del progetto **non è un programmatore**: queste regole vanno
rispettate sempre, in ogni risposta e in ogni modifica.

## 1. Sito statico, senza complicazioni
- Solo **HTML, CSS e JavaScript** scritti a mano.
- **Nessuna libreria esterna** (niente Bootstrap, jQuery, React, font o CDN esterni).
- **Nessun passaggio di build**: i file che stanno nel repository sono
  esattamente quelli che il browser carica.

## 2. Struttura dei file
- `index.html` sta nella **cartella principale** del repository.
- Si usano **solo percorsi relativi** (per esempio `css/stile.css`,
  `contenuti/testi.txt`), mai percorsi che iniziano con `/` e mai indirizzi
  completi verso altri siti. Questo serve perché GitHub Pages pubblica il sito
  dentro una sottocartella.

## 3. Contenuti separati dal codice
- I testi del sito stanno in **file di testo semplici** (per esempio dentro la
  cartella `contenuti/`), separati dal codice HTML/CSS/JS.
- Questi file devono poter essere modificati **da una persona che non sa
  programmare**: formato chiaro, righe leggibili, commenti in italiano che
  spiegano cosa fa ogni parte.
- Cambiare un testo non deve mai richiedere di toccare il codice.

## 4. Commit
- Commit **piccoli e frequenti**: una modifica logica per commit.
- Messaggi **in italiano**, che spiegano **cosa è cambiato** e perché, in parole
  semplici (esempio: "Aggiunta la pagina dei contatti con l'indirizzo della scuola").

## 5. Git sì, gh no
- Si usa **solo `git` da riga di comando**.
- **Mai la GitHub CLI (`gh`)**: non è installata su questo computer.
- **Prima di ogni `git push` va chiesta conferma** al proprietario del progetto.

## 6. Come spiegare le cose
- Spiegare ogni operazione **con parole semplici**, senza dare per scontato il
  gergo tecnico.
- Quando si usa un termine tecnico, spiegarlo brevemente la prima volta.

## 7. Privacy
- Il repository è **pubblico**: tutto quello che viene caricato è visibile a
  chiunque su internet.
- **Mai dati personali reali di studenti** (nomi, cognomi, foto, email, voti,
  classi riconoscibili). Se servono esempi, usare nomi di fantasia.
