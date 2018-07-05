# Verbindung mit cloud4Bees [](id=verbindung-mit-cloud4bees)

Alle Messwerte der Photon4Bees Bienenstockwaage werden in einer Datenbank gespeichert und können über eine Rest API abgerufen und weiterverarbeitet werden.
Dies erfolgt über die Datenplattform cloud4Bees. Jeder Besitzer einer Photon4Bees Bienenstockwaage benötigt daher ein Konto bei cloud4Bees.at und einen Kanal, um seine Daten zu speichern.

### Erstellung eines Kontos auf cloud4Bees.at

Besuchen Sie die Datenplattform cloud4Bees.at und wählen Sie den Menüpunkt Registrieren:

![Registrierung bei cloud4Bees](..images/cloud4Bees-Registrierung.JPG)

Füllen Sie das Registrierungsformular aus und Sie erhalten Zugang zur Datenplattform cloud4Bees.at.


### Kanal erstellen

Nachdem Sie sich bei cloud4Bees.at angemeldet haben können Sie einen Kanal erstellen. Wählen Sie im Menü Meine Kanäle und klicken Sie auf den Button Erstellen:

![Kanal erstellen bei cloud4Bees](..images/cloud4Bees-Kanal-erstellen.JPG)

Jeder Kanal erhält einen API-Schlüssel und eine Kanal ID. Diese benötigen Sie, um eine Verbindung mit der Bienenstockwaage herzustellen.

### Verbindung mit cloud4Bees herstellen

Dieser Prozess wurde wesentlich vereinfacht und erfolgt nun über ein einfaches Formular. Den Rest erledigt ein Javascript-Programm im Hintergrund. Achten Sie darauf, dass ihr Browser Cookies erlaubt, damit das Programm ungehindert arbeiten kann.

Besuchen Sie die Internetseite  [4Bees.at](https://www.4bees.at/web/guest/cloud4bees). und füllen das folgende Formular aus.

![cloud4Bees - Verbindung herstellen](../images/cloud4Bees-Verbindung-herstellen.JPG)

Die Verbindung wird nun über ein Programm automatisch erstellt. Die Daten werden jedoch erst übermittelt, wenn sie den ersten Schritt der Kalibrierung abgeschlossen haben. Das Programm überprüft, ob ein gültiger Scalefactor vorhanden ist und übermittelt erst dann die Daten.
