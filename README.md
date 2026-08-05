# Linux Security Learning Journey

## Obiettivo del percorso

Questo repository documenta il mio percorso pratico di studio di Linux, Bash e sicurezza dei sistemi Ubuntu.

L’obiettivo finale è acquisire le competenze necessarie per progettare e sviluppare autonomamente un **Linux Security Audit Script**, capace di analizzare la configurazione di sicurezza di un sistema Linux e produrre un report comprensibile.

Gli appunti teorici e i riassunti delle risorse vengono conservati separatamente in Obsidian. Questo repository contiene principalmente esercizi, esperimenti, report e script.

## Obiettivi specifici

Durante il percorso voglio imparare a:

* utilizzare con sicurezza il terminale Linux;
* comprendere filesystem, utenti, gruppi e permessi;
* analizzare processi, servizi e log;
* comprendere networking, porte e socket;
* configurare e analizzare SSH;
* utilizzare firewall e aggiornamenti di sicurezza;
* comprendere AppArmor;
* programmare script Bash affidabili;
* eseguire controlli basati sul CIS Ubuntu Linux Benchmark;
* documentare correttamente procedure, risultati ed errori.

## Risorse di studio

Il percorso segue queste risorse, nell’ordine indicato:

1. **The Linux Command Line**
2. **Bash Guide for Beginners**
3. **GNU Bash Reference Manual**
4. **Ubuntu Server Documentation**
5. **CIS Ubuntu Linux Benchmark**

Gli appunti relativi a queste risorse vengono organizzati in Obsidian.

## Struttura del repository

```text
linux-security-learning/
├── README.md
├── exercises/
├── reports/
├── bash-labs/
├── ubuntu-labs/
└── cis-audit/
```

### `exercises`

Contiene gli esercizi pratici svolti durante il percorso.

Ogni esercizio può avere una cartella dedicata:

```text
exercises/
├── exercise-01-filesystem/
│   └── README.md
├── exercise-02-commands/
│   └── README.md
└── exercise-03-redirections/
    └── README.md
```

### `reports`

Contiene:

* tabelle;
* risultati delle analisi;
* inventari del sistema;
* report manuali;
* confronti tra configurazioni;
* evidenze raccolte durante gli audit.

### `bash-labs`

Contiene:

* piccoli script Bash;
* esercizi su variabili e quoting;
* esercizi su condizioni e cicli;
* funzioni;
* gestione degli errori;
* script intermedi sviluppati prima del progetto finale.

### `ubuntu-labs`

Contiene la documentazione degli esperimenti eseguiti sulla macchina virtuale Ubuntu, tra cui:

* utenti e gruppi;
* servizi;
* log;
* networking;
* SSH;
* firewall;
* pacchetti;
* aggiornamenti;
* AppArmor.

### `cis-audit`

Contiene:

* controlli CIS eseguiti manualmente;
* evidenze;
* risultati di conformità;
* mini-audit Level 1;
* controlli selezionati per la futura automazione.

## Ambiente di laboratorio

Gli esercizi che richiedono modifiche al sistema vengono svolti in una macchina virtuale.

### Sistema utilizzato

