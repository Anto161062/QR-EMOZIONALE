MYSENZA – QR EMOZIONALE (FRONTE & RETRO)

STRUTTURA REPO (consigliata):
/
├─ qr/
│  ├─ citri_front.html
│  ├─ citri_back.html
│  └─ (altri prodotti front/back)
└─ README.md

1) CREA/AGGIORNA LA REPO SU GITHUB
- Nome suggerito: mysenzqrs (o come preferisci).
- Carica i file HTML nella cartella /qr.
- Vai su Settings → Pages → Source: "Deploy from a branch".
- Branch: main; Folder: /root o /docs (se usi /docs, metti i file lì).
- Attiva GitHub Pages: l’URL sarà qualcosa come
  https://<utente>.github.io/<repo>/qr/citri_front.html

2) QR FRONTALE (EMOZIONE + CARRELLO)
- File: qr/citri_front.html
- Punta allo shop: https://anto161062.github.io/mysenza-shop-/
- Stampa il QR di questa pagina in etichetta frontale (con cornice oro).

3) QR POSTERIORE (OFFERTA “PER TE” + WHATSAPP)
- File: qr/citri_back.html
- Modifica nel campo in pagina la scadenza (es. "5 agosto 2025, ore 12:00") e premi "Aggiorna QR".
- Il QR generato porta a WhatsApp +39 393717771328 con messaggio precompilato e la scadenza dentro il testo.

4) DUPLICARE PER ALTRI PROFUMI
- Duplica i due file e rinominali (es. vanilime_front.html, vanilime_back.html).
- Nel front, cambia titolo.
- Nel back, cambia il prodotto nella funzione buildText(...) (es. "VaniLime").

NOTE TECNICHE
- Il QR è generato lato client tramite api.qrserver.com (nessun server).
- Se vuoi un’immagine statica PNG, apri la pagina, click destro sull’immagine del QR → "Salva immagine".
- Su stampa, mantieni almeno 2 cm di lato per una scansione affidabile.
