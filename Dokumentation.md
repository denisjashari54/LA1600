# Projekt-Dokumentation



Apple: Nuriswat, Jesenko, Jashari

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|09.05.2023| 0.0.1|Wir haben eine erste Test Website erstellt und unser Projekt geplant.|
|16.05.2023| 0.3.0|Wir haben jetzt an unseren drei individuellen Unterseiten gearbeitet und von diesen erste versionen erstellt.|
|23.05.2023| 0.5.0|Wir haben einen Prototyp von unseren Unterseiten fertiggestellt, es hat aber nicht geklappt diese Seiten miteinander zu verlinken. Es hat auch noch nicht geklappt den Filter hinzuzufügen.|
|30.05.2023| 1.0.0| Eine erste Version unserer Werbseite ist jetzt fertig, aber es gibt noch funktionen wie der Filter die noch nicht ganz funktionieren.|
|06.06.2023|1.1.0|Wir haben das Aussehen unserer Webseite noch etwas verbessert und die Filter funktion funktioniert jetzt.|
|13.06.2023|1.1.1|Wir haben eine Kurze Presentation über Hover Effekte gemacht und Bugs gefixt.|
|20.06.2023|1.1.1|Wir haben Heute unsere Präsentation gemacht.|
|27.06.2023|1.1.1|Heute haben wir unseren Lernbericht geschrieben.|


## 1 Informieren

### 1.1 Ihr Projekt

Wir machen eine Webseite, in der die neusten News über Games stehen.

In unserem Projekt werden wir eine Webseite machen, mit News über Games, die neu erscheinen, welche Games gerade beliebt sind und was es für interessante unbekannte Games gibt. Diese Seite werden wir mit HTML und CSS machen.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 0    |Rand             |Funktional| Als Programmierer machen ich die Seite nur mit HTML und CSS, damit ich das besser lernen kann.|
| 1    |Muss             |Funktional|Als User möchte ich, das mir auf der Webseite neue Games angezeigt werden, damit ich immer die neusten Games kenne.|
| 2    |Muss             |Funktional|Als User möchte ich, dass mir auf der Webseite beliebte Games angezeigt werden, damit ich über die beliebtesten Spiele informiert bin.|
| 3    |Muss             |Funktional|Als User möchte ich, dass mir auf der Webseite interessante Games angezeigt werden, die eher unbeliebt sind, damit ich vielleicht ein neues Game finde, dass mir Spass macht|
| 4    |Kann             |Qualität|Als User möchte ich eine Filter funktion haben, damit ich meine Suche nach z.B. Genre eingrenzen kann.|
| 6    |Muss             |Funktional|Als User möchte ich, dass unsere Website über funktionierende Verlinkungen verfügt.|
| 7    |Muss             |Funktional|Als User möchte ich im Header einen Bild und eine Navigationsleiste einbauen.|
| 8    |Muss             |Funktional|Als User möchte ich im Footer Kontakt und anderen Verlinkungen (z.B Impressum) anfügen.|
| 9    |Muss             |Qualität|Als User möchte ich Hovereffekte für Buttons und eventuell Textabschnitte implementieren.|
| 10   |Muss             |Qualität|Als User möchte ich, dass unsere Website responsive für die Desktopversion ist.|
| 11   |Kann             |Qualität|Als User möchte ich, dass unsere Website responsive für das Smartphone ist.|
| 12   |Muss             |Funktional|Als User möchte ich, dass sich die Container nicht überlappen.|


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |Webseite wurde aufgerufen|Unterseite beliebte Games angeklickt|Unterseite Beliebte Games.|
| 1.2  |Unterseite beliebte Games ist offen| - | eine Liste mit beliebten Games wird angezeigt.|
| 1.3  |Unterseite beliebte Games ist offen| - | die Unterseite beliebte Games hat ein schönes Design das mit CSS gemacht wurde.|
| 2.1  |Unterseite neue Games wurde aufegerufen|Unterseite neue Games angeklickt|Unterseite neue Games.|
| 2.2  |Unterseite neue Games ist offen| - |eine Liste mit neuen Games wird angezeigt.|
| 2.3  |Unterseite neue Games ist offen| - |die Unterseite neue Games hat ein schönes Design das mit CSS gemacht wurde.|
| 3.1  |Unterseite interessante unbekannte Games wurde aufegerufen|Unterseite interessante unbekannte Games angeklickt|Unterseite interessante unbekannte Games.|
| 3.2  |Unterseite interessante unbekannte Games ist offen| - |eine Liste mit interessanten unbekannten Games wird angezeigt.|
| 3.3  |Unterseite interessante unbekannte Games ist offen| - |die Unterseite interessante unbekannte Games hat ein schönes Design das mit CSS gemacht wurde.|
| 4.1  |User drückt auf Filter funktion.| - |Filter menü öffnet sich|
| 4.2  |Filter menü ist offen|User wählt Filter Multyplayer|Es werden nurnoch Multyplayer Games angezeigt.|
| 4.3  |Fliter menü ist offen|User wählt Filter Singleplayer|Es werden nunoch Singleplayer Games angezeigt.|
| 6.1  |Webseite ist offen| User drückt auf Link| Verlinktes Objekt öffnet sich.|
| 7.1  |Webseite ist offen| - | Im Header sind ein Bild und eine Navigationsleiste|
| 8.1  |Webseite ist offen| - | Im Footer sind Verlinkungen die z.B zu einem Impressum führen.|
| 9.1  |Webseite ist offen| User Hovert über Button| Hovereffekt|
|10.1  |Webseite ist offen| - |Webseite ist für den Desktop Responsiv|
|11.1  |Webseite ist offen| - |Webseite ist für das Smartphone Responsiv|
|12.1  |Webseite ist offen| - |Container überlappen nicht.|


