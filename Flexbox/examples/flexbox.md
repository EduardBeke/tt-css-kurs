---
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
marp: true
title: Einführung in CSS
---

#### Einführung in Flexbox

- Flexbox ist ein CSS3-Layout-Modul, das flexible Layouts ermöglicht.
- Entwickelt, um Layout-Probleme in CSS zu lösen, die mit traditionellen Methoden wie Floats und Positionierung schwierig umzusetzen waren.
- Erleichtert die Verteilung von Platz und die Ausrichtung von Elementen innerhalb eines Containers.

---

#### Grundlegende Konzepte

- **Flex Container**: Das übergeordnete Element mit `display: flex`.
- **Flex Items**: Die direkten Kinder des Flex Containers.
- **Hauptachse und Querachse**: Flexbox richtet Elemente entlang der Hauptachse (standardmäßig horizontal) und der Querachse (standardmäßig vertikal) aus.

---

#### Vorteile

- **Einfaches Layout**: Flexbox vereinfacht die Erstellung komplexer Layouts.
- **Flexibilität**: Flex-Items passen sich automatisch an verschiedene Bildschirmgrößen an.
- **Ausrichtung**: Einfachere vertikale und horizontale Ausrichtung von Elementen.
- **Verteilung**: Gleichmäßige Verteilung von Platz zwischen Flex-Items.
- **Ordnung**: Flex-Items können einfach umgeordnet werden.

---

#### Nachteile

- **Komplexität**: Bei sehr komplexen Layouts kann Flexbox schwer zu handhaben sein.
- **Browser-Kompatibilität**: Ältere Browser unterstützen Flexbox möglicherweise nicht vollständig.
- **Lernkurve**: Neueinsteiger müssen sich mit neuen Konzepten und Eigenschaften vertraut machen.

---

#### Beispiel: Flexbox Layout

```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Beispiel</title>
    <style>
        .flex-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 200px;
            background-color: #f0f0f0;
        }
        .flex-item {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            margin: 10px;
        }
    </style>
</head>
<body>
    <div class="flex-container">
        <div class="flex-item">Item 1</div>
        <div class="flex-item">Item 2</div>
        <div class="flex-item">Item 3</div>
    </div>
</body>
</html>
```