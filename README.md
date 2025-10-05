# 🌟 Portfoleez

**Autor:** Portfoleez Development Team  
**Version:** 1.0.0  
**Lizenz:** MIT

## 📋 Beschreibung

Portfoleez ist ein moderner, benutzerfreundlicher Portfolio-Builder, der es jedem ermöglicht, in wenigen Minuten ein professionelles Online-Portfolio zu erstellen. Die Anwendung ist vollständig im Browser lauffähig und benötigt keine Backend-Infrastruktur.

## ✨ Funktionsweise

### Hauptfunktionen:

1. **Echtzeit-Vorschau**: Alle Änderungen werden sofort in der Vorschau angezeigt
2. **LocalStorage-Speicherung**: Portfolios werden automatisch im Browser gespeichert
3. **HTML-Export**: Fertige Portfolios können als eigenständige HTML-Datei heruntergeladen werden
4. **Responsives Design**: Optimiert für Desktop und mobile Geräte
5. **Keine Registrierung erforderlich**: Sofort einsatzbereit

### Technologie-Stack:

- **HTML5**: Strukturierung der Webseite
- **CSS3**: Modernes Styling mit Gradients und Animationen
- **Vanilla JavaScript**: Keine Abhängigkeiten, pure JS-Funktionalität

## 📁 Projektstruktur

```
portofileez2/
├── README.md                # Projektdokumentation
├── public/                  # Öffentliche Web-Dateien
│   └── index.html          # Haupt-Portfolio-Builder-Anwendung
└── data/                    # Ordner für zukünftige Portfolio-Speicherung
    └── (JSON-Dateien)      # Hier können exportierte Portfolios gespeichert werden
```

## 🚀 Verwendung

### Lokale Nutzung:

1. Öffne `public/index.html` in einem modernen Webbrowser
2. Fülle die Formularfelder mit deinen Informationen aus
3. Klicke auf "Vorschau aktualisieren" um Änderungen zu sehen
4. Speichere dein Portfolio im Browser oder lade es als HTML herunter

### In Codespaces:

1. Starte einen Live-Server (z.B. mit der Extension "Live Server")
2. Navigiere zu `public/index.html`
3. Beginne mit der Bearbeitung deines Portfolios

## 🔧 Zukünftige Erweiterungen

### Mögliche Verbesserungen:

#### Backend-Integration:
- **Express.js Server**: Für permanente Speicherung von Portfolios
- **Datenbank**: MongoDB oder PostgreSQL für Nutzerverwaltung
- **API-Endpunkte**:
  - `POST /api/portfolios` - Portfolio speichern
  - `GET /api/portfolios/:id` - Portfolio abrufen
  - `PUT /api/portfolios/:id` - Portfolio aktualisieren
  - `DELETE /api/portfolios/:id` - Portfolio löschen

#### Erweiterte Features:
- **Bild-Upload**: Profilbild und Projektbilder hochladen
- **Mehrere Themes**: Verschiedene Farbschemata und Layouts
- **Projekt-Galerie**: Sektion für Projekte mit Screenshots
- **Social Media Integration**: Links zu LinkedIn, GitHub, Twitter etc.
- **PDF-Export**: Portfolio als PDF herunterladen
- **Teilbare Links**: Eindeutige URLs für jedes Portfolio
- **Authentifizierung**: Benutzerregistrierung und Login
- **Template-Bibliothek**: Vorgefertigte Portfolio-Vorlagen

#### Technische Verbesserungen:
- **React/Vue Migration**: Für bessere Komponenten-Verwaltung
- **TypeScript**: Für Type-Safety
- **Testing**: Unit- und Integration-Tests
- **CI/CD Pipeline**: Automatisches Deployment
- **PWA-Features**: Offline-Funktionalität

## 📝 Datei-Format für gespeicherte Portfolios

Portfolios können im folgenden JSON-Format im `data/`-Ordner gespeichert werden:

```json
{
  "id": "uuid-v4",
  "name": "Max Mustermann",
  "title": "Full Stack Developer",
  "about": "Leidenschaftlicher Entwickler mit 5 Jahren Erfahrung",
  "skills": "JavaScript, React, Node.js, Python",
  "contact": "max@example.com",
  "createdAt": "2025-10-05T18:00:00Z",
  "updatedAt": "2025-10-05T18:30:00Z"
}
```

## 🎨 Anpassung

### Farben ändern:

In `public/index.html` im `<style>`-Bereich:

```css
/* Haupt-Gradient anpassen */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Alternative Farbschemata: */
/* Blau-Grün: linear-gradient(135deg, #667eea 0%, #43cea2 100%); */
/* Orange-Pink: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); */
/* Lila-Rosa: linear-gradient(135deg, #a18cd1 0%, #fbc2eb 100%); */
```

### Neue Felder hinzufügen:

1. Füge ein neues Formularfeld in den HTML-Bereich ein
2. Erweitere die `updatePreview()`-Funktion um das neue Feld
3. Aktualisiere die `savePortfolio()`-Funktion

## 🤝 Beitragen

Beiträge sind willkommen! Bitte erstelle einen Pull Request oder öffne ein Issue für Verbesserungsvorschläge.

## 📄 Lizenz

MIT License - Frei verwendbar für private und kommerzielle Projekte

## 🌐 Weitere Informationen

Für Fragen oder Support, bitte ein Issue im Repository erstellen.

---

**Happy Portfolio Building! 🚀**