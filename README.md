# Regio-Digital Webdesign

Marketing-Website für Regio-Digital – KI-gestützte Websites für KMU in der Region Stuttgart.

**Stack:** React + Vite · CSS · Lucide Icons

---

## Lokale Entwicklung

```bash
npm install
npm run dev
```

## Deployment via GitHub → Vercel

1. Diesen Ordner als neues GitHub-Repository pushen:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/DEIN-USERNAME/regio-digital.git
   git push -u origin main
   ```
2. Auf vercel.com einloggen → Add New Project
3. GitHub-Repo auswählen → Framework: Vite (auto-erkannt)
4. Deploy klicken – fertig ✓

## Vor Go-Live anpassen

- src/sections/Kontakt.jsx → Formspree-Endpoint eintragen
- Telefonnummer in Kontakt.jsx und Footer.jsx ersetzen
- index.html → Favicon ergänzen

## Projektstruktur

src/
  components/  Nav, Footer
  sections/    Hero, Problems, Branchen, Ablauf, Preise, Demos, UeberMich, FAQ, Kontakt
  hooks/       useScrollReveal.js
  App.jsx · index.css · main.jsx
