# 🚀 Deine erste Website - Ganz einfach erklärt!

Willkommen! Hier lernst du, wie du deine eigene Website baust.
Es ist einfacher als du denkst! 😊

---

## 📖 Was ist HTML und CSS?

**HTML** = Der Inhalt deiner Website (Text, Bilder, Links)
- Wie die Wände und Möbel in einem Haus

**CSS** = Das Design deiner Website (Farben, Grössen, Abstände)
- Wie die Farbe an den Wänden und die Dekoration

---

## 🏗️ HTML Tags

### Überschriften

```html
<h1>Grosse Überschrift</h1>
<h2>Mittlere Überschrift</h2>
<h3>Kleine Überschrift</h3>
```

💡 Benutze `<h1>` nur einmal pro Seite für den Haupttitel!

---

### Text

```html
<p>Das ist ein normaler Textabsatz.</p>
<strong>Fetter Text</strong>
<em>Kursiver Text</em>
```

---

### Links

```html
<a href="seite2.html">Link zu Seite 2</a>
<a href="https://google.com">Link zu Google</a>
```

📌 `href` = wohin der Link geht

---

### Bilder

```html
<img src="bild.jpg" alt="Beschreibung">
<img src="https://via.placeholder.com/300" alt="Platzhalter">
```

📌 `src` = wo das Bild ist | `alt` = Beschreibung

💡 **Kostenlose Bilder:** unsplash.com, pexels.com

---

### Listen

**Mit Punkten:**
```html
<ul>
  <li>Erster Punkt</li>
  <li>Zweiter Punkt</li>
  <li>Dritter Punkt</li>
</ul>
```

**Mit Zahlen:**
```html
<ol>
  <li>Erster Punkt</li>
  <li>Zweiter Punkt</li>
</ol>
```

---

### Navigation

```html
<nav>
  <a href="index.html">Home</a>
  <a href="about.html">Über mich</a>
  <a href="kontakt.html">Kontakt</a>
</nav>
```

---

### Struktur

**Header (Kopfbereich):**
```html
<header>
  <h1>Meine Website</h1>
  <nav>
    <a href="index.html">Home</a>
  </nav>
</header>
```

**Main (Hauptinhalt):**
```html
<main>
  <h2>Willkommen!</h2>
  <p>Das ist der Hauptinhalt.</p>
</main>
```

**Container / Box:**
```html
<div>
  <h2>Box-Titel</h2>
  <p>Alles in dieser Box gehört zusammen.</p>
</div>
```

---

### Sonstiges

**Zeilenumbruch:**
```html
Erste Zeile<br>
Zweite Zeile
```

---

## 🎨 CSS Eigenschaften

### Farben

```css
h1 {
  color: red;                    /* Textfarbe */
  background-color: lightblue;   /* Hintergrundfarbe */
}
```

**Farben schreiben:**
- Mit Namen: `red`, `blue`, `green`, `yellow`
- Mit Hex: `#FF0000` (rot), `#0000FF` (blau)

💡 **Farben finden:** Google "color picker" oder coolors.co

**Beliebte Farben:**
- Rot: `#FF0000` | Blau: `#0000FF` | Grün: `#00FF00`
- Orange: `#FF6600` | Lila: `#9B59B6` | Pink: `#E91E63`

---

### Text

```css
h1 {
  font-size: 32px;           /* Schriftgrösse */
  font-family: Arial;        /* Schriftart */
  text-align: center;        /* Ausrichtung: left, center, right */
  font-weight: bold;         /* Fett oder normal */
}
```

---

### Abstände

```css
div {
  margin: 20px;    /* Abstand AUSSEN */
  padding: 15px;   /* Abstand INNEN */
}
```

🎨 **Unterschied:**
```
┌─────── MARGIN (aussen) ───────┐
│  ┌──── PADDING (innen) ────┐  │
│  │     INHALT              │  │
│  └─────────────────────────┘  │
└───────────────────────────────┘
```

---

### Grösse

```css
img {
  width: 300px;     /* Breite */
  height: 200px;    /* Höhe */
}
```

💡 Du kannst auch `width: 50%;` schreiben (= halbe Breite)

---

### Rahmen & Ecken

```css
div {
  border: 2px solid black;    /* Rahmen */
  border-radius: 10px;        /* Runde Ecken */
}
```

💡 Mit `border-radius: 50%;` wird ein Bild rund!

---

### Schatten

```css
div {
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}
```

---

### Hover-Effekt

```css
a {
  color: blue;
}

a:hover {
  color: red;    /* Farbe ändert sich bei Maus drüber */
}
```

---

## 💾 So arbeitest du

1. **Code schreiben** im Editor
2. **Speichern** mit `Ctrl + S`
3. **Browser öffnen** (Doppelklick auf HTML-Datei)
4. **Neu laden** mit `F5` um Änderungen zu sehen

---

## 🛠️ Wichtige Regeln

✅ **Immer öffnen UND schliessen**
```html
<h1>Text</h1>  ✅ Richtig
<h1>Text       ❌ Falsch
```

✅ **Anführungszeichen nicht vergessen**
```html
href="seite.html"  ✅ Richtig
href=seite.html    ❌ Falsch
```

---

## ⚠️ Wenn etwas nicht funktioniert

**Checkliste:**
- [ ] Datei gespeichert? (Ctrl + S)
- [ ] Browser neu geladen? (F5)
- [ ] Alle Tags geschlossen? (`<h1>...</h1>`)
- [ ] Anführungszeichen da? (`href="..."`)
- [ ] Semikolon in CSS? (`color: red;`)

---

## 💡 Projektideen

Was kannst du bauen?
- ✨ Seite über dein Hobby
- 🎮 Fanseite über dein Lieblingsspiel
- ⚽ Seite über Sport
- 🐶 Seite über dein Haustier
- 🎵 Musikempfehlungen
- 🍕 Rezeptsammlung

---

## 🎯 Deine ersten Schritte

1. ✅ Öffne `index.html` im Editor
2. ✅ Ändere den Text in `<h1>`
3. ✅ Speichere mit `Ctrl + S`
4. ✅ Öffne `index.html` im Browser
5. ✅ Öffne `css/style.css`
6. ✅ Ändere eine Farbe
7. ✅ Speichern und Browser neu laden (F5)

---

## 😊 Emojis verwenden

Kopiere einfach Emojis in deinen HTML-Code:

```html
<p>Hallo! 😊 Das ist meine Website 🌟</p>
```

**Beliebte Emojis:**
😊 😎 🎮 ⚽ 🎵 📚 🍕 🎨 ✨ 🌟 ⭐ 💡 🔥 ❤️ 👍 🏆 🚀 🎉

---

## 🎉 Du schaffst das!

Programmieren lernt man durch **Ausprobieren**!

- Hab keine Angst Fehler zu machen
- Probiere verschiedene Farben aus
- Frag wenn du Hilfe brauchst

**Viel Spass beim Coden! 🚀**

---

*Erstellt für den Schnuppertag Informatiker 💻*
