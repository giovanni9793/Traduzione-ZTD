# Traduzione-ZTD
Progetto di traduzione del porting PC di Zero Time Dilemma.

# Come contribuire

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

Prima di tutto dovete fare il fork della repository, per farlo:

-Effettuate il login su github ed andate al seguente indirizzo: https://github.com/giovanni9793/Traduzione-ZTD;

-Premete il tasto "Fork" in alto a destra;

Scegliete la modalità che più vi aggrada per la configurazione e l'invio:

### Terminale

#### Creazione cartella (solo prima volta)

-Spostatevi nella cartella che conterrà i file;

-Aprire il terminale in quella cartella (Windows: tasto destro->"Git Bash Here"; Linux: avviare terminale e digitare "cd [percorso della cartella scelta]" senza le parentesi quadre, per non dover inserire il percorso a mano é anche possibile trascinare la cartella nel terminale);

-Scrivere 'git clone https://github.com/[vostro_nome_utente]/Traduzione-ZTD' (es. https://github.com/lorenzo97/Traduzione-ZTD) e 'cd ./Traduzione-ZTD';

-Settare le credenziali con 'git config --global user.name "[nome che volete]"' e 'git config --global user.email [email di github]', senza le parentesi quadre.

#### Upload dei file modificati (tradotti)

-Aprire il terminale, come da sezione precedente, nella cartella dove c'é il file modificato;

-Scrivere 'git add [Nome del file]', 'git commit -m "[Nome significativo tipo: Tradotta mappa 1° piano]"' e 'git push', quindi mettere nome utente e password di github quando richieste.

-Andate su https://github.com/[vostro nome utente]/Traduzione-ZTD (nel browser), cliccate sul pulsante "New pull request" (sotto il numero dei commit), quindi su "Create pull request", quindi nuovamente sul tasto verde.


### GUI (Graphical User Interface)

#### Creazione cartella (solo prima volta)

-Scaricare "Gitkraken" dal seguente indirizzo: https://www.gitkraken.com/;
-Avviare "Gitkrake";
-Effettuare login tramite "Github" e seguire le relative istruzioni;
-Cliccare sul pulsante "Clone a repo" situato a sinistra;
-Cliccare sul pulsante "Browser" e scegliere una cartella nella quale inserire la repo;
-In "URL" incollare il seguente indirizzo: https://github.com/giovanni9793/Traduzione-ZTD.git ;
-(Opzionale) Rinominare a piacere il full path (nome della cartella in cui saranno scaricati i files);
-Cliccare su "Clone the repo!";
-Aspettare messaggio in alto e quindi cliccare su "Open now".

#### Upload dei file modificati (tradotti)

Una volta che avrete modificato i file:

-Avviare Gitkraken;

-Cliccare sul primo rigo (dove c'é la scritta "// WIP");

-Cliccare su "Stage all changes" posizionato a destra;

-Scrivere in "Summary" situato in basso quali file avete modificato;

-(Opzionale) Scrivere in "Description" situato in basso cosa avete modificato nello specifico;

-Cliccare sul tasto "Commit changes";

-Cliccare col tasto destro del mouse sul primo rigo appena creato;

-Cliccare su "Start a pull request to origin from origin/master";

-Inserire un titolo;

-(Opzionale) Inserire una descrizione;

-Cliccare su "Create pull request".
