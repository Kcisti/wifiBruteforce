# Presentation
Il funzionamento dello script si basa su alcune librerie Python fondamentali. Utilizza subprocess per eseguire comandi di sistema, os per interagire con il sistema operativo e time per gestire i ritardi tra i tentativi. Lo script identifica le interfacce di rete disponibili, consente all'utente di selezionare quella desiderata e carica una lista di password da un file specificato.

Per ogni password nella wordlist, lo script tenta di connettersi alla rete Wi-Fi specificata. Se la connessione ha successo, la password viene segnalata come corretta e il processo termina. In caso di fallimento, lo script procede con la password successiva fino all'esaurimento della wordlist.

# Tested on platforms:
  - Windows
  - Linux

# Collaborations
This project has been possible thanks to the indirect collaboration of many other developers. If you are one of them and want to be sued, do not hesitate to contact me.

# Disclaimers
The author takes no responsibility for how this tool will be used. Do not use it for malicious purposes!

