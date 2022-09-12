# script-windows10

### ITA
È un semplice script per sistemi operativi Windows per rimuovere le applicazioni oppure i programmi preinstallati di Windows che non si possono disinstallare semplicemente con il tasto destro del mouse.

Le applicazioni che si andranno a rimuovere sono quelle legate ad Xbox, Maps o comunque sia non sono app di sistema fondamentali per il funzionamento del sistema.

Si consiglia sempre di effettuare un backup del sistema, non mi assumo responsabilità in caso di possibili malfunzionamenti.

#### Istruzioni

Ci sono due vie:

- Più semplice e sicura, ovvero è sufficiente avviare Powershell (anche in modalità utente) nella cartella dove risiede lo script scrivendo "powershell" nella barra del percorso, a questo punto è possibile copiare i singoli comandi ed eseguirli uno ad uno manualmente.

- La seconda è una modalità più avanzata, opzionale, la quale richiede di avviare Powershell in modalità amministratore ed eseguire il comando "Set-ExecutionPolicy RemoteSigned", dare conferma, a questo punto, si può aprire la cartella dove risiede lo script per eseguire una seconda finestra Powershell ed eseguire il comando "./script.ps1".

### ENG
It is a simple script for Windows operating systems to remove applications or preinstalled Windows programmes that cannot be uninstalled simply by right-clicking.

The applications that will be removed are those related to Xbox, Maps or in any case aren't system apps that are essential for the system to function.

It is always advisable to make a backup of the system, I don't take responsibility in the event of possible malfunctions.

#### Instructions

There are two ways:

- Easier and safer, i.e. simply start Powershell (also in user mode) in the folder where the script resides by typing "powershell" in the path bar, at which point you can copy the individual commands and execute them one by one manually.

- The second is a more advanced, optional mode, which requires you to start Powershell in administrator mode and execute the command "Set-ExecutionPolicy RemoteSigned", give confirmation, at this point, you can open the folder where the script resides to run a second Powershell window and execute the command "./script.ps1".
