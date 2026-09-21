# Codebuch – Sportmarken und Sportler*innen

**Version:** Codebuch_A

**Letzte Überarbeitung:** 21.September 2026

**Kurs:** Soziale Netzwerkanalyse SoSe 2026

**Fokus:** Es wird geschaut, von welchen Sportmarken Sportler*innen, die im Zeitraum 2017 bis 2026 für den Laureus-Preis nominiert waren, gesponsert werden.



**Allgemeine Informationen:**

Multi-mode Netzwerk: Sportler*in, Sportart, Marke

Ungerichtet

Ungewichtet 

Ego-Netzwerke ergeben sich bei der Analyse → bestimmte Sportmarke analysieren

Momentaufnahme → also was gerade aktuell ist und wenn sie nicht mehr aktiv sind, der letzte Vertrag



**Knoten Attribute:**

id: 	Die ersten drei Buchstaben des Vornamens und der erste Buchstabe vom Nachname 

z.B. Lebron James = lebj

name: 	Name der Marke 
        Sportart 
        Sportler*innen

sex: 	  1 = weiblich
        2 = männlich

sport: 	Sportart wird mit den ersten vier Buchstaben abgekürzt

z.B. Schwimmen = schw

nationality: Internationale Abkürzung des Landes
z.B. GER

status: 1 = aktiv
        2 = inaktiv

type: 	1 = Sportler*in
        2 = Sportart
        3 = Marke

team: 	1 = ja
        2 = nein



**Kanten Attribute:**

from: Sportler*in

to: Sportart oder Sportmarke

relationship: 	1 = zur Sportart
                2 = zur Sportmarke


**Versionierungsregel:**

Die Versionen des Codebuchs und der Markdowndokumente werden alphabetisch benannt. 

z.B. 	codebuch_A
      codebuch_B
      codebuch_C …


**Kodierregeln:**

Fehlende Werte = NA
