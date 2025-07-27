# 🏙️ Viola City - FiveM Roleplay Server Website

![Viola City Banner](assets/VC_Banner.gif)

Ein modernes, professionelles Website-Design für den deutschen FiveM Roleplay Server **Viola City**. Diese Website bietet eine ansprechende Präsentation des Servers mit vollständigem Regelwerk und Community-Informationen.

## 🌟 Features

### 🎨 **Design & UX**
- **Photorealistisches Design** mit modernen Gradienten und Animationen
- **Responsive Layout** - optimiert für Desktop, Tablet und Mobile
- **Tailwind CSS** für konsistente und saubere Styling
- **Font Awesome Icons** für professionelle Symbolik
- **Smooth Scrolling** und interaktive Navigationselemente

### 📄 **Seiten & Inhalte**
- **Homepage** (`index.html`) - Willkommensseite mit Server-Features
- **Regelwerk** (`regelwerk.html`) - Vollständiges offizielles Regelwerk
- **About Section** - Server-Statistiken und Community-Info
- **Discord Integration** - Community-Bereich mit Mitgliederzahlen

### 🛡️ **Regelwerk-System**
- **§1 Roleplay Verhalten** - Grundregeln für authentisches RP
- **§2 Fraktionsregelwerk** - Detaillierte Fraktions- und Organisationsregeln
- **§3 Blacklist & Blackwords** - Kommunikationsrichtlinien
- **Interaktives Inhaltsverzeichnis** mit direkter Navigation
- **Responsive Regeldarstellung** mit farbcodierten Abschnitten

## 🚀 Live Demo

Die Website kann direkt über einen lokalen Webserver oder GitHub Pages gehostet werden.

## 📁 Projektstruktur

```
website-viola/
├── index.html              # Hauptseite
├── regelwerk.html           # Regelwerk-Seite
├── assets/                  # Medien-Dateien
│   ├── vc.png              # Logo
│   └── VC_Banner.gif       # Banner
└── README.md               # Projektdokumentation
```

## 🛠️ Installation & Setup

### 1. Repository klonen
```bash
git clone https://github.com/[username]/website-viola.git
cd website-viola
```

### 2. Lokaler Server (optional)
```bash
# Mit Python
python -m http.server 8000

# Mit Node.js (http-server)
npx http-server

# Mit PHP
php -S localhost:8000
```

### 3. Browser öffnen
Navigiere zu `http://localhost:8000` oder öffne `index.html` direkt im Browser.

## 🎯 Verwendete Technologien

| Technologie | Zweck | Version |
|-------------|-------|---------|
| **HTML5** | Markup-Struktur | Latest |
| **Tailwind CSS** | CSS Framework | 3.x (CDN) |
| **Font Awesome** | Icons | 6.0.0 |
| **JavaScript** | Interaktivität | ES6+ |

## 📱 Responsive Design

Die Website ist vollständig responsive und optimiert für:

- **Desktop** (1920px+) - Vollständige Feature-Darstellung
- **Laptop** (1024px-1919px) - Angepasste Grid-Layouts
- **Tablet** (768px-1023px) - Optimierte Navigation
- **Mobile** (320px-767px) - Touch-optimiert mit Hamburger-Menu

## 🎨 Design-System

### Farbpalette
```css
Primary:   #F59E0B (Amber-500)
Secondary: #D97706 (Amber-600)
Accent:    #EA580C (Orange-600)
Dark:      #111827 (Gray-900)
Light:     #F3F4F6 (Gray-100)
```

### Typographie
- **Headings**: System Font Stack (optimiert für Performance)
- **Body**: System Font Stack
- **Icons**: Font Awesome 6.0

## 📋 Regelwerk-Integration

Das Regelwerk basiert auf dem offiziellen **Viola City Server Dokument** und umfasst:

### Hauptsektionen
- **Einleitung** - Server-Anforderungen und grundlegende Informationen
- **§1 Roleplay Verhalten** - 27 detaillierte Unterregeln
- **§2 Fraktionsregelwerk** - Fraktionsarten und Aktionsregeln
- **§3 Blacklist & Blackwords** - Kommunikationsrichtlinien
- **§5 Hinweise** - Aktuelle Informationen und Updates

### Features
- ✅ Interaktive Navigation zwischen Paragraphen
- ✅ Farbcodierte Regel-Kategorien
- ✅ Mobile-optimierte Darstellung
- ✅ Suchfreundliche Struktur

## 🚀 Deployment

### GitHub Pages
1. Repository zu GitHub pushen
2. Settings → Pages → Source: Deploy from branch
3. Branch: `main` auswählen
4. Save

### Netlify
1. Repository zu Netlify verbinden
2. Build Command: (leer lassen)
3. Publish Directory: `/`
4. Deploy

### Eigener Server
```bash
# Dateien auf Server hochladen
scp -r * user@server:/var/www/html/viola-city/

# Nginx/Apache Konfiguration anpassen
# Stelle sicher, dass index.html als Standard-Datei dient
```

## 🤝 Contributing

Beiträge sind willkommen! Bitte beachte folgende Guidelines:

1. **Fork** das Repository
2. **Branch** erstellen (`git checkout -b feature/AmazingFeature`)
3. **Commit** deine Änderungen (`git commit -m 'Add AmazingFeature'`)
4. **Push** zum Branch (`git push origin feature/AmazingFeature`)
5. **Pull Request** öffnen

### Development Guidelines
- Verwende **semantische HTML-Struktur**
- Halte dich an **Tailwind CSS Konventionen**
- Teste auf **mehreren Geräten** und Browsern
- **Optimiere Bilder** vor dem Commit
- **Dokumentiere** neue Features im README

## 📄 Lizenz

Dieses Projekt steht unter der MIT Lizenz. Siehe `LICENSE` Datei für Details.

## 👥 Team

**Viola City Development Team**
- Website Design & Development
- Server Administration
- Community Management

## 📞 Support

Bei Fragen oder Problemen:

- **Discord**: [Viola City Discord Server]
- **Ticket System**: [Support Portal]
- **GitHub Issues**: Für technische Website-Probleme

## 🔄 Changelog

### Version 1.0.0 (Januar 2025)
- ✨ Initiale Website-Erstellung
- ✨ Vollständiges Regelwerk integriert
- ✨ Responsive Design implementiert
- ✨ Discord Integration hinzugefügt
- ✨ Mobile Navigation optimiert

---

**Made with ❤️ for the Viola City Community**

*Erlebe authentisches Roleplay in der aufregendsten deutschen FiveM Community!*

