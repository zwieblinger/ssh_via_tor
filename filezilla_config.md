Dieses Tutorial zeigt dir, wie du dich mit Filezilla über Tor mit sftp verbinden und Dateien von deinem versteckten Dienst herunterladen kannst.

Tor-Netzwerk verbinden
Zuerst musst du das Tor-Netzwerk konfigurieren, um es zu verbinden. Um das Tor-Netzwerk zu verbinden, musst du den Tor-Browser öffnen (wenn du den Tor-Browser nicht installiert hast, kannst du diese Anleitung lesen, um den Tor-Browser zu installieren). Klicke auf "Verbinden" und du hast dich mit dem Tor-Netzwerk verbunden.

Herunterladen des SFTP-Clients
In dieser Anleitung verwenden wir Filezilla als SFTP-Client. Es ist nicht notwendig, Filezilla zu benutzen. Du kannst auch einen anderen SFTP-Client benutzen, wenn du das möchtest.

SFTP-Client konfigurieren
Um Filezilla zu konfigurieren, klicken Sie im Menü auf "Bearbeiten" und wählen Sie "Einstellungen".

Klicken Sie auf den Proxy-Typ "generischer Proxy", dann auf "SOCKS 5" und geben Sie den Wert wie unten gezeigt ein

Proxy-Host: 127.0.0.1
Proxy-Anschluss: 9150

*Wenn Sie die Verbindung zu Ihrem versteckten Dienst hergestellt haben, müssen Sie Ihre Einstellungen zurücksetzen - und den Proxy-Typ auf "Kein" setzen. Andernfalls können Sie sich nicht mit dem Clearnet-Dienst verbinden, wenn Sie den Tor-Browser schließen.

Um sich mit dem versteckten Dienst zu verbinden, müssen Sie den Host, den Benutzernamen, das Passwort und den Port eingeben. Sie können die Werte von unserer Hosting Admin Access Seite kopieren.

Nachdem Sie SFTP verbunden haben, können Sie das Zugriffsprotokoll und das Fehlerprotokoll von Ihrem Hosting herunterladen. Und Sie können Ihre Website-Datei in Ihr www-Root-Verzeichnis hochladen, indem Sie SFTP über das Tor-Netzwerk verbinden.
