# Project Landing Page

Eine moderne, responsive Landing Page mit sauberem Design und CSS-Features.

## 🚀 Features

- **Responsive Design** - Funktioniert auf allen Bildschirmgrößen
- **Moderne CSS-Techniken** - Flexbox, CSS-Variablen, Box-Model
- **Optimierte Typografie** - Roboto Font von Google Fonts
- **Semantisches HTML** - Saubere Struktur und Accessibility
- **SVG-Illustrationen** - Skalierbare Vektorgrafiken

## 🎨 CSS-Elemente & Techniken

### Layout & Flexbox

- **`.flex`** - Flexbox-Container für horizontale Ausrichtung
- **`display: flex`** - Moderne Layout-Technik
- **`justify-content`** - Horizontale Ausrichtung (space-between, center)
- **`align-items`** - Vertikale Ausrichtung (center)
- **`flex-direction: column`** - Vertikale Anordnung in Cards
- **`flex-wrap: wrap`** - Responsive Umbrüche

### CSS-Variablen (Custom Properties)

```css
:root {
  --dark: #1f2937;
  --primary-text: #f9faf8;
  --secondary-text: #e5e7eb;
  --light-blue: #3882f6;
  --tertiary: #e5e7eb;
}
```

### Box-Model & Reset

- **`box-sizing: border-box`** - Moderne Box-Model-Berechnung
- **CSS Reset** - Entfernt Browser-Standards
- **Margin/Padding Reset** - Saubere Basis für alle Elemente

### Typografie

- **Google Fonts Integration** - Roboto Font-Familie
- **Font-Weight Varianten** - 300, 400, 500, 700, 900
- **Responsive Font-Sizes** - 18px, 24px, 36px, 48px
- **Line-Height** - 1.6 für bessere Lesbarkeit

### Komponenten

- **Navigation** - Flexbox-basierte Navigation
- **Hero Section** - Header mit Call-to-Action
- **Cards Grid** - Flexbox-basierte Card-Anordnung
- **Quote Section** - Inspirierender Zitat-Bereich
- **CTA Section** - Call-to-Action mit Button
- **Footer** - Einfacher Footer

## 📁 Projektstruktur

```
project-landing-page/
├── index.html          # Haupt-HTML-Datei
├── styles.css          # CSS-Styles
├── assets/             # Bilder und Assets
│   ├── header-placeholder.svg
│   ├── placeholder1.svg
│   ├── placeholder2.svg
│   ├── placeholder3.svg
│   └── placeholder4.svg
└── README.md           # Diese Datei
```

## 🛠️ Verwendete Technologien

- **HTML5** - Semantische Struktur
- **CSS3** - Moderne Styling-Techniken
- **Flexbox** - Layout-System
- **CSS-Variablen** - Wiederverwendbare Werte
- **Google Fonts** - Web-Typografie
- **SVG** - Vektorgrafiken

## 🎯 CSS-Klassen Übersicht

### Layout-Klassen

- `.flex` - Flexbox-Container
- `.container` - Zentrierte Container mit max-width
- `.cards-container` - Flexbox-Grid für Cards

### Komponenten-Klassen

- `.card` - Einzelne Card-Elemente
- `.hero` - Header-Bereich
- `.quote` - Zitat-Sektion
- `.cta` - Call-to-Action Sektion
- `.dark-bg` - Dunkler Hintergrund

### Utility-Klassen

- `.btn-outline` - Outline-Button-Style
- `.information` - Informations-Sektion

## 📱 Responsive Breakpoints

- **Desktop**: max-width: 1000px
- **Tablet**: Flexbox-wrap aktiviert
- **Mobile**: Responsive Typografie und Layout

## 🎨 Design-System

- **Farbschema**: Dunkle Töne mit blauen Akzenten
- **Typografie**: Roboto Font-Familie
- **Spacing**: Konsistente Abstände (24px, 36px, 100px)
- **Borders**: Abgerundete Ecken (6px, 10px)

## 🔧 Anpassungen

Alle Farben, Größen und Abstände sind als CSS-Variablen definiert und können einfach in der `:root` Sektion geändert werden.

---

**Entwickelt mit ❤️ und modernen CSS-Techniken**