* Distribuzione: Ubuntu 26.04 LTS
* Tipo di installazione: Desktop
* Shell: Bash
* Repository GitHub: [](https://github.com/noticso/linux-security-learning)
* Applicazione per gli appunti: Obsidian

## Regole di sicurezza

* Non eseguire esperimenti rischiosi sul sistema principale.
* Creare uno snapshot prima delle modifiche importanti.
* Non modificare file di sistema senza averne compreso la funzione.
* Documentare lo stato iniziale e quello finale.
* Ripristinare le configurazioni di laboratorio quando necessario.
* Eseguire attività di sicurezza esclusivamente su sistemi propri o autorizzati.
* Non pubblicare password, chiavi private, token o informazioni sensibili.

## Metodo di studio

Ogni argomento viene affrontato seguendo questo processo:

1. lettura della risorsa;
2. creazione degli appunti teorici in Obsidian;
3. consultazione delle pagine `man`;
4. prova dei comandi nel terminale;
5. svolgimento dell’esercizio;
6. analisi del risultato;
7. documentazione dell’esercizio nel repository;
8. breve riepilogo di ciò che è stato imparato.

## Come documento gli esercizi

Ogni cartella di esercizio contiene un proprio `README.md` con:

* obiettivo;
* risorsa e capitolo studiato;
* concetti necessari;
* ambiente utilizzato;
* procedura seguita;
* comandi utilizzati;
* risultato ottenuto;
* errori incontrati;
* spiegazione degli errori;
* considerazioni di sicurezza;
* conclusioni.

## Avanzamento generale

* [x] The Linux Command Line
* [ ] Bash Guide for Beginners
* [ ] GNU Bash Reference Manual
* [ ] Ubuntu Server Documentation
* [ ] CIS Ubuntu Linux Benchmark
* [ ] Audit manuale completo
* [ ] Progettazione del Linux Security Audit Script
* [ ] Sviluppo della prima versione
* [ ] Test
* [ ] Documentazione finale

## Stato attuale

* Data di inizio: 05/08/2026
* Settimana attuale: Settimana 1
* Giorno attuale: Giorno 1
* Risorsa attuale: The Linux Command Line
* Capitolo attuale: 1
* Ultimo esercizio completato: [inserire esercizio]

## Registro settimanale

### Settimana 1

* Risorsa studiata: The Linux Command Line  
* Capitoli letti: 1
* Esercizi completati:
* File prodotti: Glossario di comandi, Appunti
* Problemi incontrati:
* Cosa ho imparato: `df`, `free`, 
* Stato: Iniziato

### Settimana 2

* Risorsa studiata:
* Capitoli letti:
* Esercizi completati:
* File prodotti:
* Problemi incontrati:
* Cosa ho imparato:
* Stato: Da iniziare

Aggiungere una nuova sezione per ogni settimana.

## Competenze acquisite

### Linux

* [ ] Navigazione nel filesystem
* [ ] Gestione di file e directory
* [ ] Pipe e redirezioni
* [ ] Utenti e gruppi
* [ ] Permessi Linux
* [ ] Processi
* [ ] Servizi systemd
* [ ] Analisi dei log
* [ ] Networking
* [ ] Gestione dei pacchetti

### Bash

* [ ] Variabili
* [ ] Quoting
* [ ] Condizioni
* [ ] Cicli
* [ ] Array
* [ ] Funzioni
* [ ] Parametri posizionali
* [ ] Exit status
* [ ] Gestione degli errori
* [ ] Segnali e `trap`
* [ ] Opzioni con `getopts`

### Sicurezza Ubuntu

* [ ] Audit di utenti e privilegi
* [ ] Analisi dei permessi
* [ ] Analisi dei servizi
* [ ] Analisi dei log di autenticazione
* [ ] Analisi delle porte
* [ ] Audit SSH
* [ ] Verifica del firewall
* [ ] Verifica degli aggiornamenti
* [ ] Analisi di AppArmor
* [ ] Controlli CIS Level 1

## Progetto finale

Il progetto conclusivo sarà un **Linux Security Audit Script**.

La prima versione dovrebbe poter analizzare:

* informazioni generali sul sistema;
* utenti e gruppi;
* privilegi amministrativi;
* file e permessi sensibili;
* servizi attivi e falliti;
* porte in ascolto;
* configurazione SSH;
* stato del firewall;
* aggiornamenti disponibili;
* stato di AppArmor;
* alcuni controlli CIS Level 1.

Il programma dovrà produrre risultati classificati come:

* `INFO`
* `PASS`
* `WARNING`
* `FAIL`
* `MANUAL REVIEW`
* `ERROR`

## Nota personale

Questo repository non serve a raccogliere gli appunti teorici, che vengono gestiti in Obsidian.

Serve a mostrare il lavoro pratico svolto: esercizi, esperimenti, errori, risultati, report e script sviluppati durante il percorso.
