# Virtual Studio Code instellen
Volgende zaken worden besproken:

[Github]()
## Github
Het synchroniseren van Github met VS Code in Windows vereist enkele stappen. Hier is een stapsgewijze uitleg:

1. Git installeren Als u nog geen Git op uw computer hebt geïnstalleerd, moet u dit eerst doen. U kunt Git downloaden vanaf de officiële website: https://git-scm.com/downloads. 
Volg de installatie-instructies om Git op uw computer te installeren.
2. Github-account maken Als u nog geen Github-account hebt, moet u er een maken. Ga naar https://github.com/join en volg de instructies om een account aan te maken.


3. Extensies installeren Om Github te synchroniseren met VS Code, moet u enkele extensies installeren. Hier zijn de extensies die u nodig hebt:
•	Github Pull Requests and Issues: https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github
•	Github classroom: https://marketplace.visualstudio.com/items?itemName=GitHub.classroom

Om deze extensies te installeren, opent u VS Code en klikt u op de knop "Extensions" in de zijbalk aan de linkerzijde van het scherm. Typ vervolgens de naam van elke extensie in het zoekvak en klik op "Install" om ze te installeren.

4. Verbinden met Github 
Nu kunt u VS Code verbinden met uw Github-account 
*	Open VS Code en druk op Ctrl+Shift+P (of Command+Shift+P op Mac) om de opdrachtprompt te openen.
*	Typ "Github: Sign in" en druk op Enter.
*	volg de instructies
*	U bent nu verbonden met uw Github-account. U kunt dit controleren door op de knop "accounts" te klikken in de zijbalk aan de linkerzijde beneden van het scherm. 
___

## Microbit programmeren in vs code
Ook om te werken met de microbit in vs code, moet je enkele extenties installeren:

Zoek bij de extenties voor "microbit", installeer van daaruit de volgende [extentie](https://marketplace.visualstudio.com/items?itemName=MAKinteract.micro-bit-python) .


Met deze extentie kan de microbit geprogrammeerd worden met micropython.



Om de commando's voor de extensie te zien, gebruik je het commandopalet (**Windows / Linux**: `CTRL + Shift + P`, **Mac**: `⌘ + Shift + P`) en zoek je naar `micro:bit -python`. U ziet de volgende lijst.

![Opdrachten](images/commands.png)

Een uitgebreide uitleg vind je als je [hier](https://marketplace.visualstudio.com/items?itemName=MAKinteract.micro-bit-python) .


#### Beknopte handleiding
Raadpleeg [deze link](https://youtu.be/eSGJLu1kqyg) voor een video-tutorial over het gebruik van deze extensie.

1. [Download en installeer](https://www.python.org/downloads/) python op uw systeem, bij voorkeur python3.
   
2. Open VSCode en installeer de [micro:bit python-extensie](https://marketplace.visualstudio.com/items?itemName=MAKinteract.micro-bit-python)
3. Sluit de micro:bit aan via een USB-kabel (zorg ervoor dat je kabel gegevensoverdracht mogelijk maakt en dat het niet alleen een oplaadkabel is)
4. Voer de eerste keer de opdracht `micro:bit-python: Flash MicroPython-omgeving op micro:bit` uit

* Bij elke oefening moet de microbit-map aanwezig zijn in de oefeningen-map. Deze map bevat alle modules die nodig zijn. Als dit nog niet aanwezig is, kan je dit doen met onderstaand commando:
`micro:bit-python: Initialize the workspace` uit. Kies de lege code.

* Upload je bestanden naar de micro:bit met het commando `micro:bit-python: Flash sketch on the micro:bit`. 
  * er moet altijd een main.py bestand aanwezig zijn in de map.

___

### Serial monitor
Om de uitvoer van de micro:bit te kunnen lezen, installeren we de extentie [Serial Monitor](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-serial-monitor).
Als deze extentie geïnstalleerd is, kunnen we de monitor openen, door een terminalvenster te openen, en het tabblad 'serial monitor' te openen.
* selecteer 'start monitoring' om te starten.
* Als je nu probeert te flashen, zal dit niet lukken. Je moet de monitoring eerst opnieuw stoppen.

