# Traduzione-ZTD
Progetto di traduzione del porting PC di Zero Time Dilemma.

## Prerequisiti

-Avere un account GitHub;

-Avere git installato sul pc:

    Windows: 
    -Scaricare git dal seguente indirizzo:https://git-scm.com/download/win;
    -Premere "Next" finché non viene chiesto l'editor predefinito (personalmente consiglio "Sublime Text");
    -Premere "Next" finché non parte l'installazione di Git.
    
    Linux:
    -Scaricate git col vostro gestore pacchetti (Ubuntu e derivate: sudo apt-get install git; Archlinux e derivate: sudo pacman -S git).
    
## Istruzioni

### Creazione cartella (solo prima volta)

-Creare una cartella nella quale lavorare;

-Aprire il terminale in quella cartella (Windows: tasto destro->"Git Bash Here"; Linux: avviare terminale e digitare "cd [percorso della cartella precedentemente creata (ps: va bene anche trascinare la cartella nel terminale)]" senza le parentesi quadre);

-Scrivere 'git clone https://github.com/giovanni9793/Traduzione-ZTD' e 'cd ./Traduzione-ZTD';

-Settare le credenziali con 'git config --global user.name "[nome che volete]"' e 'git config --global user.email [email di github]', senza gli apostrofi e le parentesi quadre.

### Upload dei file modificati (tradotti)

-Aprire il terminale, come da sezione precedente, nella cartella dove c'é il file modificato;

-Scrivere 'git add [Nome del file]', 'git commit -m "[Nome significativo tipo: Tradotta mappa 1° piano]"' e 'git push', quindi mettere nome utente e password di github quando richieste.

### Come contribuire

-Seguire "Prerequisiti";

-Andare su https://github.com/giovanni9793/Traduzione-ZTD, quindi premere il tasto in alto a destra "FORK";

-Seguire le istruzioni di "Creazione cartella (solo prima volta)", ma sostituire 'https://github.com/giovanni9793/Traduzione-ZTD' con qualcosa del tipo 'https://github.com/[vostro nome utente]/Traduzione-ZTD', senza le parentesi quadre;

-Una volta che avete modificato il file che volete scrivete nel terminale 'cd ./Traduzione-ZTD', 'git add .', 'git commit -m "[Nome significativo tipo: Tradotta mappa 1° piano]"' e 'git push';

-Andate su https://github.com/[vostro nome utente]/Traduzione-ZTD (nel browser), cliccate sul pulsante "New pull request" (sotto il numero dei commit), quindi su "Create pull request", quindi nuovamente sul tasto verde.
