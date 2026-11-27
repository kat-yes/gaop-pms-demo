# Patientenportal – Demo

Ein interaktiver Prototyp eines Patientenportals für ein Zentrum für geschlechtsangleichende Chirurgie. Die Demo zeigt den möglichen Ablauf von der Terminanfrage bis zum OP-Termin und macht Statusänderungen zwischen Patient*innen- und Klinikansicht nachvollziehbar.

## Funktionen

- Vierstufiger Behandlungsablauf mit Fortschrittsanzeige:
  1. Terminanfrage für ein Vorgespräch
  2. Auswahl eines Termins für das Erstgespräch
  3. Einreichen von Unterlagen und OP-Freigabe
  4. Auswahl eines OP-Termins
- Klinik-Backoffice-Simulator zum Auslösen von Prüfungen, Rückfragen und Freigaben.
- Beispieldaten, Dokument-Muster und Download von Kalenderdateien zur Veranschaulichung.
- Responsives Layout für unterschiedliche Bildschirmgrößen.

## Demo starten

Das Projekt benötigt keine Installation, keinen Build-Schritt und keine zusätzlichen Abhängigkeiten:

1. [Demo Seite](https://kat-yes.github.io/gaop-pms-demo/gaop-pms-demo.html) in einem aktuellen Webbrowser öffnen.
2. Im ersten Schritt die vorausgefüllten Beispieldaten ansehen oder ändern und die Terminanfrage absenden.
3. Die danach freigeschalteten Schritte über die Fortschrittsanzeige oder die Schaltflächen im jeweiligen Schritt öffnen.
4. Den **Klinik-Backoffice-Simulator** am unteren Bildschirmrand verwenden, um den nächsten Klinikschritt auszulösen. Über seine Schaltflächen lassen sich zum Beispiel eine Prüfung starten, eine Rückfrage simulieren und Unterlagen freigeben.
5. Für den Dokumentenschritt entweder eine Datei auswählen oder **Muster-PDF anhängen** verwenden. Zum Neustart **Demo zurücksetzen** wählen.

## Technischer Hinweis

Die Anwendung ist als einzelne HTML-Datei umgesetzt; HTML, CSS und JavaScript sind darin enthalten. Der Prototyp dient ausschließlich der Demonstration: Es gibt keinen Server und keine echte Speicherung oder Übermittlung. Ausgewählte Dateien werden nicht hochgeladen; die Oberfläche merkt sich lediglich deren Dateinamen im aktuellen Browserzustand. Beim Neuladen der Seite wird der Ausgangszustand mit Beispieldaten wiederhergestellt.

Bitte keine echten persönlichen, medizinischen oder sonstigen vertraulichen Daten verwenden.

## Lizenz

Für dieses Repository gilt die in [license.md](./license.md) beschriebene „All Rights Reserved“-Regelung. Die Einsicht in das Repository erteilt keine Erlaubnis zum Kopieren, Ändern, Verbreiten oder anderweitigen Nutzen der Inhalte. Für Anfragen ist die dort angegebene Rechteinhaberin zu kontaktieren.
