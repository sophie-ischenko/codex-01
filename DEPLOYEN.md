# Veröffentlichen mit Netlify Drop

Netlify Drop ist der einfachste Weg, eine HTML-Datei unter einer echten URL erreichbar zu machen. Keine Kreditkarte, kein Server, kein kompliziertes Setup. Du ziehst eine Datei in ein Feld, fertig.

---

## Was passiert dabei?

Deine `index.html` wird auf Netlify-Servern gespeichert und unter einer Webadresse ausgeliefert. Die neue URL beginnt mit `https://` statt mit `file://`. Das ist der Unterschied zwischen einem lokalen Dokument und einer echten Seite im Netz.

---

## Schritt für Schritt

### 1. Netlify Drop öffnen

Geh auf [app.netlify.com/drop](https://app.netlify.com/drop). Du siehst eine große Fläche mit dem Text „Drag and drop your site output folder here".

### 2. Datei hineinziehen

Ziehe deine `index.html` direkt in dieses Feld. Netlify erkennt die Datei automatisch.

> **Hinweis:** Netlify erwartet eigentlich einen Ordner, nimmt aber auch eine einzelne Datei. Falls es nicht funktioniert, lege `index.html` in einen neuen leeren Ordner und ziehe den Ordner hinein.

### 3. URL kopieren

Nach wenigen Sekunden erscheint eine URL, zum Beispiel `https://eloquent-mango-3a9f12.netlify.app`. Diese Adresse ist sofort erreichbar. Kopiere die das dazugehörige Passwort. Du brauchst es, wenn du deine URL aufrufst. Dort wirst du dann aufgefordert es einzugeben.

### 4. Account erstellen (optional, aber empfohlen)

Ohne Account bleibt deine Seite nur 24 Stunden online. Mit einem kostenlosen Netlify-Account bleibt sie dauerhaft erreichbar, und du kannst die Seite jederzeit aktualisieren, einfach wieder eine neue Version der Datei hineinziehen.

---

## Seite aktualisieren

1. `index.html` in deinem Texteditor öffnen
2. Änderungen machen und speichern
3. Auf [app.netlify.com](https://app.netlify.com) einloggen → dein Projekt öffnen → neue Datei hineinziehen

Die URL bleibt dieselbe.

---

## Eigene Domain (später)

Netlify-URLs sehen technisch aus. Wenn du irgendwann eine eigene Domain willst, zum Beispiel `deinnname.de`, kannst du diese in den Netlify-Einstellungen verknüpfen. Das ist ein separater Schritt, der eine Domain-Registrierung voraussetzt, aber technisch nicht kompliziert ist.

---

## Häufige Fragen

**Kostet das etwas?**
Nein. Netlify Drop und der kostenlose Account reichen für eine einzelne Seite vollständig aus.

**Kann ich die URL ändern?**
Der erste Teil der URL (der zufällige Name) lässt sich in den Einstellungen manuell ändern – zum Beispiel auf `deinname.netlify.app`.

**Was ist, wenn ich die Seite wieder löschen will?**
Im Netlify-Dashboard kannst du dein Projekt jederzeit löschen. Die URL ist dann nicht mehr erreichbar.

---

*Zurück zur Hauptanleitung: [README.md](README.md)*