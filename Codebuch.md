# Codebuch – Sportmarken und Sportler*innen

**Soziale Netzwerkanalyse SoSe 2026**

Codebuch Stand 01.10.26 

## Inhalt 

- edges.csv (Edgelist)
- nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)


## Ursprung und Datenerhebung 

(...)

Es wird geschaut, von welchen Sportmarken Sportler*innen, die im Zeitraum 2017 bis 2026 für den Laureus-Preis nominiert waren, gesponsert werden.



Multi-mode Netzwerk: Sportler*in, Sportart, Marke

Ungerichtet

Ungewichtet

Ego-Netzwerke ergeben sich bei der Analyse → bestimmte Sportmarke analysieren

Momentaufnahme → also was gerade aktuell ist und wenn sie nicht mehr aktiv sind, der letzte Vertrag


# NODE-Attribute

**id** 	

Die ersten drei Buchstaben des Vornamens und der erste Buchstabe vom Nachname 

z.B. Lebron James = lebj


**name**

Name der Marke, Sportart, Sportler*innen


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


**team**

1 = ja

2 = nein


# EDGE-Attribute

**from**

Sportler*in


**to**

Sportart oder Sportmarke


**relationship** 	

1 = zur Sportart              

2 = zur Sportmarke
