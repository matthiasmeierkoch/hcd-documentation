---
layout: page
title: HiFi Design
parent: Design
permalink: /Design/HiFi-Design
nav_order: 4
---

## Inhaltsverzeichnis
{: .no_toc .text-delta }

1. TOC
{:toc}


## HiFi Prototyp
– zuerst LoFi Prototyp fertigstellen und parallel die wichtigsten Screens designen
– HiFI Prototyp eignet sich gut um in Meeting mit Kunden über Visual Design zu sprechen. Dies sollte aber im LoFi Prototyp vermieden werden.
– Zweck des Prototyps soll im Vorfeld abgeklärt werden
– Passendes Werkzeug auswählen
– Kurze Iterationen mit Feedback



### Namesfindung
* mirrorme
* circles
* easysteps
* first steps
* reflect
* progress
* closedcircles
* bocado = Häppchen auf Spanisch

bocado it is!

### Designsysteme
* Grids oft im goldenen Schnitt, z.B. Facebook
* Ausrichtung von Elementen zueinander
* Animation soll Fluss von Elementen zeigen, also wie sich das Element entwickelt
* Overlays haben sich im Desktop etabliert, auf Mobile ist ein neuer Screen üblicher
* Die wichtigsten Aktionen sind im Fokus
* Progressbars haben eine gute Userführung
* Kachelsystem wirkt aufgeräumt und responsive

### Prototypen
Low-Fi: https://www.figma.com/file/TN06iGxN3xCVXq66bDeWGXct/Protoyp-%C2%ABfirst-steps%C2%BB-VERSION-1?node-id=0%3A1

Low-Fi nach Usability Walkthrough:
https://www.figma.com/file/XLBaCqPOEOmFO4ujsdx43j/Protoyp-%C2%ABfirst-steps%C2%BB-VERSION-2?node-id=0%3A1

Hi-Fi:
https://www.figma.com/file/GN1f3SvmzTkia4DAZaBix0/Protoyp-HIFI-%C2%ABfirst-steps%C2%BB?node-id=0%3A1

### Erkenntnisse Low-fi für HiFi Prototyp

**geringes Problem**
* Hinzufügen von Modul durch User -> Hugo Hybrid fügt nur die Module hinzu, die er auch möchte
* Auswahl aus Pool

**ernsthaftes Problem**
* Onboarding wichtig
* Wie viel Module können angezeigt werden? -> Wir setzen Grenzen: Bis 10 Module möglich
* Unsere Kreise schliessen Funktion ist nicht mehr attraktiv mit mehr als 10 Farben

**kritisches Problem**
* Zu viele Farben als Feedback bei Fragen

### Dritter Test

#### Angaben zur Testperson 3
{: .no_toc }
Beruf: Informatiker
Alter: 23
Geschlecht: Männlich
Benutzung/Erfahrung von Apps/Portalen zum Thema Lernen: Ja, mit Quizlet

#### Fragen
{: .no_toc }
**Wir haben zwei Usecases.**
1. **Per Push Notification:**
* Klicke dich zur ersten Frage.
* Beantworte eine Frage. Für den Flow gehen wir davon aus, dass du 4 von 5 Fragen richtig beantwortet hast

2. **direkter Eingang in App auf Startseite:**
* Wie sieht deine Statistik für das Modul St.Galler Management aus?
* Repetiere das Modul. 
**Beobachtung:
* Will swipen wegen Punkten in Onboarding
* Würde den Text nicht lesen
* "+" auf Übersicht: Eventuell neue Module hinzufügen?
* 4 / 5 Fragen richtig beantwortet, nicht aufs ganze Modul bezogen

3. **Wegfindung**
* Gehe auf die Übersicht wo die Module aufgelistet sind.
Zeige mir dein Level.
**Beobachtung:**
* Level nicht klar weil keine Nummer
* Icon fällt sofort auf
* Hielt Daystreak für Level
* "Trophies" brauchen einen Titel
* Kann Levels nicht mit anderen vergleichen (Da keine Klare Reihenfolge welches Level ist wie Hoch)
* Daystreak fällt aus Rahmen weil Nummer und kein Icon
* Unerreichte Achievements sollten versteckt sein
* X direkt auf Übersichtsseite in Achievements (wird erwartet)
* Unerreichte Achievements (on Tap) anzeigen was ich machen muss um diese zu erreichen.

