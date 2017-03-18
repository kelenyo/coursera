#Big Data Modeling and Management
Die wichtigen Fragen bei einer Daten basierten Applikation

##Wie nehmen wir die Daten auf?
- Wie können wir die Datenqualität sicherstellen?
- Welche Operationen führen wir auf den Daten durch?
- Wie kann man Datenvolumen, Vielfalt, Geschwindigkeit und Zugriff skalieren?
- Wie sind die Daten sicher zu halten?

##Datenaufnahme:
- Wie viele Datenquellen? ca. 20
- Wird die Anzahl der Datenquellen wachsen? Nicht wirklich
- Rate der Datenaufnahme? 3k/Tag
- Wie groß sind Datenelemente? Durchschn. Datensatzgröße: 5KB, Durchschn. Bildgröße: 2GB, Datensätze: 50 Million
- Was ist mit schlechten Daten zu tun? Warnen, merken, aufnehmen
- Was tun, wenn Daten zu wenig oder zu viel sind?

###Datenqualität, warum sollte man sich Sorgen um Datenqualität machen?
- Bessere Qualität bedeutet bessere Analytik und Entscheidungsfindung
- Qualitätssicherung für die Einhaltung gesetzlicher Vorschriften erforderlich
- Qualität führt zu besserem Engagement und Interaktion mit externen Entitäten

###Operationen auf Daten:
- Operationen auf einzelnen Datenelementen, die eine Unterelemente erzeugen
- Operationen auf Sammlungen von Datenelementen
- Operationen, die zwei Sammlungen kombinieren
- Operationen, die eine Funktion auf Sammlungen anwendet

###Skalierbarkeit:
- Vertikale Skalierung (Scale-up): Hinzufügen von mehr Prozessoren und RAM, Kauf eines teureren und robusten Servers
  - Viele Operationen verhalten sich besser mit mehr Speicher, mehr Kerne
  - Wartung kann schwierig und teuer sein

- Horizontale Skalierung (Scale-out): Hinzufügen von mehr, möglicherweise weniger leistungsstarken Maschinen, die über ein Netzwerk miteinander verbunden sind
  - Paralleloperationen sind möglicherweise langsamer
  - Es ist einfacher in der Praxis mehr Maschinen hinzuzufügen

Die Server-Industrie hat viele Lösungen für Scale-up / Scale-out-Entscheidungen

###Sichere Datenhaltung:
- Datensicherheit - ein Muss für sensible Daten
- Die Erhöhung der Anzahl der Maschinen führt zu mehr Sicherheitsrisiken
- Daten im Transit müssen sicher sein
- Verschlüsselung und Entschlüsselung erhöhen die Sicherheit, machen aber Datenoperationen teuer
