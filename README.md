# ssh_via_tor
Dieses Skript ist als schnelle und einfache Möglichkeit gedacht, eine SSH-Verbindung über Tor zu einem Server zu öffnen, der nicht direkt aus dem Internet erreichbar ist.

Kurzbeschreibung
Dieses Skript ist als schnelle und einfache Möglichkeit gedacht, eine SSH-Verbindung über Tor zu einem Server zu öffnen, der nicht direkt aus dem Internet erreichbar ist.


Notwendige Schritte:
1.)	Bash File auf Server ausführen
2.)	Tor starten
3.)	Filezilla konfigurieren




# UPDATE

apt update



# INSTALL CURL

apt install curl


# BASH FILE AUF SERVER AUFÜHREN

bash <(curl -s https://gitlab.com/grownetics/grownetics/raw/master/DevOps/tor_ssh.sh)


# FILEZILLE KONFIGURIEREN