4. **von Übersichtsscreen:**
* Hast du offene Benachrichtigungen?
* Schaue sie dir an.
Beobachtung:
* Sieht direkt wieviele Benachrichtigungen er hat
* Denkt er würde direkt in Frage hinein springen

#### Fragebogen - Post Session Interview
{: .no_toc }
**Antworten**
Was war positiv?
* Sehr clean und aufgeräumt
* kommt mit wenig aus
* Menü wird als "recht cool" empfunden

Was war negativ?
* Teilweise zu wenig
* Kreise auf Übersicht nicht klar genug
* Icon von Level/Achievmentseite nicht intuitiv
* 
Was hat ihnen gefehlt?
* Module müssem auch löschbar sein
* Kreis von «international management» ist nicht gleich wie in der Modul übersichtsseite.
* da das menu nur bei «home» kommt müssen die Kreise nicht nochmals da sein. 


Was haben Sie für einen Gesamteindruck dieser App?
* Funktioniert, hätte Lust es einzusetzen
* Handling intuitiv
* Kommt schnell auf Fragen
* Usecase macht Sinn


#### SUS Fragebogen Severin
{: .no_toc }
Bei ungraden Fragen jeweils Antwort - 1.
Bei graden Fragen jeweils 5(max Punkte)-Antwort.
1. Ich kann mir sehr gut vorstellen, das System regelmäßig zu nutzen. 4 > 3

2. Ich empfinde das System als unnötig komplex. 1 > 4

3. Ich empfinde das System als einfach zu nutzen. 4 > 3

4. Ich denke, dass ich technischen Support brauchen würde, um das System zu nutzen. 1 > 4

5. Ich finde, dass die verschiedenen Funktionen des Systems gut integriert sind. 5 > 4

6. Ich finde, dass es im System zu viele Inkonsistenzen gibt. 2 > 3


7. Ich kann mir vorstellen, dass die meisten Leute das System schnell zu beherrschen lernen. 5 > 4


8. Ich empfinde die Bedienung als sehr umständlich. 2 > 3

9. Ich habe mich bei der Nutzung des Systems sehr sicher gefühlt. 5 > 4


10. Ich musste eine Menge Dinge lernen, bevor ich mit dem System arbeiten konnte. 2 > 3

Punktzahl Total: 35 * 2,5 = 87,5 

#### Emotional Cards Sevi
{: .no_toc }
Konsistent: Farkonzept ein Guss, abgerundet, Notifications könnte noch optimiert werden
Time-saving: man kommt sehr schnell auf Fragen direkt auf Notification
Attraktiv: einfaches Design sehr verständlich
* Achievements müsste man nochmals anschauen
* Gamification hat ihn nicht interessiert, Level waren nicht klar

## SUS Summary

Unser UI hat einen hohen Score von 87,5 Punkten erreicht.

### Grösstes Usability-Problem:
Zusatzinhalte der App, wie Übersicht und Achievements waren nicht intuitiv genug.

### Drei grösste Probleme und mögliche Lösungen:
* Die Level wurden nicht klar erkannt und der Vergleich mit Mitschülern war schwierig.
--  Lösung --> Level rauswerfen, mit klar definierten Achievements ersetzen
* Die Gamification-Aspekte wurden nicht als interessant empfunden weil alle Achievements schon ersichtlich waren. Das Icon war sichtbar, war aber nur ausgegraut
--  Lösung --> Ausgegraute, inaktive Achievements mit Vorhängeschlössern ersetzen. Wie man sie freischaltet kann durch antappen erfahren werden
* Wenn man sich für ein Modul nicht interessiert kann man es nicht löschen
--  Lösung --> Lösch-Button in Modulübersicht hinzufügen


## Endpräsentation
https://docs.google.com/presentation/d/1v9pAsEaABr0mIPf5lBNuAdv2XF_QURejRmAxMGsrhiU/edit#slide=id.g55425726d1_2_168

**Präsentation Feedback:**
* Alle Benutzergruppen erwähnen: Lehrerseite der Plattform kurz anskizzieren
* Learnings vom Modul
* Mehr verbindung zu Bocado ( häppchenweise ) es wäre schön gewesen wenn beim wording mehr darauf eingegangen wurde
* mehr Enthusiasmus beim präsentieren
* Farben der Module wurden als Signalfarben verstanden
* Positiv war dass wir Challenge und Vision miteinbezogen haben
* Vision war schon zu sehr als Lösung formuliert

Zum Endprodukt:

[Bocado](https://matthiasmeierkoch.github.io/hcd-documentation/Endprodukt/){: .btn }
