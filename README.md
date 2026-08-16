# Fototeca — canale di distribuzione

Qui non c'è codice: questo repository serve solo a **distribuire gli
aggiornamenti** dell'app Android Fototeca, che non passa dal Play Store.

- `latest.json` — l'app lo controlla all'apertura per sapere se c'è una
  versione più recente.
- **Releases** — gli APK firmati, allegati a ogni versione.

## Scaricare l'ultima versione

https://github.com/alyonhd-lgtm/fototeca-releases/releases/latest

## Sicurezza

Ogni APK dichiara la propria impronta SHA-256 dentro `latest.json`. L'app
verifica il file scaricato e annulla l'installazione se non corrisponde.
Android accetta inoltre solo aggiornamenti firmati con la stessa chiave
dell'app già installata.