### 1.4 Diagramme
![543b4711-997f-4bcc-a9d5-4e088274c43c](https://user-images.githubusercontent.com/110892250/237024444-c7267a5b-140e-4ab0-b502-b86de9b3f6e5.jpg)
![usecaseDiagramm_LA1600 drawio](https://user-images.githubusercontent.com/110892637/237026835-1fbec158-235a-4edd-a142-d45273f59935.png)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |16.05.2023|Jashari|Eine Unterseite auf der beliebte Games gezeigt werden erstellen|45min|
| 1.B  |16.05.2023|Jashari|Die Unterseite beliebte Games zeigt eine Liste von beliebten Games an.|45min|
| 1.C  |23.05.2023|Jashari|Die Unterseite beliebte Games mit CSS Designen.|90min|
| 2.A  |16.05.2023|Jesenko|Eine Unterseite auf der neue Games gezeigt werden erstellen.|45min|
| 2.B  |16.05.2023|Jesenko|Die Unterseite neue Games zeigt eine Liste von neuen Games an.|45min|
| 2.C  |23.05.2023|Jesenko|Die Unterseite neue Games mit CSS Designen.|90min|
| 3.A  |16.05.2023|Nuriswat|Eine Unterseite auf der interessante unbekannte Games gezeigt werden erstellen.|45min|
| 3.B  |16.05.2023|Nuriswat|Die Unterseite interessante unbekannte Games zeigt eine Liste von interessanten unbekannten Games an.|45min|
| 3.C  |23.05.2023|Nuriswat|Die Unterseite interessante unbekannte Games mit CSS Designen.|90min|
| 4.A  |16.05.2023|Jesenko|User kann nach z.B. Genres Filtern.|90min|
| 6.A  |16.05.2023|Jashari|Webseite hat funktionierende Verlinkungen.|90min|
| 7.A  |16.05.2023|Nuriswat|Navigationsleiste im Header.|45min|
| 7.B  |16.05.2023|Nuriswat|Bild im Header.|45min|
| 8.A  |23.05.2023|Jesenko|Impressum im Footer hinzugefügt.|45min|
| 8.B  |23.05.2023|Jesenko|Verlinkungen im Footer hinzugefügt.|45min|



## 3 Entscheiden

Wir haben uns dazu entschieden die Weibseite mit drei websites zu gestallten.
Für die Farben haben wir uns noch nicht festgelegt aber vorerst haben wir ein blau schwarzes design.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |16.05.2023|Jashari|45min|30min|
| 1.B  |16.05.2023|Jashari|45min|45min|
| 1.C  |16.05.2023|Jashari|90min|90min|
| 2.A  |16.05.2023|Jesenko|45min|30min|
| 2.B  |16.05.2023|Jesenko|45min|60min|
| 2.C  |16.05.2023|Jesenko|90min|120min|
|3.A|16.05.2023|Nursiwat|45min|70min|
| 3.B  |16.05.2023|Nuriswat|45min|50min|
| 3.C  |16.05.2023|Nuriswat|90min|120min|
| 4.A  |06.06.2023|Jesenko|90min|180min|
| 6.A  |06.06.2023|Jashari|90mi|30min|



## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |19.06.2023|OK|Jesenko|
| 1.2  |19.06.2023|OK|Jesenko|
| 1.3  |19.06.2023|OK|Jesenko|
| 2.1  |19.06.2023|OK|Jesenko|
| 2.2  |19.06.2023|OK|Jesenko|
| 2.3  |19.06.2023|OK|Jesenko|
| 3.1  |19.06.2023|OK|Jesenko|
| 3.2  |19.06.2023|OK|Jesenko|
| 3.3  |19.06.2023|OK|Jesenko|
| 4.1  |19.06.2023|NOK|Jesenko|
| 4.2  |19.06.2023|OK|Jesenko|
| 4.3  |19.06.2023|OK|Jesenko|
| 6.1  |19.06.2023|OK|Jesenko|
| 7.1  |19.06.2023|OK|Jesenko|
| 8.1  |19.06.2023|NOK|Jesenko|
| 9.1  |19.06.2023|OK|Jesenko|
|10.1  |19.06.2023|OK|Jesenko|
|11.1  |19.06.2023|OK|Jesenko|
|12.1  |19.06.2023|OK|Jesenko|

Wir haben Nr. 4.1 nicht gemacht, weil wir kein Filter menü gemacht haben, unsere Filter sind direkt erreichbar.
Wir hatten keine Zeit ein Impressun zu erstellen deswegen hat der "Über Uns" Button keine Funktion.


## 6 Auswerten
Hier ist unser ![Lernbericht](https://github.com/denisjashari54/LA1600/blob/main/Lernbericht.md)
