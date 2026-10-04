# ESTIMO LAB

App web didattica modulare per lo studio dell'estimo.

## Contenuto attuale
- Capitolo 1: I principi dell'estimo
- 8 moduli di studio
- 30 quiz a risposta multipla
- 10 vero/falso
- 6 casi "Quale criterio?"
- verifica finale
- calcolatori per comparazione, capitalizzazione, trasformazione e complementare
- progressi salvati sul dispositivo
- struttura pronta per aggiungere capitoli futuri

## Avvio rapido
Per una prova locale semplice, apri `index.html` nel browser.
Per l'installazione come PWA e l'uso offline completo è meglio pubblicarla su HTTPS
(GitHub Pages, Netlify, Vercel o un hosting scolastico).

## Come aggiungere un nuovo capitolo
1. Copia `data/chapter1.js` e rinominalo, per esempio `chapter2.js`.
2. Cambia `id`, titolo, lezioni, quiz, vero/falso, casi e riepilogo.
3. Aggiungi in `index.html`, prima di `app.js`:
   `<script src="data/chapter2.js"></script>`
4. Il nuovo capitolo comparirà automaticamente nella barra "Capitoli".

## Nota didattica
Il Capitolo 1 è stato costruito sulla dispensa fornita dal docente.
Gli esercizi di calcolo riprendono le formule e gli esempi presenti nella dispensa.
