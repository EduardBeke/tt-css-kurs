---
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
marp: true
title: Einführung in CSS
---

## Einführung in CSS

- CSS steht für Cascading Style Sheets.
- Es ist eine Stylesheet-Sprache, die verwendet wird, um das Layout und die Darstellung von HTML-Dokumenten zu gestalten.
- CSS beschreibt, wie HTML-Elemente auf dem Bildschirm, auf Papier oder in anderen Medien angezeigt werden sollen.

---

#### Wie funktioniert CSS?

- CSS wird entweder in den `<head>`-Bereich eines HTML-Dokuments eingebunden oder in einem separaten .css-Dokument gespeichert.
- Es gibt drei Möglichkeiten, CSS zu einem HTML-Dokument hinzuzufügen:
  1. Inline-CSS: Direkt im HTML-Element mittels des `style` Attributs.
  2. Internes CSS: Innerhalb des `<style>`-Tags im `<head>`-Bereich.
  3. Externes CSS: In einer separaten CSS-Datei, die mittels eines `<link>`-Tags eingebunden wird.

---

#### Beispiel: Inline, Intern und Extern

```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>CSS Beispiele</title>
    <!-- Internes CSS -->
    <style>
        body {
            background-color: lightblue;
        }
    </style>
    <!-- Externes CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1 style="color: red;">Hallo Welt!</h1> <!-- Inline CSS -->
    <p>Dies ist ein Absatz.</p>
</body>
</html>
```