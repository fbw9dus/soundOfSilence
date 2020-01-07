
# The Sound of Silence 

Mach eine Vorschau für's Suchergebnis mit den Daten in `music.js` (schon verfügbar in der `music`-Variablen)

Für jedes Lied sollte angezeigt werden:
- Stück name
- Künstler name
- Bild
- Erscheinungsdatum
- Preis und Währung

## 2. Aufgabe
- Füg oben neben **Songs** ein Suchfeld ein
- Wenn der Nutzer etwas eingibt, sollen unten nur die Ergebnisse angezeigt werden, die zur Suche passen
- Ein Eintrag soll nur angezeigt werden, wenn der String aus dem Suchfeld im Titel des Lieds oder im Künstlernamen enthalten ist

## 2. Aufgabe
- Bau die App um, so dass die Ergebnisse nicht aus `music.js` geladen werden sondern von der (iTunes-API)[https://affiliate.itunes.apple.com/resources/documentation/itunes-store-web-service-search-api/]
- Da diese API wegen CORS nicht mit Fetch benutzt werden kann, nutze die jQuery-Methode `getJSON`, die JSONP unterstützt, um die Suchergebnisse abzufragen.
- Die URL für die Abfrage mit jQuery ist `https://itunes.apple.com/search?term=jack+johnson&callback=?`
- Zugriffe auf diese API sind auf etwa 20 pro Minute begrenzt.

- Die Seite sollte so aufgebaut sein, muss aber nicht genau so aussehen:

![preview](./assets/img/preview.png)
