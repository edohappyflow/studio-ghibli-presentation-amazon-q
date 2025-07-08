# Deployment Instructies - GitHub Pages

## 🚀 Stap-voor-Stap GitHub Pages Setup

### Stap 1: GitHub Repository Maken
1. Ga naar [GitHub.com](https://github.com)
2. Klik op "New repository" (groene knop)
3. Vul in:
   - **Repository name:** `studio-ghibli-presentation`
   - **Description:** `Studio Ghibli presentatie voor Aurélie - Groep 4`
   - **Public:** ✅ (vereist voor GitHub Pages)
   - **Add README:** ❌ (we hebben al een README)

### Stap 2: Bestanden Uploaden
1. Klik op "uploading an existing file"
2. Sleep alle bestanden naar de upload zone:
   - `index.html`
   - `style.css`
   - `README.md`
   - `BRIEFING.md`
   - `DEPLOYMENT.md`
   - `images/` map (als je afbeeldingen hebt)
3. Commit message: `Initial commit - Studio Ghibli presentatie`
4. Klik "Commit changes"

### Stap 3: GitHub Pages Activeren
1. Ga naar repository **Settings** tab
2. Scroll naar beneden naar **Pages** sectie
3. Bij **Source** selecteer: `Deploy from a branch`
4. Bij **Branch** selecteer: `main`
5. Bij **Folder** selecteer: `/ (root)`
6. Klik **Save**

### Stap 4: Wachten op Deployment
- GitHub Pages heeft 2-5 minuten nodig
- Je krijgt een groene ✅ als het klaar is
- URL wordt getoond: `https://[username].github.io/studio-ghibli-presentation`

## 📱 Presentatie URL

### Voor Aurélie's Presentatie
**URL:** `https://[jouw-github-username].github.io/studio-ghibli-presentation`

### Voorbeeld URLs
- `https://edohappyflow.github.io/studio-ghibli-presentation`
- `https://aurelie-school.github.io/studio-ghibli-presentation`

## 🔧 Updates Maken

### Bestanden Wijzigen
1. Ga naar je repository op GitHub
2. Klik op het bestand dat je wilt wijzigen
3. Klik op het potlood icoon (Edit)
4. Maak je wijzigingen
5. Scroll naar beneden naar "Commit changes"
6. Voeg een beschrijving toe
7. Klik "Commit changes"

### Automatische Update
- GitHub Pages update automatisch binnen 1-2 minuten
- Ververs je browser om wijzigingen te zien

## 🎯 Voor de Presentatie Dag

### Checklist
- [ ] Repository is publiek
- [ ] GitHub Pages is geactiveerd
- [ ] URL werkt in browser
- [ ] Presentatie test op smartboard
- [ ] URL genoteerd voor in de klas
- [ ] Backup plan klaar

### URL Delen
1. **Korte URL maken:** Gebruik bit.ly of tinyurl.com
2. **QR Code:** Maak QR code van de URL
3. **Backup:** Noteer URL op papier
4. **Test:** Open URL op verschillende apparaten

## 🐛 Troubleshooting

### Presentatie Laadt Niet
1. **Check URL:** Zorg dat je de juiste URL gebruikt
2. **Wacht:** GitHub Pages kan tot 10 minuten duren
3. **Repository Public:** Zorg dat repository publiek is
4. **Branch:** Controleer dat je `main` branch gebruikt

### 404 Error
1. **Bestandsnaam:** `index.html` moet exact zo heten
2. **Locatie:** `index.html` moet in root staan (niet in map)
3. **Case sensitive:** Let op hoofdletters/kleine letters

### Wijzigingen Niet Zichtbaar
1. **Cache:** Ververs browser (Ctrl+F5 of Cmd+Shift+R)
2. **Wachten:** Geef GitHub 2-3 minuten
3. **Incognito:** Test in incognito/private browsing

## 🔒 Backup Opties

### Lokale Backup
1. Download alle bestanden naar USB stick
2. Test `index.html` lokaal in browser
3. Neem USB mee naar school

### Alternative Hosting
- **Netlify Drop:** Sleep bestanden naar netlify.app/drop
- **Surge.sh:** Gratis hosting voor statische sites
- **Vercel:** Eenvoudige deployment

## 📊 Analytics (Optioneel)

### Bezoeker Statistieken
Voeg toe aan `index.html` voor de `</head>` tag:

```html
<!-- Google Analytics (optioneel) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🌟 Pro Tips

### Custom Domain (Geavanceerd)
- Koop een domein zoals `aurelie-presentatie.nl`
- Voeg CNAME bestand toe aan repository
- Configureer DNS instellingen

### HTTPS
- GitHub Pages gebruikt automatisch HTTPS
- Altijd veilig voor school gebruik

### Mobile Friendly
- Presentatie werkt op tablets
- Test op verschillende schermformaten
- Responsive design ingebouwd

## 📞 Hulp Nodig?

### GitHub Support
- [GitHub Pages Documentatie](https://docs.github.com/en/pages)
- [GitHub Community Forum](https://github.community)

### Technische Hulp
1. Check GitHub repository settings
2. Kijk naar Actions tab voor errors
3. Test in verschillende browsers
4. Vraag om hulp van technisch persoon

---

**Succes met de deployment! 🚀**

*De presentatie zal prachtig werken op het smartboard in de klas!*
