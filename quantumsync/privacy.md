---
title: Informativa sulla privacy – Quantum Sync
permalink: /quantumsync/privacy/
---

# Informativa sulla privacy – App Quantum Sync

*Ultimo aggiornamento: 10 novembre 2026*

Quantum Sync è un'app Android che sincronizza due cartelle scelte dall'utente (sul telefono, su server
FTP/FTPS, SFTP, WebDAV, SMB o su Google Drive) e conserva le versioni precedenti dei file.
[Home page di Quantum Sync](https://terronologo.github.io/privacy/quantumsync/)

## Titolare e contatti
Lo sviluppatore di Quantum Sync – email: marc.pantina@gmail.com

## Principio generale
Quantum Sync **non ha un server proprio** e non richiede la creazione di un account. Lo sviluppatore non riceve,
non vede e non conserva i tuoi file né i tuoi dati: tutto resta sul telefono e nelle cartelle o nei servizi che
configuri tu.

## Dati trattati sul dispositivo
- **Configurazione**: connessioni (indirizzi dei server, nome utente, cartelle), sincronizzazioni pianificate,
  storico delle sincronizzazioni ed elenco dei file sincronizzati. È salvata in un database locale sul telefono.
- **Credenziali**: password, chiavi SSH e accessi a Google sono salvati nell'archivio sicuro di Android
  (Keystore), mai in chiaro, e non sono inclusi nell'esportazione della configurazione.
- **File**: i file vengono letti dalla cartella di origine e copiati nella cartella di destinazione scelta.
  Le versioni precedenti sono conservate nella destinazione per il periodo che imposti (predefinito 14 giorni)
  e poi cancellate automaticamente.

## Dati di Google (Google Drive)
Se colleghi un account Google, l'app chiede il permesso di accesso a Google Drive
(`https://www.googleapis.com/auth/drive`) e legge l'indirizzo email dell'account per mostrarti a quale account
sei collegato.

- **Uso**: i dati di Drive (elenco di file e cartelle, contenuto dei file) sono usati **solo** per eseguire le
  sincronizzazioni che hai configurato: elencare le cartelle, scaricare e caricare file, creare cartelle,
  spostare ed eliminare file nelle cartelle sincronizzate. L'accesso completo a Drive serve per poter scegliere
  una cartella già esistente.
- **Conservazione**: il token di accesso è salvato solo sul telefono, nell'archivio sicuro di Android. L'elenco
  dei file sincronizzati è salvato nel database locale. Nessun dato di Google viene inviato allo sviluppatore o
  a server diversi da quelli di Google.
- **Condivisione**: i dati di Google non sono condivisi, venduti o trasferiti a terzi, non sono usati per
  pubblicità e non sono usati per addestrare modelli di intelligenza artificiale.
- **Revoca**: puoi scollegare l'account dall'app (eliminando la connessione) oppure revocare l'accesso in
  qualsiasi momento da <https://myaccount.google.com/permissions>.

L'uso e il trasferimento ad altre app delle informazioni ricevute dalle API di Google rispettano le
[Norme sui dati utente dei servizi API di Google](https://developers.google.com/terms/api-services-user-data-policy),
inclusi i requisiti di Uso limitato (Limited Use).

## Permessi del telefono
- **Accesso a tutti i file**: per leggere e scrivere le cartelle locali da sincronizzare.
- **Posizione**: richiesta da Android solo per leggere il **nome della rete Wi-Fi**, se usi l'opzione
  "solo con la Wi-Fi di casa". La posizione non viene letta, salvata né inviata.
- **Notifiche e servizio in primo piano**: per mostrare l'avanzamento e il risultato delle sincronizzazioni.

## Cosa l'app NON fa
- Non contiene pubblicità.
- Non usa strumenti di analisi, tracciamento o raccolta degli errori.
- Non vende né cede dati a terzi.

Gli unici servizi esterni contattati sono i server che configuri tu e, se usi Google Drive, i server di Google
(accounts.google.com, oauth2.googleapis.com, www.googleapis.com).

## Eliminazione dei dati
Tutti i dati dell'app sono sul telefono: disinstallando l'app o cancellandone i dati da Impostazioni → App
vengono eliminati configurazione, storico e credenziali. I file e le versioni copiati nelle destinazioni restano
nelle tue cartelle e puoi cancellarli quando vuoi. Per domande scrivi a marc.pantina@gmail.com.

## Diritti dell'utente
Poiché lo sviluppatore non conserva dati personali, non ci sono dati da consultare o cancellare presso di lui.
Puoi comunque scrivere a marc.pantina@gmail.com e proporre reclamo al Garante per la protezione dei dati
personali (www.garanteprivacy.it).

## Modifiche
Eventuali modifiche a questa informativa saranno pubblicate su questa pagina, con la data di aggiornamento.

---

<h2 id="english">English – Privacy policy</h2>

*Last updated: 10 November 2026*

Quantum Sync is an Android app that synchronises two folders chosen by the user (on the phone, on FTP/FTPS,
SFTP, WebDAV or SMB servers, or on Google Drive) and keeps previous versions of the files.
Contact: marc.pantina@gmail.com

**No server, no account.** Quantum Sync has no server of its own and requires no account. The developer does not
receive, see or store your files or data: everything stays on your phone and in the folders or services you
configure.

**Data on the device.** Connections, scheduled syncs, sync history and the list of synced files are stored in a
local database on the phone. Passwords, SSH keys and Google access tokens are stored in the Android Keystore and
are never included in configuration exports. Previous file versions are kept in the destination for the period
you choose (14 days by default) and then deleted automatically.

**Google user data.** If you connect a Google account, the app requests the Google Drive scope
(`https://www.googleapis.com/auth/drive`) and reads the account e-mail address to show which account is
connected. Drive data (file and folder lists, file contents) is used **only** to run the syncs you configured:
listing folders, downloading and uploading files, creating folders, moving and deleting files in the synced
folders. Full Drive access is needed to let you pick an existing folder. The access token is stored only on the
phone in the Android Keystore. Google user data is never sent to the developer or to any server other than
Google's, is not shared, sold or transferred to third parties, is not used for advertising and is not used to
train artificial intelligence models. You can disconnect the account in the app or revoke access at any time at
<https://myaccount.google.com/permissions>.

Quantum Sync's use and transfer to any other app of information received from Google APIs will adhere to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

**Permissions.** All files access (to sync local folders); location, required by Android only to read the Wi-Fi
network name for the "home Wi-Fi only" option (location is never read, stored or sent); notifications and a
foreground service (to show sync progress).

**No ads, no analytics, no tracking, no crash reporting, no sale of data.** The only external services contacted
are the servers you configure and, if you use Google Drive, Google's servers.

**Deletion.** All app data is on the phone: uninstalling the app or clearing its data removes configuration,
history and credentials. Files and versions copied to your destinations stay in your folders until you delete
them. For any question write to marc.pantina@gmail.com.
