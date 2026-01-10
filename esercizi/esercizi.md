PARTE 1 – Operazioni base con Git
Esercizio 1 – Clone di un repository
Clona un repository Git pubblico a tua scelta.
Entra nella cartella del progetto.
Verifica che il repository sia correttamente collegato all’origine remota.

Esercizio 2 – Creazione di un repository
Crea una nuova cartella chiamata git-esercizi.
Inizializza un repository Git al suo interno.
Verifica che Git sia attivo nella cartella.

Esercizio 3 – Controllo dello stato
Crea un file README.md.
Controlla lo stato del repository.
Identifica i file untracked.

Esercizio 4 – Aggiunta file allo stage
Aggiungi README.md allo stage.
Verifica lo stato del repository.

Esercizio 5 – Commit
Effettua un commit con messaggio significativo.
Controlla lo stato dopo il commit.

Esercizio 6 – Rollback delle modifiche locali
Modifica README.md senza fare commit.
Annulla le modifiche riportando il file allo stato dell’ultimo commit.

🌿 PARTE 2 – Gestione dei branch
Esercizio 7 – Creazione e uso dei branch
Crea un branch chiamato feature-login.
Passa al branch appena creato.
Crea un file login.txt e fai un commit.
Torna sul branch main.

🔁 PARTE 3 – Reset e Restore
Esercizio 8 – Reset di una commit mantenendo le modifiche
Fai una modifica e una commit.
Annulla la commit mantenendo le modifiche nello stage.

Esercizio 9 – Togliere file dallo stage
Modifica un file e aggiungilo allo stage.
Rimuovi il file dallo stage mantenendo le modifiche nel file.

Esercizio 10 – Spostare modifiche su un altro branch
Modifica un file senza fare commit.
Crea un nuovo branch.
Porta le modifiche sul nuovo branch.
Esegui stage e commit.

📜 PARTE 4– Log
Esercizio 11 – Analisi dello storico
Visualizza la cronologia dei commit.
Usa una versione compatta del log.
Visualizza solo gli ultimi 3 commit.

🔀 PARTE 5 – Rebase
Esercizio 12 – Rebase di un branch
Crea un branch feature-rebase.
Fai almeno una commit.
Torna su main e fai una commit.
Riporta feature-rebase aggiornato usando rebase.

🚫 PARTE 6– .gitignore
Esercizio 13 – File ignorati
Crea un file .gitignore.
Aggiungi l’esclusione per:
node_modules/
.env
*.log

Verifica che Git ignori questi file.

🌍 PARTE 7– Repository remoto
Esercizio 14 – Push, Pull, Fetch
Collega il repository locale a uno remoto.
Esegui il push del branch main.
Simula una modifica remota e recuperala con fetch.

Allinea il branch locale.

🗑️ PARTE 8 – Rimozione file dal repository
Esercizio 15 – Rimuovere un file versionato
Elimina un file già tracciato.
Registra la rimozione con una commit.
Verifica lo stato finale.