---
title: Ausfall des BananaDrive-Servers
date: 2025-03-24 11:00:00
resolved: true
# Mögliche Schweregrade: down, disrupted, notice
severity: disrupted
affected:
  - BananaDrive
section: issue
---

---

*Update 3*
Jetzt wird geschaut wie das System bei einer sehr hohen Anzahl von Scans läuft. Es wurde aber mittlerweile vermutlich eine gute Einstellung insbesondere für den Cache gefunden. Generell sollten also keine Probleme oder Anpassungen mehr vorkommen.

*Update 2*
Ok, also auf dem Medienserver gab es tatsächlich einen Fehler mit Autoscan, war nicht korrekt aktiv, somit wurden Filme zwar gelöscht aber nicht wieder korrekt hinzugefügt und waren dann als nicht verfügbar.
Das wurde jetzt behoben! Autoscan läuft jetzt vermutlich zuverlässig. Lag an falscher Portweiterleitung.
Heute früh um 9 wurde nochmal etwas an den Medien gemacht und daher war zeitweise gar nichts abspielbar, denn normalerweise hätte ein Restart das Problem behoben, scheinbar hat aber ein Skript nicht alles korrekt neugestartet.

*Update*
Laut den Server-Logs war der Server zu den problematischen Zeitpunkten nicht offline. Es muss also eine andere Ursache geben wieso der Server zu bestimmten Zeiten nicht erreichbar ist.

*Untersuchung*
Ich bin mir eines Problems bewusst, dass es vereinzelt Probleme mit dem Online-Status vom Plex-Server gibt. Das Problem konnte noch nicht lokalisiert werden und es werden bereits einige Tests durchgeführt.
