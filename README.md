# Sito web Didelphis

Sito statico (HTML + CSS, nessuna dipendenza) pronto per GitHub Pages.

## File
- `index.html` – home page
- `privacy.html` – informativa privacy (da completare)
- `cookie.html` – cookie policy (da far verificare)
- `assets/logo-didelphis.png` – logo

## Pubblicazione su GitHub Pages
1. Crea un nuovo repository su GitHub (es. `didelphis-sito`).
2. Carica tutti i file mantenendo la cartella `assets`.
3. Vai in **Settings → Pages**, alla voce *Source* scegli **Deploy from a branch**, branch `main`, cartella `/ (root)`, poi **Save**.
4. Dopo un paio di minuti il sito è online su `https://<utente>.github.io/didelphis-sito/`.

Per usare un dominio vostro (es. `www.didelphis.it`) inseriscilo in **Settings → Pages → Custom domain** e configura il DNS come indicato da GitHub.

## Da completare
- P.IVA (in attivazione): aggiungerla nel footer di `index.html` e nel paragrafo "Titolare del trattamento" di `privacy.html` appena attribuita
- Testo della privacy policy (farlo verificare)

## Modulo di contatto
Il modulo invia le richieste direttamente a Formspree (endpoint https://formspree.io/f/mkjjlrje), con verifica Google reCAPTCHA sulla pagina di Formspree; le richieste vengono inoltrate a amministrazione@didelphis.it. Il CAPTCHA va lasciato attivo nelle impostazioni del form su Formspree. Le richieste sono visibili anche nella dashboard di Formspree.
