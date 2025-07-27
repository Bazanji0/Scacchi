# Scacchiera Interattiva in HTML, CSS e JavaScript

Questo è un progettino completo per giocare a scacchi direttamente nel browser. È tutto scritto in HTML, CSS e JavaScript puro, senza librerie esterne, e funziona sia su PC che su mobile.

## 🔥 Cosa fa
- Scacchiera visiva 8x8, con coordinate e colori classici.
- Tutti i pezzi si muovono come devono: re, regina, torre, cavallo, alfiere, pedone.
- Riconosce le mosse valide e blocca quelle sbagliate.
- Permette di mangiare i pezzi nemici.
- Mostra i pezzi catturati.
- Evidenzia lo scacco al re.
- Segna il turno (bianco o nero).
- Pulsante per iniziare una nuova partita.

## 🎮 Come funziona
1. Ogni pezzo ha il suo simbolo Unicode (♔, ♕, ♖, ecc.).
2. Quando clicchi su un pezzo, si evidenzia.
3. Poi clicchi su una casella valida e il pezzo si muove.
4. Se la mossa non è valida, semplicemente non succede nulla.

## 🛠️ Com'è fatto
- Il CSS crea l'estetica (colori, dimensioni, font, stile scacchiera, evidenziazione...).
- L'HTML ha una `div.scacchiera` che viene riempita dinamicamente dal JavaScript.
- Il JavaScript:
  - Inizializza la scacchiera con i pezzi nella posizione giusta.
  - Gestisce clic, selezioni, mosse, catture e controlla lo scacco.
  - Tiene conto del turno e aggiorna il display.

## 🧠 Come capire il codice
- `inizializzaScacchiera()` imposta la scacchiera all'avvio.
- `gestisciClick(riga, col)` gestisce tutto quando clicchi.
- `mossaValida(...)` decide se la mossa che vuoi fare è legale.
- Ogni pezzo ha la sua funzione: `mossaValidaTorre`, `mossaValidaCavallo`, ecc.
- `controllaScacco()` cerca se uno dei re è sotto scacco.
- `controllaFinePartita()` controlla se uno dei re è stato mangiato.


## 📦 Come usarlo
1. Salva il file con estensione `.html`
2. Aprilo con Chrome, Firefox o un qualsiasi browser moderno
3. Gioca da solo o con un amico passandovi il mouse

Buon divertimento ✌️
