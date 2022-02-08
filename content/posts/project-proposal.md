---
title: "PFLICHTENHEFT"
date: 2022-02-05T17:53:05+01:00
draft: true
---

<!--more-->

### 1.1 Ausgangssituation

Das unabhängige Familienunternehmen namens Ostwind welches
moderne Wind- und Solarparks europaweit projektiert und errichtet
hat Ihre Stammorte in Frankreich und Deutschland verteilt.

In der Vergangenheit haben sie schon 603 Windkraftanlagen mit 1085
Megawatt Leistung geplant, gebaut und ans Netz gebracht. Energiekonsumenten welche
Wert auf ökonomische Energie legen, können sich diesen Wunsch bei Ostwind
erfüllen lassen.

### 1.2 Istzustand

In der Vergangenheit kam es öfters vor, dass durch motivierte
Wanderer die Vegetation verschmutzt und zerstört wurde,
indem sie unmarkierte/unoffizielle Wege nahmen.
Um die Bäume und das Umfeld in solchen Gebieten in Zukunft
zu schützen wird eine Software entwickelt, die als Profit
für die Einwohner wegen des darauffolgenden Tourismus dient.

### 1.3 Problemstellung

Um die Route des zurückgelegten Weges visualisieren zu können, werden die Koordinatenpunkte
der zu bewandernden Pfade bei einer Person der Organisation angefragt.

### 1.4 Aufgabenstellung

* Vorbereitungen
  * Koordinaten beantragen
  * Landkarte vorbereiten mittels erhaltenen Koordinaten
* Dokumentation
  * README.md
  * asciidoctor
  * use-case diagram
  * Datenmodell (ERD)

#### Funktionale Anforderungen

![use-case diagram](https://github.com/htl-leonding-project/primeval-forest-route/raw/main/asciidocs/images/use_case1.png)

#### UML-Diagramm

![uml diagram](https://github.com/htl-leonding-project/primeval-forest-route/raw/main/asciidocs/images/uml.png)

### Ziele

Unterstützung des Umweltschutzes und betroffene Bewohner die davon profitieren.

### Mengengerüst

Es wird eine Wanderschaft veranstaltet, dabei nimmt eine Gruppe von 12 Personen teil.
Wenn jeder Teilnehmer diese App nutzt, werden schlussendlich 12 verschiedene Fotoalben erstellt.

NOTE: Die Nutzung der App kann stark variieren, da möglicherweise nicht alle Personen die Applikation verwenden
die die Route durchqueren.

### Rahmenbedingungen

* Quarkus Backend
* Angular Frontend