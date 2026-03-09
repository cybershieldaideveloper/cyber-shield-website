# 📦 Versionen & Releases

## Aktuelle Version: v2.1-mobile

**Live URL:** https://cybershieldaideveloper.github.io/cyber-shield-website/

---

## 🏷️ Version History

### v2.1-mobile (CURRENT) - 09.03.2026
**Branch:** `main`  
**Tag:** `v2.1-mobile`  
**Commit:** `175686a`

**Features:**
- ✅ Mobile-optimierter animierter Gradient-Hintergrund
- ✅ Funktioniert auf ALLEN Geräten (Desktop, Tablet, Mobile)
- ✅ Reduzierte Partikel-Anzahl auf Mobile (Performance)
- ✅ Pulsierender Gradient-Effekt
- ✅ Video auf Mobile deaktiviert (bessere Performance)

**Empfohlen für:** Production Deploy (alle Geräte)

---

### v2.0-desktop - 09.03.2026
**Branch:** `version/desktop-only`  
**Tag:** `v2.0-desktop`  
**Commit:** `e86ebb7`

**Features:**
- ✅ Video-Hero mit Particle-Animation Fallback
- ✅ Exakte cyber-shield.org Farbpalette
- ✅ Modernes UI mit Glasmorphism
- ✅ Smooth Scroll-Animationen
- ✅ Counter-Animationen
- ✅ Featured Service Card

**Empfohlen für:** Desktop-First / Demo-Zwecke

---

### v1.0-original - 09.03.2026
**Tag:** `v1.0-original`  
**Commit:** `92e50b2`

**Features:**
- ✅ Basic Layout
- ✅ Service Cards
- ✅ Team Section
- ✅ Contact Form

**Empfohlen für:** Minimalistisches Design

---

## 🔄 Zwischen Versionen wechseln

### Lokales Checkout (für Entwicklung)

```bash
cd /home/csa/.openclaw/workspace/cyber-shield-website

# Desktop-Version auschecken
git checkout version/desktop-only

# Zurück zur aktuellen Version
git checkout main

# Bestimmten Tag auschecken
git checkout v1.0-original

# Zurück zum neuesten Stand
git checkout main
```

### GitHub Pages auf bestimmte Version deployen

**Option 1: Branch wechseln (empfohlen)**
1. Gehe zu: https://github.com/cybershieldaideveloper/cyber-shield-website/settings/pages
2. Unter "Source" → wähle Branch:
   - `main` → v2.1-mobile (aktuelle Version)
   - `version/desktop-only` → v2.0-desktop

**Option 2: Tag deployen**
```bash
# Tag zu Branch machen
git checkout v2.0-desktop
git checkout -b deploy-desktop
git push origin deploy-desktop

# Dann in GitHub Pages Settings den Branch wählen
```

---

## 🔍 Version vergleichen

```bash
# Unterschiede zwischen Versionen anzeigen
git diff v2.0-desktop v2.1-mobile

# Dateien einer bestimmten Version anzeigen
git show v1.0-original:index.html
```

---

## 📊 Version-Features Matrix

| Feature | v1.0 | v2.0 | v2.1 |
|---------|------|------|------|
| Basic Layout | ✅ | ✅ | ✅ |
| Exact Colors | ❌ | ✅ | ✅ |
| Video Hero | ❌ | ✅ | ⚠️ |
| Particle Animation | ❌ | ⚠️ | ✅ |
| Animated Gradient | ❌ | ⚠️ | ✅ |
| Mobile Optimized | ⚠️ | ⚠️ | ✅ |
| Counter Animations | ❌ | ✅ | ✅ |
| Glasmorphism | ❌ | ✅ | ✅ |

**Legende:**
- ✅ Vollständig implementiert
- ⚠️ Teilweise / mit Einschränkungen
- ❌ Nicht vorhanden

---

## 🚀 Neue Version erstellen

```bash
# 1. Änderungen machen
git add .
git commit -m "feat: New feature"

# 2. Tag erstellen
git tag -a v2.2-feature -m "Description"

# 3. Pushen
git push origin main --tags
```

---

## 📝 Changelog

### [2.1] - 2026-03-09
**Hinzugefügt:**
- Mobile-optimierter Gradient-Hintergrund
- Pulsierender Effekt auf Mobile
- Performance-Optimierung für Partikel

**Geändert:**
- Video auf Mobile deaktiviert
- Partikel-Anzahl reduziert (50 statt 100)

**Behoben:**
- Fehlender animierter Hintergrund auf Mobile

### [2.0] - 2026-03-09
**Hinzugefügt:**
- Video-Hero Background
- Particle-Animation Fallback
- Exakte Farbpalette
- Glasmorphism-Effekte
- Counter-Animationen

**Geändert:**
- Komplettes Redesign
- Moderne UI-Komponenten

### [1.0] - 2026-03-09
**Hinzugefügt:**
- Initial Release
- Basic Layout
- Service Cards
- Team Section

---

## 🔒 Rollback durchführen

Falls die neue Version Probleme macht:

```bash
# Zurück zu v2.0-desktop
git checkout version/desktop-only
git push origin main --force

# ODER: Tag deployen
git reset --hard v2.0-desktop
git push origin main --force
```

**⚠️ WARNUNG:** `--force` überschreibt die Remote-Historie!

---

## 📞 Support

Bei Fragen zur Versionierung:
- **Repo:** https://github.com/cybershieldaideveloper/cyber-shield-website
- **Releases:** https://github.com/cybershieldaideveloper/cyber-shield-website/releases
- **Tags:** https://github.com/cybershieldaideveloper/cyber-shield-website/tags
