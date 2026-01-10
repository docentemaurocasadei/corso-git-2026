Soluzione 1 – Clone
git clone https://github.com/docentemaurocasadei/corso-git-2026
cd repo
git remote -v

Soluzione 2 – Creazione repository
mkdir git-esercizi
cd git-esercizi
git init

Soluzione 3 – Stato
touch README.md
git status

Soluzione 4 – Stage
git add README.md
git status

Soluzione 5 – Commit
git commit -m "Aggiunto README iniziale"
git status

Soluzione 6 – Rollback modifiche locali
git restore README.md

Soluzione 7 – Branch
git branch feature-login
git checkout feature-login
touch login.txt
git add login.txt
git commit -m "Aggiunto file login"
git checkout main

Soluzione 8 – Reset mantenendo lo stage
git reset --soft HEAD~1

Soluzione 9 – Rimuovere dallo stage
git restore --staged nomefile.ext

Soluzione 10 – Spostare modifiche su altro branch
git checkout -b nuovo-branch
git add .
git commit -m "Spostate modifiche su nuovo branch"

Soluzione 11 – Log
git log
git log --oneline
git log -3

Soluzione 12 – Rebase
git checkout feature-rebase
git rebase main

Soluzione 13 – .gitignore
node_modules/
.env
*.log


git status

Soluzione 14 – Remoto
git remote add origin https://github.com/utente/repo.git
git push -u origin main
git fetch
git pull

Soluzione 15 – Rimuovere file
git rm nomefile.ext
git commit -m "Rimosso file non più necessario"