# Datensatz Pretest Indie-Kollaborationen #
Codebuch Stand 2021-29-01   
erstellt von Gruppe Indie (ss502@hdm-stuttgart.de)

**Titel des Netzwerks:**
Kollaborationen Indie

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.rm (Codierung der Datensätze)

## Ursprung und Datenerhebung

Es werden Kollaborationen vom 01.01.2015 bis 31.12.2020 erfasst.

Das Netzwerk ist ein *ungerichtetes one-mode Akteursnetzwerk*.

# EDGE-Attribute

**id**  
(eindeutige Codierung des Knoten)   
codiert nach den ersten vier Buchstaben der Künstler_innen und Bands, jede ID entspricht einer Künster_in oder Band

**weight**  
Beziehungsstärke   
4 = Feature (Gemeinsamer Song)  
3 = Gemeinsam auf Tour / gemeinsame Auftritte  
2 = gemeinsames Musiklabel  
1 = Auf dem selben Festival  

**year**
Jahreszahl der Kooperation als YYYY

# NODE-Attribute  
  
**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten

**Name**  
Name der Band

**Anzahl Personen**  
Anzahl der Bandmitglieder

**Musiklabel**  
Aktuelles und frühere Musiklabel der Band oder der Künster_in

**Instagram-Follower**  
Anzahl der Instagram-Follower_innen zum Stichtag 07.03.2021 in Tausenden

**Hörer auf Spotify**  
Monatliche Hörer_innen auf Spotify zum Stichtag 07.03.2021 in Tausenden

##

