BPMN 2.0

# Objekte

# Pools and Lanes 
Pools sind Organisationen oder Rollen (Abteilungen)-> Ganzes Ding
Lanes Untergliderung von Pools ( Unter Rollen)

## Start symbol
Dünne Linien 

## Stop symbol 
Dicke Linien

# Daten Objekte 

# Gateway 
Ja / Nein Gateway mit X 

***exklusive Gateways***		| ereignisbasierte exklusive Gateways
XOR -> Ja oder Nein 

> Symbole = Raute leehr oder Raute mit X 

XOR-Join -> Zusammenführng zweier sequenzflüsse

***parallele Gateways***		| ereignisbasierte parallele Gateways
Und Bedingung

Wenn Aktivitäten Parralel bearbeitet werden 
zum teilen und zusammenführen der Aktiviäten
Muss zwingend zusammengeführt werden

> Symbole = Raute mit +			> Symbole = Raute mit lehrem +
	
***inklusive Gateways*** 

Oder Bedingung

Werden Aktivitäten Parralel durchgeführt aber es müssen nicht alle ausgeführt werden sondern einfach mindestens eine. 

> Symbole = Raute mit o	

***ereignisbasierte Gateways***	| ereignisbasierte exklusive Gateways

gleich wie ein exclusives Gateway aber ausgelöst von einem Erreignis

> Symbole = Raute mit zwei kreisen und einem Viereck


Komplexe Gateways 

Gateway Aufgabe wird mit Text definiert 
z.b Min.2 aus 3 Aktiviäten müssen ausgeführt werden.

> Symbole = Raute mit *	

# Aktivität 
Arbeitseinhaten in einem Prozess

***Aufgaben***

> Symbole = Rechteck mit dünner line	

***Teilprozesse***
Aktiviät mit Subaktivitäten

> Symbole = Rechteck mit dünner line und +

***Aufruf-Aktivität***
Wird global definiert und hier nur verlinkt.

> Symbole = Rechteck mit dicker line

***Task-definition***

Siehe JPEG

***Schleifen***
Wenn etwas mehrmals ausgeführt wird (Bewerbung Prüfen)

> Symbole = Runder Pfeil 

***Mehrfachaktivitäten***
Wenn etwas mehrfach seriell oder parralel ausgeführt werden muss 

Unterschid zu schleiffe weis man bereits wie viel mal man es durchführen muss. 

> Symbole = Hamburger

# Sequenzfluss 
Fluss Lienien / Lienien zwischen erregnissen. 
Reienfolge wird definiert

# Ereignis 

***Startereignis*** 

> Symbole = Ein kreis 

***Zwischenereignis***

> Symbole = zwei Kreise

	Eintretendes Zwischenereignis
	Bestellung wird empfangen (Ereigniss das herein kommt)
	> Symbole = Leeres E-Mail
	

	auslösendes Zwischenereignis
	Verschicken von bestellung ( ausgehendes ereignis)
	> Symbole = volles E-Mail

***Endereignis***

> Symbole = Ein dicker kreis

***Eregnis-definition**

Es kann jedes Erreignis mit einem Symbol / definition ergänzt werden. 

beendet alle aktiven Pfade ausf aktueller Prozessebene. 

*** Link-Ereignis***

Weiterleitung 

> Symbole = dicker Pfeil
