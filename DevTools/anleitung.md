## Anleitung für die Verwendung der DevTools

### 1. Einführung in DevTools

DevTools sind integrierte Entwicklungswerkzeuge in modernen Browsern (wie Chrome, Firefox und Edge), die Entwicklern helfen, Webseiten zu inspizieren, zu debuggen und zu optimieren.

### 2. Zugriff auf DevTools

**Schritt-für-Schritt-Anleitung:**

1. Öffne deinen Browser (z.B. Google Chrome).
2. Gehe zu der Webseite, die du inspizieren möchtest (in diesem Fall die Datei `index.html`).
3. Rechtsklick auf die Seite und wähle "Untersuchen" oder drücke die Taste F12 auf deiner Tastatur.

### 3. Elemente untersuchen

#### HTML-Struktur ansehen:

1. Klicke in den DevTools auf das "Element auswählen"-Symbol (Mauszeiger-Symbol).
2. Bewege den Mauszeiger über verschiedene Teile der Webseite. Der entsprechende HTML-Code wird hervorgehoben.
3. Klicke auf ein Element, um dessen HTML-Code im "Elements"-Tab zu sehen.

#### CSS-Stile anzeigen:

1. Im rechten Bereich der DevTools siehst du die angewendeten CSS-Stile für das ausgewählte Element.
2. Der "Styles"-Bereich zeigt die CSS-Regeln, die auf das Element angewendet werden.

#### Stile live bearbeiten:

1. Wähle ein Element aus (z.B. ein `<div class="flex-item">`).
2. Im "Styles"-Bereich kannst du CSS-Eigenschaften direkt bearbeiten. Ändere z.B. die Hintergrundfarbe von `background: #333;` zu `background: #ff0000;`.
3. Beobachte die sofortigen Änderungen auf der Webseite.

### 4. CSS-Box-Modell

#### Box-Modell anzeigen:

1. Wähle ein Element aus (z.B. ein `<div class="flex-item">`).
2. Im "Styles"-Bereich siehst du das Box-Modell, das die Abmessungen des Elements zeigt (Content, Padding, Border, Margin).

#### Element-Abmessungen:

1. Im Box-Modell kannst du die Größe und Position des Elements überprüfen.
2. Fahre mit der Maus über die verschiedenen Bereiche des Box-Modells, um die entsprechenden Abmessungen auf der Webseite hervorgehoben zu sehen.

#### Layout: Margins ändern:

1. Wähle ein Element aus (z.B. ein `<div class="flex-item">`).
2. Im "Styles"-Bereich ändere die Margin-Werte, z.B. `margin: 0.5rem;` zu `margin: 1rem;`.
3. Beobachte, wie sich das Layout des Elements verändert.

### 5. CSS-Regeln

#### Neue Regeln hinzufügen:

1. Wähle ein Element aus.
2. Im "Styles"-Bereich klicke auf das Plus-Symbol (+), um eine neue CSS-Regel hinzuzufügen.
3. Füge z.B. `border: 2px solid red;` hinzu und sieh die sofortige Auswirkung.

#### Regeln deaktivieren:

1. Wähle ein Element aus.
2. Im "Styles"-Bereich kannst du eine CSS-Regel deaktivieren, indem du das Häkchen neben der Regel entfernst.
3. Beobachte, wie sich das Design ohne diese Regel verändert.

### 6. Responsives Design

#### Responsive Design Mode:

1. Öffne den responsiven Design-Modus, indem du in den DevTools auf das "Toggle device toolbar"-Symbol (oder Strg+Shift+M) klickst.
2. Wähle verschiedene Gerätetypen (z.B. iPhone, iPad) und Auflösungen aus dem Dropdown-Menü aus.

#### Media Queries testen:

1. Im responsiven Design-Modus kannst du die Ansicht auf verschiedene Bildschirmgrößen anpassen.
2. Beobachte, wie Media Queries auf die Darstellung der Webseite reagieren.
