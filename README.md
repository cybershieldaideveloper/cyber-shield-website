# 🛡️ Cyber Shield - Offensive Security Website

Moderne Webseite für **CS Cyber Shield GmbH** - Offensive Security & Red Teaming Services.

## 🎨 Design

### Farbpalette (Original cyber-shield.org)
- **Primary Pink:** `#F52199` - Hauptakzentfarbe
- **Dark Blue:** `#314568` - Primäre dunkle Farbe
- **Dark Gray:** `#32373c` - Sekundäre dunkle Farbe
- **Light Blue:** `#7aa6d2` - Helle Akzente
- **Medium Blue:** `#92bae3` - Zusätzliche Akzente

### Features
✅ **Video Hero Background** - Dynamischer 3D Network Video-Hintergrund  
✅ **Glasmorphism Effects** - Moderne frosted glass Effekte  
✅ **Smooth Scroll Animations** - Elegante Scroll-basierte Animationen  
✅ **Counter Animations** - Animierte Statistiken (100% Erfolgsrate, 24/7 Support, 500+ Kunden)  
✅ **Featured Service Card** - Highlighted C2-as-a-Service  
✅ **Responsive Design** - Optimiert für alle Geräte (Desktop, Tablet, Mobile)  
✅ **Performance Optimized** - Lazy Loading, Video Pause on Scroll  
✅ **Accessibility** - Reduced Motion Support, Semantic HTML  

## 🚀 Live Demo

**GitHub Pages:** https://cybershieldaideveloper.github.io/cyber-shield-website/

## 📁 Struktur

```
cyber-shield-website/
├── index.html          # Haupt-HTML
├── style.css           # Styling mit exakter Farbpalette
├── script.js           # JavaScript für Interaktivität
├── assets/
│   └── images/         # Bilder & Icons
├── favicon.ico
└── README.md
```

## 🎯 Sections

1. **Hero** - Video-Background mit CTA Buttons
2. **Mission** - Unternehmensaussage + Statistiken
3. **Services** - 4 Service-Karten (Red Teaming, C2aaS, VAPT, Training)
4. **Principles** - Discover, Improve, Prevail
5. **Why Us** - 5 Gründe (Innovation, Robustheit, Präzision, Proaktivität, Nachhaltigkeit)
6. **Team** - 4 Team-Mitglieder
7. **Contact** - Kontaktinformationen + CTA

## 🛠️ Technologien

- **HTML5** - Semantic markup
- **CSS3** - Modern CSS mit Custom Properties, Grid, Flexbox
- **Vanilla JavaScript** - Keine Dependencies
- **Google Fonts** - Inter Font Family

## 📱 Responsive Breakpoints

- **Desktop:** 1200px+
- **Tablet:** 768px - 1199px
- **Mobile:** < 768px

## 🎬 Video Background

Verwendet ein kostenloses Video von Mixkit:
- Source: Digital Network Animation (3D Blue)
- Optimiert für Performance (autoplay, muted, loop)
- Fallback: Gradient Overlay wenn Video nicht lädt

## 🔧 Anpassungen

### Farben ändern
Bearbeite die CSS Variables in `style.css`:

```css
:root {
    --primary-pink: #F52199;
    --dark-blue: #314568;
    --dark-gray: #32373c;
    /* ... */
}
```

### Video austauschen
Ersetze die Video-URL in `index.html`:

```html
<video autoplay muted loop playsinline class="hero-video">
    <source src="DEIN-VIDEO.mp4" type="video/mp4">
</video>
```

### Inhalte bearbeiten
Alle Texte sind direkt in `index.html` editierbar.

## 📊 Performance

- **Lazy Loading** für Bilder
- **Video Pause** bei Scroll aus Viewport
- **Optimierte Animationen** mit CSS transforms
- **Minimale Dependencies** (nur Google Fonts)

## ♿ Accessibility

- Semantic HTML5 elements
- Reduced Motion Support für Nutzer mit Bewegungsempfindlichkeit
- ARIA Labels wo nötig
- Keyboard Navigation Support

## 📝 To-Do / Verbesserungen

- [ ] Eigenes Branding-Video erstellen
- [ ] Team-Fotos hinzufügen (aktuell Platzhalter-Avatare)
- [ ] Service-Icons optimieren
- [ ] Impressum & Datenschutz Seiten
- [ ] Kontaktformular Backend (aktuell nur Mailto)
- [ ] Blog-Section
- [ ] Case Studies / Portfolio
- [ ] Mehrsprachigkeit (EN/DE)

## 🚦 Deployment

### GitHub Pages (aktuell)
Automatisch deployed auf jeden Push zu `main`.

### Custom Domain
1. GitHub Repo Settings → Pages → Custom Domain
2. DNS CNAME auf `cybershieldaideveloper.github.io` setzen
3. HTTPS aktivieren

## 📄 Lizenz

© 2024 CS Cyber Shield GmbH - Alle Rechte vorbehalten

## 👨‍💻 Entwickler

Erstellt mit ❤️ von OpenClaw AI Agent

---

**Kontakt:**
- Email: vertrieb@cyber-shield.org
- Tel: +49 174 260 1741
