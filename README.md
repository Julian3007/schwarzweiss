# 🎯 Schwarz Weiß - Multiplayer Word Guessing Game

Ein Echtzeit-Multiplayer-Wortratespiel basierend auf dem klassischen "Bulls and Cows" Konzept, aber mit Wörtern statt Zahlen.

![Game Screenshot](https://via.placeholder.com/800x400/667eea/ffffff?text=Schwarz+Wei%C3%9F+Game)

## 🎮 Spielregeln

- Zwei Spieler wählen geheime Wörter gleicher Länge
- Abwechselnd versuchen sie, das Wort des Gegners zu erraten
- **Schwarz** = Richtiger Buchstabe an richtiger Position
- **Weiß** = Richtiger Buchstabe an falscher Position
- Der erste Spieler, der das komplette Wort errät, gewinnt!

## ✨ Features

- 🌐 **Echtzeit-Multiplayer** mit Firebase
- 👥 **Benutzerregistrierung** und -verwaltung
- 🎲 **Flexible Wortlängen** (3-8 Buchstaben)
- 💬 **In-Game Chat** während des Spiels
- 🏆 **Gewinn-Benachrichtigungen** mit Sound-Effekten
- 📱 **Responsive Design** für Mobile und Desktop
- 🎮 **Spiellobby** mit öffentlichen und privaten Spielen
- 🗑️ **Spiel-Management** (Erstellen, Beitreten, Löschen)
- 📊 **Sortierbare Spieleliste** nach Datum/Aktivität

## 🚀 Live Demo

[Hier klicken um das Spiel zu spielen](https://your-game-url.netlify.app)

## 🛠️ Installation & Setup

### Voraussetzungen
- Ein Firebase-Projekt mit Realtime Database
- Webserver oder Hosting-Service

### Lokale Entwicklung
1. Repository klonen:
   ```bash
   git clone https://github.com/yourusername/schwarz-weiss-game.git
   cd schwarz-weiss-game
   ```

2. Firebase-Konfiguration:
   - Öffne `schwarz-weiss-vollversion.html`
   - Ersetze die Firebase-Konfiguration mit deinen Credentials

3. Lokalen Server starten:
   ```bash
   # Mit Python
   python -m http.server 8000
   
   # Mit Node.js
   npx serve .
   
   # Mit PHP
   php -S localhost:8000
   ```

4. Öffne `http://localhost:8000/schwarz-weiss-vollversion.html`

## 🔧 Technologie-Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Firebase Realtime Database
- **Styling**: Custom CSS mit Gradients und Animationen
- **Real-time**: Firebase WebSocket-Verbindungen
- **Responsive**: CSS Grid und Flexbox

## 🎨 Architektur

```
schwarz-weiss-vollversion.html
├── 🎨 CSS Styling
│   ├── Responsive Layout
│   ├── Game Cards Design
│   ├── Win Animations
│   └── Mobile Optimization
├── 🧠 JavaScript Logic
│   ├── User Management
│   ├── Game State Management
│   ├── Real-time Synchronization
│   ├── Chat System
│   └── Performance Optimizations
└── 🔥 Firebase Integration
    ├── User Authentication
    ├── Game Data Storage
    ├── Real-time Updates
    └── Chat Messages
```

## 🔒 Sicherheit

- Firebase Security Rules implementiert
- Client-seitige Validierung
- Eingabe-Sanitization
- Rate-Limiting über Firebase

## 📱 Browser-Kompatibilität

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile Browsers (iOS Safari, Chrome Mobile)

## 🤝 Beitragen

1. Fork das Repository
2. Erstelle einen Feature-Branch (`git checkout -b feature/AmazingFeature`)
3. Committe deine Änderungen (`git commit -m 'Add some AmazingFeature'`)
4. Push zum Branch (`git push origin feature/AmazingFeature`)
5. Öffne einen Pull Request

## 🐛 Bug Reports

Bitte erstelle ein [Issue](https://github.com/yourusername/schwarz-weiss-game/issues) für Bug Reports mit:
- Browser und Version
- Schritte zur Reproduktion
- Erwartetes vs. tatsächliches Verhalten
- Screenshots (falls hilfreich)

## 📋 Roadmap

- [ ] Turnier-Modus
- [ ] Statistiken und Ranglisten
- [ ] Verschiedene Schwierigkeitsgrade
- [ ] KI-Gegner für Solo-Spiel
- [ ] Spiel-Replay-System
- [ ] Mobile App (PWA)
- [ ] Mehrsprachige Unterstützung


## 👨‍💻 Autor

**Julian3007**
- GitHub: [@Julian3007](https://github.com/Julian3007)

## 🙏 Danksagungen

- Inspiriert vom klassischen "Bulls and Cows" Spiel
- Firebase für die Echtzeit-Multiplayer-Infrastruktur
- Die Open-Source-Community für Tools und Inspiration

---

⭐ **Gefällt dir das Spiel? Gib dem Repository einen Stern!** ⭐

