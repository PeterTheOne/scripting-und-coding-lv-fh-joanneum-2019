Projektanforderungen 2
======================

Scripting & Coding Projektanforderungen.


svg
---
Balkendiagramm oder nach Rücksprache andere Visualisierung.

 - __*Eine*__ von zwei SVG Grafiken schreiben (codepen)
   - Mit den Werten vom ersten Datensatz
 - Zuerst auf Papier planen:
   - Was sind die höchsten und niedrigsten Werte im Diagramm?
   - Wieviele Balken gibt es? Wie breit ist ein Balken? Abstände dazwischen?
 - Rechnen:
   - Wie komme ich von einem Datenpunkt auf eine Koordinate?
   - Gibt es dafür eine Formel. Welche?
 - x und y Achsen mit Werten/Beschriftungen
 - Sichtbare Überschrift oben
 - `title` und `desc` im SVG
 - SVG inline einfügen ins HTML
 - SVG id festlegen
 - Einzelne Balken mit eindeutigen ids benennen


Referenzen
----------

https://developer.mozilla.org/en-US/docs/Web/SVG


```
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
<svg version="1.1" baseProfile="full" xmlns="http://www.w3.org/2000/svg" 
    preserveAspectRatio="xMidYMid meet" viewBox="0 0 300 300">

  <title>Title goes here</title>

  <!-- SVG Elements go here -->
</svg>

```
