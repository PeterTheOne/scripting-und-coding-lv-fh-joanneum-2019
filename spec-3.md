Projektanforderungen 3
======================

Scripting & Coding Projektanforderungen.


javascript
----------

### Vorbereitung
 
 - `script.js` Datei erstellen & einbinden
 - Testen ob es funktioniert (`alert('test');`)
 
 
 - Daten für SVG 1 als array schreiben.
 - Daten für SVG 2 als array schreiben.
 
 
 - SVG 1 kopieren -> SVG 2
 - SVG 2 anpassen: Falls nötig SVG anpassen (Beschriftung etc.).
   - Die Werte (zb. Höhe der Balken) noch gleich lassen!


### Aufgabe 1: Erstelle zwei Listen mit den Werten aus den Arrays.

Gebt mit einer javascript Schleife die Werte vom Array als HTML Liste aus.

HTML:
 - HTML sortiertes oder unsortiertes listen HTML Element anlegen (noch ohne Inhalt).
 - Dem listen Element eine beliebig `id` anlegen.

JS:
 - Das listen HTML Element auswählen.
 - Mit javascript ein listen item Element erstellen.
 - Diesem listen item Element den ersten Wert aus dem array als text setzen.
 - Das listen item Element in das listen Element einfügen.
 - Diese Schritte in einer Schleife für alle array elemente durchführen.
 
 
### Aufgabe 2: SVG 2 Werte per javascript setzen.

Berechnet und setzt die Balken Höhe und y position sie in javascript.

HTML:
 - Gebt jedem balken eine eindeutige ID.
 
Javascript:
 - Nehmt einen ersten Wert aus eurem Daten Array.
 - Rechnet aus diesem Wert die Höhe des ersten Balken aus.
 - Berechnet auch die y position vom Balken rechteck.
 - Selektiert das erste BalkenElement.
 - Setzt die attribute für höhe und y position vom balken.
 - Wiederholt diese Schritte für jeden Balken.
 
 
### Aufgabe 3: Hin- und herschalten zwischen SVGs.

Mit zwei Knöpfen zwischen den SVG grafiken hin- und herschalten.

HTML:
 - Gebt den SVG grafiken eindeutige ids
 - Gebt den buttons eindeutige ids

CSS:
 - versteckt SVG 2
 
JS:
 - Selektiert den zweiten button.
 - Reagiert auf einen button click.
 - Selektiert SVG 1 und SVG 2.
 - Versteckt SVG 1 und zeigt SVG 2.
 
 
 - Macht die gleichen Schritte für den ersten button, 
 versteckt jedoch SVG 2 und zeigt SVG 1.
 

Referenzen
----------

https://developer.mozilla.org/en-US/docs/Web/HTML

https://developer.mozilla.org/en-US/docs/Web/CSS

https://developer.mozilla.org/en-US/docs/Web/JavaScript

### JS einbinden

```
<!doctype html>
<html lang="en">
  <head>
    <!-- ... -->
  </head>
  <body>
    <!-- hiert steht alles andere, script kommt ganz am Ende! -->
  
    <script src="script.js"></script>
  </body>
</html>
```

### Array

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array

### While Schleife

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#while_statement


### HTML Element mit Javascript auswählen

```
var buttonElement = document.querySelector("button"); 
```

https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector


### HTML Attribut setzen mit Javascript

```
buttonElement.setAttribute("name", "helloButton");
```

https://developer.mozilla.org/en-US/docs/Web/API/Element/setAttribute


### HTML Element erschaffen

```
var newDiv = document.createElement("div");
```

https://developer.mozilla.org/en-US/docs/Web/API/Document/createElement

### Text von einem HTML Element setzen

```
var divElement = document.createElement("div");
divElement.textContent = 'Hier steht jetzt ein text';
```

https://developer.mozilla.org/en-US/docs/Web/API/Node/textContent

### HTML Element einfügen

```
var someElement = document.querySelector("#someId"); 
var pElement = document.createElement("p");

someElement.appendChild(pElement);
```

https://developer.mozilla.org/en-US/docs/Web/API/Node/appendChild

### Auf einen Click reagieren

```
buttonElement1.addEventListener("click", function() {
    // was hier steht passiert wenn der button geklickt wird. zb. alert('test');
});
```

https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener

### CSS mit javascript setzen

```
pElement.style.color = "blue";
```

https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/style
