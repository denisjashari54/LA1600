
# Projekt-Dokumentation



Apple: Nuriswat, Jesenko, Jashari

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

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
| 5    |Muss             |Funktional|Als User möchte ich eine Such leiste, damit ich nach einem bestimmten Game direkt suchen kann und es schneller finde.|
| 6    |Muss             |Funktional|Als User möchte ich, dass unsere Website über funktionierende Verlinkungen verfügt.|
| 7    |Muss             |Funktional|Als User möchte ich im Header einen Bild und eine Navigationsleiste einbauen.|
| 8    |Muss             |Funktional|Als User möchte ich im Footer Kontakt und anderen Verlinkungen (z.B Impressum) anfügen.|
| 9    |Muss             |Qualität|Als User möchte ich Hovereffekte für Buttons und eventuell Textabschnitte implementieren.|
| 10   |Muss             |Qualität|Als User möchte ich, dass unsere Website responsive für die Desktopversion ist.|
| 11   |Kann             |Qualität|Als User möchte ich, dass unsere Website responsove für das Smartphone ist.|
| 12   |Muss             |Funktional|Als User möchte ich, dass sich die Container nicht überlappen.|




✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

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
| 4.2  |Filter menü ist offen|User wählt Filter Genre Action|Webseite wird nach Action gefilltert|
| 6.1  |Webseite ist offen| User drückt auf Link| Verlinktes Objekt öffnet sich.|
| 7.1  |Wenseite ist offen| - | Im Header sind ein Bild und eine Navigationsleiste|
| 8.1  |Webseite ist offen| - | Im Footer sind Verlinkungen die z.B zu einem Impressum führen.|
| 9.1  |Webseite ist offen| User Hovert über Button| Hovereffekt|
|10.1  |Webseite ist offen| - |Webseite ist für den Desktop Responsiv|
|11.1  |Webseite ist offen| - |Webseite ist für das Smartphone Responsiv|
|12.1  |Webseite ist offen| - |Container überlappen nicht.|
✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme
![543b4711-997f-4bcc-a9d5-4e088274c43c](https://user-images.githubusercontent.com/110892250/237024444-c7267a5b-140e-4ab0-b502-b86de9b3f6e5.jpg)
![usecaseDiagramm_LA1600 drawio](https://user-images.githubusercontent.com/110892637/237026835-1fbec158-235a-4edd-a142-d45273f59935.png)

✍️Fügen Sie hier ein Use Case-Diagramm mit mindestens 3 Anwendungsfällen ein; und eine Skizze davon, wie Ihre Netzseite aussehen sollte45min|.

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


Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
