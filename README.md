# ACRON Technologies — NEXUS Drive v0.9

Versione Web/PWA di **ACRON NEXUS Drive**, realizzata per iPhone e Dell Ubuntu.

## Funzioni
Navigazione e destinazioni preferite, accesso a ChatGPT/Claude/Grok, musica, parcheggio, diario viaggi e note auto inserite manualmente. Grafica ACRON blu/arancione.

## Pubblicazione su GitHub Pages
Una sola configurazione iniziale: **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.

Indirizzo previsto: https://alessandro111193.github.io/acron-nexus-drive/

## Struttura
- `index.html`: caricatore Web che ricompone l'app originale v0.9.
- `p0.txt`–`p3.txt`: versione v0.9 compressa; il caricatore la ricostruisce senza modificarne interfaccia e logica.
- `manifest.webmanifest`, `icon.svg` e `sw.js`: installabilità PWA e utilizzo offline.

## Sicurezza e limiti
L'app non modifica il software Peugeot, non accede alle centraline e non legge dati motore reali. Il mirroring tramite CAR# sulla Peugeot RCC non è ancora confermato: eseguire eventuali prove esclusivamente a vettura parcheggiata. Non inserire dati sensibili: il repository è pubblico. Le note dell'app vengono memorizzate localmente sul dispositivo.

Per ulteriori modifiche mantenere i sorgenti originali in `ACRON_NEXUS_Drive_v0.9_GitHub_Pages.zip`, usato come riferimento per questa pubblicazione.
