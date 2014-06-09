kernel-update
============

Kernel-update   
Written By AleRitty <aleritty#\@/#aleritty.net>   
Aggiorna o gestisce i kernel installati sul sistema

```
Usage: 
sudo ./update-kernel [--help | --upd | --rem ] 

--upd 			Aggiorna il kernel all'ultima versione 
--rem			rimuove tutti i kernel tranne l'ultimo 
--chk			controlla se ci sono aggiornamenti del kernel
--help			Mostra questa schermata 
```

Per maggiori informazioni leggere il contenuto dello script

##todo:

* internazionalizzazione (l'inglese è importante nella vita)
* sistemare rimozione vecchi kernel con scelta manuale

##Nel caso foste a conoscenza di altre distribuzioni che utilizzano il kernel patchato da Ubuntu segnalatemele e provvederò ad aggiungerle allo script!

#ATTENZIONE: tutti gli utenti che hanno una versione minore della 0.46 dovranno aggiornare manualmente lo script! A causa di un problema il sistema di aggiornamento automatico non funziona correttamente nella versione 0.45!
