
# HTTP-Statuscodes

# Welcome

##  



####Was ist ein HTTP-Statuscode ?
Geht bei einen Server eine Anfrage für eine Website ein, beispielsweise wenn ein Nutzer über einen Browser auf eine Webseite zugreift will, gibt der Server auf die Anfrage einen Http-Statuscode zurück. Dieser Statuscode enthält Informationen über den Status der Anfrage. 

Folgende Statuscodes werden häufig angezeigt:

- 200: Die Seite wurde erfolgreich vom Server zurückgegeben.
- 404: Die gewünschte Seite ist nicht vorhanden.
- 503: Der Server ist vorrübergehend nicht verfügbar

#Basiscodes  

##1xx (Vorläufige Antwort) 

Diese Statuscodes bedeuten, dass nur eine vorläufige Antwort zurückgegeben wurde und der Anfragende weitere Maßnahmen ergreifen muss.

Beispiele:

#####100(Weiter): 

Der Anfragende soll die Anfrage fortsetzen. Dieser Code zeigt an, dass der Server den ersten Teil der Anfrage erhalten hat und nun auf den Rest wartet.

#####101(Umstellung der Protokolle):

Der Anfragende hat vom Server eine Umstellung der Protokolle gefordert, die vom Server bestätigt und vorgenommen wird.


##2xx (Erfolgreiche Operationen) 

Diese Statuscodes geben an, dass die Anforderung vom Server erfolgreich verarbeitet wurde.


Beispiele: 


#####200 (Erfolgreich):
Die Anfrage wurde vom Server verarbeitet. Im Allgemeinen bedeutet dies, dass die angeforderte Seite vom Server zurückgegeben wurde. 

#####202 (Akzeptiert):

Die Anforderung wurde vom Server angenommen, aber noch nicht verarbeitet.


##3xx (Weitergeleitet)

Die 3xx-Klasse zeigt an, dass die Anfrage zwar korrekt empfangen wurde, der Benutzer jedoch Änderungen an der Anfrage zur Ressource machen sollte.

Beispiele: 

#####300 (Mehrfachauswahl):
Der Server hat bei dieser Anfrage die Wahl zwischen mehreren Aktionen. Entweder wählt er eine vom Anfragenden, dem User-Agent, angeforderte Aktion aus oder stellt dem Anfragenden eine Liste mit Aktionen zur Auswahl.


#####305 (Proxy verwenden):

Der Anfragende kann nur über einen Proxy-Server auf die gewünschte Seite zugreifen. Bei dieser Antwort des Servers wird auch der zu verwendende Proxy angegeben.

##4xx (Anfragefehler)

Diese Statuscodes deuten darauf hin, dass die Anforderung wahrscheinlich einen Fehler enthält, der die Verarbeitung durch den Server verhindert.

Beispiele: 

#####400 (Ungültige Anfrage):

Der Server konnte die Syntax der Anforderung nicht interpretieren.

#####401 (Nicht autorisiert):

Die Anfrage erfordert eine Authentifizierung. Der Server gibt diese Antwort unter Umständen für eine Seite nach einer Anmeldung zurück.


##5xx (Serverfehler)

Diese Statuscodes bedeuten, dass beim Verarbeiten der Anfrage ein interner Fehler auf dem Server aufgetreten ist. In der Regel werden diese Fehler vom Server selbst und nicht von der Anfrage verursacht.

#####500 (Interner Serverfehler):

Der Server kann die Anforderung aufgrund eines Fehlers nicht ausführen.

#####502 (Falsches Gateway): 

Der Server hat als Gateway oder Proxy agiert und von einem vorgeschalteten Server eine ungültige Antwort erhalten.




##Fachbegriffe

#####Proxy:
Ein Proxy ist eine Kommunikationsschnittstelle in einem Netzwerk. Er arbeitet als Vermittler, der auf der einen Seite Anfragen entgegennimmt, um dann über seine eigene Adresse eine Verbindung zur anderen Seite herzustellen.

#####Client

Ein Client bezeichnet ein Computerprogramm, das auf dem Endgerät eines Netzwerks ausgeführt wird und mit einem Zentralrechner Server kommuniziert. Man nennt auch ein Endgerät selbst, das Dienste von einem Server abruft, Client

#####Syntax
Die Syntax einer Sprache (eines Zeichensystems) beschreibt die Regeln, nach denen die Sprachkonstrukte (Zeichen des Zeichensystems) gebildet werden