Projektanforderungen 4 - extra
==============================

Scripting & Coding Projektanforderungen.


Abgabe
------

Bis __18. July 23:59__ Projektdateien als zip Datei per E-Mail an 
[peter.grassberger@fh-joanneum.at](mailto:peter.grassberger@fh-joanneum.at), 
Betreff "SuC Abgabe". Kurzes Abgabegespräch online oder in der FH.


Aufgabe
-------

Einen Projektordner anlegen mit mindestens folgenden Dateien:

 - index.html
 - theorie.txt (oder gerne auch .pdf oder anderes Textformat)
 - symbol.svg


Theoriefragen
-------------

[Slides Vorlesung](
https://github.com/PeterTheOne/scripting-und-coding-lv-fh-joanneum-2019/blob/master/Scripting-und-Coding-Slides-2019.pdf)

Beantwortet folgende Fragen:

 1. Was sind Beispiele für Algorithmen im Alltag, 
 abgesehen von digitalen Computerprogrammen?
 Für eines der Beispiele: Aus welchen Einzelschritte besteht der Algorithmus.
 Wann endet der Algorithmus und was ist das Ergebnis?
 In welcher Form ist der Algorithmus festgehalten bzw. wie wird er weiter vermittelt?
 2. Sucht einen online Zeitungsartikel und gebt den Link als Quelle an oder speichert den Artikel. 
 Ab der Artikelüberschrift und bis zum letzten Absatz (nicht die ganze Webseite) welche HTML Elemente kommen im Artikel vor?
 Wofür stehen diese Element bzw. welche Bedeutung geben sie ihrem Inhalt?
 Welche davon haben ein Start-Tag und ein End-Tag, welche haben nur ein Tag?
 HTML Element sind hierarchisch verschachtelt, gibt es ein Element mit einem Kind-Element im Artikel?
 3. Sucht eine Formal mit mindestens zwei Variablen und einem Ergebnis, am besten aus dem Alltag.
 Mit einem Tabellenprogramm: Schreibt die Variablen jeweils in ein eigenes Feld.
 Berechnet das Ergebnis der Formel in einem weiteren Feld.
 Was ist die Formel im Tabellenprogramm?
 4. Verwendet die Gleiche Formel.
 In javascript ( https://jsconsole.com/ ): Legt die Variablen mit den Werten an.
 Eine Variable pro Zeile. Verwendet sprechende englische Variablennamen.
 Rechnet das Ergebnis in einer weiteren Zeile aus und speichert es in einer weiteren Variable.


HTML
----

Nehmt einen Text den ihr zum Beispiel selbst geschrieben habt und fügt
sinnvolle HTML-Elemente ein. Überprüft ob das Dokument validiert ( https://validator.w3.org ) und 
bessert Fehler aus. Speichert es als `index.html`.

HTML Dokument sollte zumindest folgends enthalten:

- HTML Grundgerüst: doctype, html, head, body, meta charset, title (siehe unten)
- Überschrift
- Paragraphen
- Bild
- Link
- Hervorhebung von einem Textabschnitt
- Liste


SVG
---

Sucht euch ein Symbol, zum Beispiel in einer Online Bildersuche. 
Ideen für Symbole: Olympische Ringe, Play Pause Stop, Pacman Geist.
Schreibt in einem Text editor (empfehle Codepen: https://codepen.io/pen/ ) 
dieses Symbol als SVG.
Speicher es als `symbol.svg`.
Beginnt mit dem SVG Grundgrüst, siehe unten.


Referenzen
----------

### HTML

https://developer.mozilla.org/en-US/docs/Web/HTML
https://developer.mozilla.org/en-US/docs/Web/HTML/Element

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>HTML Wiederholung</title>
  </head>
  <body>
    <h1>HTML Wiederholung</h1>

    <!-- Hier können weitere HTML Element stehen. -->
  </body>
</html>
```

### SVG

https://developer.mozilla.org/en-US/docs/Web/SVG
https://developer.mozilla.org/en-US/docs/Web/SVG/Element

```
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
<svg version="1.1" baseProfile="full" xmlns="http://www.w3.org/2000/svg" 
    preserveAspectRatio="xMidYMid meet" viewBox="0 0 300 300">

  <title>Title goes here</title>

  <!-- SVG Elements go here -->
</svg>

```
