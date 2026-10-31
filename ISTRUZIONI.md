# Archivio Documenti – come ottenere l'app Android (APK)

Questo pacchetto contiene l'archivio già pronto. Serve solo trasformarlo in APK.
Non l'ho potuto compilare io: il procedimento qui sotto è preparato ma va provato.

## Metodo consigliato: GitHub (gratis, senza installare nulla)
1. Crea un account gratuito su https://github.com
2. Crea un nuovo "repository" privato (pulsante "New"), chiamalo `archivio-documenti`.
3. Carica TUTTO il contenuto di questa cartella (compresa la cartella nascosta `.github`).
   Sul computer: "Add file" > "Upload files" e trascina i file.
   Attenzione: la cartella `.github/workflows/apk.yml` deve essere caricata, altrimenti non parte nulla.
4. Vai nella scheda **Actions**. Se chiede di abilitare i workflow, conferma.
5. Seleziona "Crea APK" e premi **Run workflow**. Aspetta 5-10 minuti (pallino verde = finito).
6. Apri l'esecuzione finita e in fondo, sotto **Artifacts**, scarica `archivio-documenti-apk`.
   Dentro lo zip c'è `app-debug.apk`.

## Installazione sul telefono
1. Copia `app-debug.apk` sul telefono.
2. Toccalo: Android chiede di consentire l'installazione da questa fonte. Consenti.
3. Apri "Archivio Documenti".

## Cose da sapere
- I dati restano dentro l'app. Se disinstalli l'app, si perdono: fai i backup.
- Backup: il pulsante apre il menu di Android "Condividi": da lì scegli dove salvarlo
  (File, Google Drive, ecc.). Stesso discorso per il PDF del collage.
- Il PDF si apre dentro l'app anche senza internet.
- Il pulsante "Stampa" del collage nell'app non c'è: usa "PDF" e stampa il PDF dal telefono.
- Questo è un APK di prova ("debug"): va bene per uso personale.
