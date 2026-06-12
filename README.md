# Digitale Visitenkarte

Eine einzelne HTML-Datei. Dein Name, deine Rolle, dein Kontakt – kein Framework, kein CMS, keine Plattform.

Dieses Repository gehört zum Artikel **„Deine erste eigene Seite"** auf [Upgrade läuft →](https://upgradelaeuft.substack.com)

---

## Was hier drin ist

```
index.html        → die Visitenkarte
DEPLOYEN.md       → Anleitung zum Veröffentlichen mit Netlify Drop
README.md         → diese Datei
```

---

## Schnellstart: in CodePen ausprobieren

Du brauchst nichts zu installieren. Geh auf [codepen.io](https://codepen.io), erstelle einen kostenlosen Account, öffne einen neuen Pen und kopiere den Inhalt von `index.html` in das HTML-Feld. Die Vorschau erscheint sofort.

---

## Lokal bearbeiten: Schritt für Schritt

Wenn du die Datei auf deinem eigenen Computer bearbeiten willst, brauchst du einen Texteditor und einen Browser, beides ist bereits installiert.

### 1. Texteditor öffnen

Ein Texteditor speichert reinen Text ohne versteckte Formatierungen. Word oder Google Docs sind dafür die falsche Umgebung.

- **Windows:** Notepad ist vorinstalliert und reicht für den Anfang.
- **Mac:** TextEdit funktioniert, aber nur wenn du vorher auf **Format → Reinen Text verwenden** umstellst. Sonst speichert TextEdit unsichtbare Formatierungen, die dein HTML stören.

Kopiere den Code der `index.html` aus dem Codepen oder dem [Beitrag](Link ergänzen) und füge ihn in den Editor deiner Wahl. 

### 3. Eigene Angaben eintragen

Ersetze die Platzhalter durch deine echten Daten:

| Platzhalter | Ersetzen durch |
|---|---|
| `Dein Name` | deinen Namen |
| `Deine Berufsbezeichnung oder Rolle in einem Satz.` | deine Rolle |
| `Ein kurzer Satz über dich, deine Arbeit oder dein Angebot.` | deine Beschreibung |
| `du@beispiel.de` | deine E-Mail-Adresse (zweimal) |

Wichtig: Die spitzen Klammern (`<h1>`, `</h1>` usw.) bleiben stehen. Du änderst nur den Text zwischen ihnen.

### 4. Lokal testen

Speichere die Datei und öffne sie per Doppelklick im Browser. Die Adresszeile beginnt mit `file://` – das ist normal, die Seite liegt noch auf deinem Computer.

Änderungen machen → speichern → im Browser **F5** (Windows) oder **Cmd+R** (Mac) drücken. So sieht ein normaler Web-Workflow aus.

**Häufige Fehler:**

- Nur Code statt Seite sichtbar → die Datei heißt vermutlich `index.html.txt`. Zeige dir die Dateiendungen an und benenne sie um.
- Umlaute kaputt → prüfe ob `<meta charset="UTF-8">` im Code steht.
- Seite völlig leer → eine Klammer oder ein schließender Tag fehlt. Vergleiche deinen Code mit dem Original.

---

## Weiter mit VS Code (optional)

VS Code ist ein kostenloser Editor für Code, der deutlich komfortabler ist als Notepad oder TextEdit: Syntaxfärbung, Autovervollständigung, integriertes Terminal.

**Installation:** [code.visualstudio.com](https://code.visualstudio.com) → Download → installieren.

**Empfohlene Erweiterung:** „Live Preview" von Microsoft. Sie öffnet eine Vorschau direkt im Editor, die sich bei jeder Änderung automatisch aktualisiert, ähnlich wie CodePen, aber lokal auf deinem Computer.

VS Code ist kein notwendiger Schritt für dieses Projekt, aber ein sinnvoller, sobald du merkst, dass du öfter an Code arbeitest.

---

## Nächste Schritte

Die Visitenkarte ist fertig? In `DEPLOYEN.md` steht, wie du sie mit Netlify Drop in wenigen Minuten unter einer echten URL veröffentlichst.

---

*Teil der Artikelserie ,,Praxis" aus dem [Codex Journal](https://codex.fundament-studio.de).*