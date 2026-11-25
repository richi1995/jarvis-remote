# J.A.R.V.I.S. — Pannello remoto

## Pubblicazione con GitHub Pages
1. Crea un repository pubblico chiamato `jarvis-remote`.
2. Carica `index.html`, `manifest.webmanifest` e `sw.js` nella radice.
3. In Settings → Pages, scegli Deploy from a branch, branch `main`, folder `/ (root)` e salva.
4. Attendi la pubblicazione e apri l'URL GitHub Pages su iPhone.
5. In Safari: Condividi → Aggiungi alla schermata Home.

## Collegamento al Comando Rapido
Il pulsante apre il Comando Rapido Apple chiamato esattamente `ATTIVA JARVIS REMOTO`.
Il comando deve essere già installato sullo stesso iPhone e configurato in modo sicuro.

## Limiti importanti
Questa pagina è solo l'interfaccia grafica: non esegue SSH e non installa Tailscale da sola. Il pulsante richiama il Comando Rapido. Prima di condividerlo, verifica che il comando funzioni dalla rete domestica e che non esponga password o credenziali. Non inserire segreti nel repository GitHub.
