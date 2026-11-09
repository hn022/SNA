# Codebuch – Sportmarken und Sportler*innen

**Soziale Netzwerkanalyse SoSe 2026**

Codebuch Stand 09.11.26 

## Inhalt 

- edges.csv (Edgelist)
- nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)


## Ursprung und Datenerhebung 


Der folgende Datensatz wurde anhand der nominierten Sportler und Sportlerinnen des Laureus-Preis (Kategorie: Sportsman of the Year & Sportswoman of the Year) von 2012 - 2026 erhoben. Es wird geschaut von welchen Sportmarken die ausgewählten Personen gesponsert werden.

Bei den erhobenen Daten handelt es sich um eine Momentaufnahme. Das bedeutet, bei aktiven Sportler und Sportlerinnen werden die aktuellen Sportmarken verwendet. Bei inaktiven werden die letzten Verträge benutzt.

Das Netzwerk ist ein *ungerichtetes und ungewichtetes multi-mode Akteursnetzwerk*. Die Akteure des Netzwerks sind: die Sportler*in, die Sportarten, die unterschiedlichen Marken und die Herkunftsländer der Sportlerinnen und Sportler.


# NODE-Attribute

**id** 	

Die ersten drei Buchstaben des Vornamens und der erste Buchstabe vom Nachname der Sportler*innen

z.B. Lebron James = lebj


**name**

Name der Marke, Sportart, Sportler*innen oder des Landes


**sex**

1 = weiblich

2 = männlich


**sport**

Sportart wird mit vier Buchstaben abgekürzt

z.B. Schwimmen = schw


**nationality**

Internationale Abkürzung des Landes

z.B. GER


**status**

1 = aktiv

2 = inaktiv


**type**

1 = Sportler*in

2 = Sportart

3 = Marke

4 = Land


**team**

1 = ja

2 = nein


**nominations**

Anzahl der Nominierungen


**winner**

1 = ja 

2 = nein


# EDGE-Attribute

**from**

Sportler*in


**to**

Sportart, Sportmarke oder Land


**relationship** 	

1 = zur Sportart              

2 = zur Sportmarke

3 = zum Land
