# Radicali

Web app didattica e interattiva sui **radicali**: dalle radici n-esime e le loro condizioni di
esistenza fino alle potenze a esponente razionale e alle prime equazioni irrazionali.

La pagina (`index.html`) con la libreria **KaTeX** inclusa nel repo (cartella `katex/`) per la resa
delle formule: basta aprirla nel browser, funziona anche offline e da mobile, senza dipendenze da
CDN esterni. Tema chiaro e scuro.

Riprende lo stile e l'impostazione delle app della stessa serie
([equazioni-disequazioni-sistemi](https://ventilii-gif.github.io/equazioni-disequazioni-sistemi/),
[derivate](https://ventilii-gif.github.io/derivate/)).

## Struttura

Ogni capitolo è organizzato in quattro momenti:

- **Teoria** — definizioni, formule ed esempi in schede richiudibili.
- **Simulazione** — una visualizzazione interattiva da esplorare muovendo i cursori, con la
  conferma numerica del risultato.
- **Esercizi guidati** — esercizi svolti passo per passo, con i passaggi rivelati uno alla volta.
- **Quiz** — domande a risposta chiusa, una per volta, con correzione, spiegazione e punteggio.

## Capitoli

1. **Radici ed esistenza** — radice n-esima, indice e radicando, condizioni di esistenza (indice
   pari/dispari), `√(a²) = |a|` e significato geometrico. Simulazione: il grafico di `y = ⁿ√x`, la
   zona in cui la radice esiste e il valore del punto scelto.
2. **Proprietà e semplificazione** — proprietà invariantiva, semplificazione, riduzione allo stesso
   indice e confronto. Simulazione: due radicali ridotti al m.c.m. degli indici e confrontati.
3. **Operazioni con i radicali** — prodotto e quoziente, trasporto dentro e fuori dal segno di
   radice, potenza e radice di un radicale, somma di radicali simili. Simulazione: un laboratorio
   che svolge l'operazione scelta con i passaggi e il controllo numerico.
4. **Razionalizzazione del denominatore** — caso monomio, radice n-esima e uso del coniugio.
   Simulazione: la razionalizzazione passo per passo, con verifica che il valore non cambia.
5. **Esponenti razionali ed espressioni irrazionali** — potenze a esponente frazionario, proprietà
   estese ai razionali e cenni sulle equazioni irrazionali. Simulazione: `aᵐ⁄ⁿ = ⁿ√(aᵐ)` sul grafico
   e la risoluzione di `√x = c`.

## Accessibilità

- Nessuna coppia di colori rosso/verde per corretto/errato (scelta accessibile ai daltonici): si
  usano blu, arancione e viola, con i simboli `✓` / `✕` come indicazione ridondante.
- Tema chiaro e scuro con selettore e rispetto delle preferenze di sistema; i grafici si adattano al
  tema.
- Interfaccia utilizzabile da tastiera con focus visibile e leggibile anche da mobile.

## Utilizzo

- In locale: aprire `index.html` con un qualsiasi browser moderno.
- Online: attivabile con GitHub Pages (Settings → Pages → branch di pubblicazione); l'app sarà
  raggiungibile all'indirizzo `https://ventilii-gif.github.io/radicali/`.

I valori mostrati nelle simulazioni (radici, semplificazioni, confronti, razionalizzazioni) sono
calcolati e verificati numericamente, non sono approssimazioni di comodo.
