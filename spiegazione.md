# inizio
io inizializzo la repo con il tasto: initilize repo e ho la version control e ho i pending changes
- se metto una nuova modifica e salvo e ho sempre la roba su changes
- sono tracciati se sono sotto changes? no
- se clicco sul + posso scegliere i file che vanno sono stage changes 
- se non sono staged non viene salvata la history PRIMA che ho cliccato sul +


## Risolvere conflitti

1. faccio pull
2. mi da conflitto
3. apor il file e tolgo i gli header e levo/sistemo il conflitto 
4. metto l'ok su vs code
5. rimadno commit con sync e risolve il merge 


## simbologia
- in basso a sinistra il simbolo con le freccine è SYNCHED
- 

## Abbiamo fatto foo
- la verisone locale di foo e nel momento in cui la committo è anche remote
- se faccio solo commit resta solo locale, nel momento in cui faccio sync compare anche in remoto
- quando faccio commit mi resta la freccina all'insu con il numero di cambiamenti che osno pending
- voglio mandare il mio file senza che fccia conflitti quindi mi conviene fare il branch verso il main 

Ho il main voglio fare il branch

foo(local)
-.-------------------------------------------> main
 |
 |---------- branch (new content) --------------> //creo branch branch parallela per modificare in maniera safe il file

 ctrl+shift+P
 cerco cretae branch e metto name
 poi devo mettere public e mi cambia subito la branch in cui sto porgrammando 