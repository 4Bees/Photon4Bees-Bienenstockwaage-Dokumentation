# Verbindung mit dem Internet [](id=verbindung-mit-dem-Internet)

Das WLAN-Modul des Photon ermöglicht es, die Photon4Bees-Bienenstockwaage mit dem Internet zu verbinden. Die Verbindung mit dem Internet erfolgt über die gleiche Weise wie es ein Smartphone macht.
Da die Bienenstockwaage allerdings keine Eingabemöglichkeit (Touchscreen bzw. Tastatur) hat, muss die Bienenstockwaage zunächst einen Hotspot zur Verfügung stellen. Über den Hotspot kann dann ein Smartphone mit der Stockwaage verbunden werden und die WLAN-Konfiguration vorgenommen werden.

### WLAN-Hotspot erstellen

Beim ersten Mal einschalten der Stockwaage, beginnt die LED blau zu leuchten. Dies bedeutet, dass das Photon einen WLAN-Hotspot zur Verfügung stellt.
Wenn Sie zu einem späteren Zeitpunkt die WLAN-Konfiguration ändern wollen, müssen Sie einfach bevor Sie die Bienenstockwaage einschalten den linken Taster drücken und solange halten bis Sie den EIN/AUS-Schalter auf EIN gestellt haben. Die LED sollte nun ebenfalls blau blinken.

### Smartphone mit der Bienenstockwaage verbinden

Gehen Sie bei Ihrem Smartphone auf die WLAN-Einstellungen. Schalten Sie Ihr WLAN am Smartphone ein und wählen Photon-xxxxxx als WLAN-Netz. Sobald Sie mit dem Photon-xxxxxx WLAN-Netz verbunden sind öffnen Sie Ihren Internet-Browser am Smartphone. Geben Sie im Eingabefeld die URL: 192.168.0.1 ein. Auf Ihrem Smartphone sollte nun folgende Seite erscheinen.

![Smartphone mit Bienenstockwaage verbinden](..images/WLAN-Konfiguration_1.JPG)

Klicken Sie nun auf den Scan-Button. Nun werden alle verfügbaren WLAN-Netze angegeben.

### WLAN Konfiguration

Wählen Sie das gwünschte WLAN-Netz aus und geben Sie das entsprechende Passwort ein. Drücken Sie den Connect-Button. Die Photon4Bees-Bienenstockwaage verbindet sich jetzt mit dem Internet.

![WLAN Konfiguration](..images/WLAN-Konfiguration_2.JPG)

Die LED blinkt zunächst grün (Verbindung mit dem Internet wird hergestellt), dann Cyan (Verbindung mit der Particle-Cloud wird hergestellt) und schließlich pulsiert die LED in Cyan (das Photon ist mit der Particle-Cloud verbunden).
