# Base Passage Hostel Karlsruhe - Website

> Modernes, hochwertiges Design-Hostel Website für Base Passage im Herzen von Karlsruhe.

![Next.js](https://img.shields.io/badge/Next.js-14-black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.3-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![License](https://img.shields.io/badge/License-Proprietary-red)

## 🚀 Live Demo

**[🌐 Zur Live-Website](https://basepassage-website-kpfirmann91-lang.vercel.app/)** - Hosted auf Vercel

---

## 📱 Features

✅ **Vollständig responsive** - Mobile, Tablet, Desktop  
✅ **Moderne Animationen** - Scroll-Effekte, Fade-In Animations  
✅ **SEO optimiert** - Meta Tags, Open Graph, Structured Data  
✅ **Performance** - Next.js 14 mit Optimized Images  
✅ **Kontaktformular** - Vorbereitet für Email-Integration  
✅ **Mehrsprachigkeit** - Deutsch/Englisch vorbereitet  
✅ **Premium Design** - Boutique-Hotel Ästhetik  
✅ **Booking-Integration** - Vorbereitet  

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org/)
- **Styling**: [Tailwind CSS 3](https://tailwindcss.com/)
- **Animations**: [Framer Motion](https://www.framer.com/motion/)
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Hosting**: [Vercel](https://vercel.com/)

---

## 📖 Seiten & Sections

### 🏠 Startseite

1. **Hero Section** - Vollbild mit CTA Buttons
2. **Über Base Passage** - Mission & Features
3. **Unsere Werte** - 5 Kernwerte (Community, Design, Local Experience, Sauberkeit, Digital)
4. **Zimmer** - Schlafkapseln & Doppelzimmer mit Preisen
5. **Community** - Lounge, Küche, Begegnungsbereiche
6. **Line76 Club** - Partnerschaft mit Nachtclub
7. **Karlsruhe Entdecken** - 6 Sehenswürdigkeiten
8. **Kontakt** - Kontaktformular & Informationen

---

## 🎨 Design System

### Farben
```
- Primary Dark: #111111 (Anthrazit)
- White: #FAFAF7 (Warmes Weiß)
- Sand: #D4C5B0
- Beige: #E8DCC8
- Orange: #E67E22 (Akzent)
- Gold: #D4AF37
- Night: #1A1A1A
```

### Typografie
```
- Headlines: Playfair Display (elegant, serif)
- Body: Inter (modern, sans-serif)
```

---

## 🚀 Schnellstart (Lokal)

```bash
# Repository klonen
git clone https://github.com/kpfirmann91-lang/base-passage-website.git
cd base-passage-website

# Dependencies installieren
npm install

# Development Server starten
npm run dev

# Im Browser öffnen
# http://localhost:3000
```

## 🔨 Verfügbare Commands

```bash
# Development Server
npm run dev

# Production Build
npm run build

# Production Server starten
npm start

# Linting
npm run lint
```

---

## 📦 Projektstruktur

```
src/
├── app/
│   ├── layout.tsx              # Root Layout
│   ├── globals.css             # Global Styles
│   └── page.tsx                # Home Page
├── components/
│   ├── common/
│   │   ├── Navigation.tsx       # Sticky Navigation
│   │   └── Footer.tsx           # Footer
│   └── sections/
│       ├── HeroSection.tsx
│       ├── AboutSection.tsx
│       ├── ValuesSection.tsx
│       ├── RoomsSection.tsx
│       ├── CommunitySection.tsx
│       ├── Line76Section.tsx
│       ├── KarlsruheSection.tsx
│       └── ContactSection.tsx
├── hooks/
│   └── useInView.ts            # Scroll Animation Hook
├── data/
│   └── translations/
│       ├── de.json             # German
│       └── en.json             # English
└── public/
    └── robots.txt              # SEO
```

---

## 🔌 Integration Guides

### Kontaktformular (Email)

**Benötigte Schritte:**
1. Email-Service wählen (SendGrid, Brevo, Nodemailer)
2. API Keys in `.env.local` speichern
3. `src/components/sections/ContactSection.tsx` anpassen

**Beispiel mit SendGrid:**
```bash
SENDGRID_API_KEY=your_api_key
```

### Booking-System

**Empfohlene Lösungen:**
- [Booking.com](https://www.booking.com/)
- [Hostelworld](https://www.hostelworld.com/)
- [Airbnb API](https://www.airbnb.com/)
- [Beds24](https://www.beds24.com/)

**Button in `Navigation.tsx` + `HeroSection.tsx` aktualisieren**

### Instagram Integration

**Placeholder in `src/data/` vorbereitet**
- Nutze: [Instagram Graph API](https://developers.facebook.com/docs/instagram-graph-api)
- Oder: [Embed Service](https://www.instagram.com/developers/)

### Google Maps

**Integration in `KarlsruheSection.tsx`:**
```tsx
// Placeholder ersetzen mit:
import { GoogleMap, LoadScript, Marker } from '@react-google-maps/api';
```

---

## 📊 SEO Optimierung

✅ **Meta Tags** - Dynamisch in `layout.tsx`  
✅ **Open Graph** - Für Social Media Sharing  
✅ **robots.txt** - Für Google Crawler  
✅ **Sitemap** - Vorbereitet (noch zu generieren)  
✅ **Strukturierte Daten** - JSON-LD vorbereitet  

**Sitemap generieren:**
```bash
npm install next-sitemap
```

---

## 🌍 Mehrsprachigkeit (i18n)

Die Website ist vorbereitet für Deutsch/Englisch.

**Aktuell:** Deutsch als Standard  
**TODO:** Full i18n Setup mit next-i18n

---

## 📈 Performance

- ⚡ Next.js 14 App Router
- 🖼️ Optimized Images
- 📦 Code Splitting
- 🎯 Core Web Vitals optimiert

**Lighthouse Score (Ziel):**
- Performance: 90+
- Accessibility: 95+
- Best Practices: 95+
- SEO: 100

---

## 🔒 Sicherheit

- ✅ HTTPS (Vercel)
- ✅ Content Security Policy (vorbereitet)
- ✅ XSS Protection
- ✅ CSRF Protection (bei Formular)

---

## 📝 Lizenz

**Proprietary** - Base Passage Hostel GmbH / HOBÄCK-Gruppe

Alle Rechte vorbehalten. Vervielfältigung, Verbreitung oder Modifikation ohne ausdrückliche schriftliche Genehmigung nicht gestattet.

---

## 📞 Kontakt

**Base Passage Hostel GmbH**

📍 Passagehof 6, 76133 Karlsruhe  
📧 info@basepassage.de  
📱 +49 (0) 721 123456  
🌐 [basepassage.de](https://basepassage.de)  

---

## 🚀 Deployment

### Vercel (Empfohlen)

1. **Repository mit Vercel verbinden:**
   - Gehe zu [vercel.com](https://vercel.com/)
   - Klicke "New Project"
   - Wähle dieses GitHub Repository
   - Klicke "Deploy"

2. **Automatische Deployments:**
   - Jeder Push zu `main` triggert automatisch ein Deployment
   - Preview-URLs für Pull Requests

3. **Environment Variables:**
   ```
   NEXT_PUBLIC_SITE_URL=https://basepassage.de
   ```

### Eigener Server

```bash
# Build
npm run build

# Start
npm start

# Mit PM2 (persistent)
pm2 start npm --name "base-passage" -- start
```

---

## 📚 Weitere Ressourcen

- [Next.js Dokumentation](https://nextjs.org/docs)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)
- [Framer Motion Guide](https://www.framer.com/motion/)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)

---

**Erstellt mit ❤️ für Base Passage Hostel Karlsruhe**
