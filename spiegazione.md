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
 1. cerco cretae branch e metto name
 2. poi devo mettere public e mi cambia subito la branch in cui sto porgrammando 
 Palla = commit

 In quetso primo caos non  ho conflitti se faccio merge perchè in quetso caso l'unico altro commit che c'è è il mio 
 - devo vederlo dal pov temporale e sequenziale di azione, ho conflitti se per dire nel main qualcuno ha fatto modifiche prima che io faccio merge del mio branch 


- se nel mentre sul main succede qualcosa, git non può sapere qual è la versione corretta da mantenere e quindi io devo decidere quale versione voglio mantenere
- quindi git vede due commit a differenza di prima, e ho due versioni diverse -> conflitto 

per fare merge:
1. vado alla mia branch
2. poi al main shift+ctrl+p
3. seleziono merge from e metto la branch
4. poi cliccare l'editor e decidere
5. posso accettare la orrente, la nuova o mantenere originale e rifitutare tutto o un merge delle due
Se ho codice posso anche deicdere di mantere both e scrivere io qualcosa che serva nell'editor



Una volta scelto metto complete merge
Ho scelto la verisone corretta per il futuro
Posso anche tornare indietro e capire cosa è successo nel tempo 

