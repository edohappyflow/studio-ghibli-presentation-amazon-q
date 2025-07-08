# Studio Ghibli Presentatie voor Aurélie

Een interactieve RevealJS presentatie over Studio Ghibli voor groep 4.

## 🎯 Presentatie Overzicht

- **Presentator:** Aurélie
- **Doelgroep:** ±30 klasgenoten en juf (groep 4)
- **Duur:** 10-15 minuten
- **Onderwerp:** Studio Ghibli en favoriete karakters

## 🚀 Snel Starten

### Lokaal Bekijken
1. Open `index.html` in je browser
2. Gebruik pijltjestoetsen om te navigeren
3. Druk op `F` voor fullscreen
4. Druk op `Escape` voor slide overzicht

### Online Deployment (GitHub Pages)
1. Upload bestanden naar GitHub repository
2. Activeer GitHub Pages in repository settings
3. Kies `main` branch als bron
4. Presentatie is beschikbaar op: `https://[username].github.io/[repository-name]`

## 📱 Navigatie

### Toetsenbord
- **Pijltjes:** Navigeer tussen slides
- **F:** Toggle fullscreen
- **Escape:** Slide overzicht
- **Spatie:** Volgende slide

### Touch/Smartboard
- **Swipe:** Links/rechts voor navigatie
- **Tap:** Klik op slide voor volgende fragment

## 🎨 Presentatie Structuur

### 1. Introductie (2 min)
- Openingsvraag over favoriete animatiefilms
- Persoonlijke introductie

### 2. Over Studio Ghibli (2 min)
- Wat is Studio Ghibli?
- Belangrijke kenmerken

### 3. Favoriete Figuren (6-8 min)
- **Totoro:** De bosgod
- **Ponyo:** Het magische visje
- **Gigi:** De pratende kat

### 4. Japan Connectie (2 min)
- Verbinding met andere Japanse interesses

### 5. Quiz (2 min)
- 4 interactieve vragen
- Multiple choice format

### 6. Afsluiting (1 min)
- Dankwoord en vragen

## 🖼️ Afbeeldingen Vervangen

Momenteel gebruikt de presentatie kleurrijke placeholders. Voor echte afbeeldingen:

### Benodigde Afbeeldingen
1. **Studio Ghibli Logo** (voor titelslide)
2. **Totoro afbeelding** (300x300px)
3. **Ponyo animated GIF** (300x300px)
4. **Gigi afbeelding** (300x300px)
5. **Kleine karakters** voor eindslide

### Vervangen
1. Plaats afbeeldingen in `images/` map
2. Vervang placeholder divs in `index.html`:
   ```html
   <!-- Van: -->
   <div class="placeholder-image totoro">🌳 TOTORO 🌳</div>
   
   <!-- Naar: -->
   <img src="images/totoro.jpg" alt="Totoro" class="character-img">
   ```

## 🎯 Presentatie Tips voor Aurélie

### Voor de Presentatie
- [ ] Oefen de presentatie 2-3 keer
- [ ] Test op het smartboard van tevoren
- [ ] Bereid antwoorden voor op mogelijke vragen
- [ ] Zorg voor backup (offline versie)

### Tijdens Presenteren
- **Timing:** Elke slide 1-2 minuten
- **Steekwoorden:** Gebruik bullets als geheugensteun
- **Interactie:** Stel vragen bij de quiz
- **Enthousiasme:** Laat je passie zien!
- **Ademhaling:** Rustig aan, diep ademhalen

### Technische Tips
- **Navigatie:** Gebruik pijltjestoetsen
- **Fullscreen:** F-toets voor volledig scherm
- **Overzicht:** Escape voor slide overzicht
- **Hulp:** Vraag om hulp als iets niet werkt

## 🔧 Technische Details

### Gebruikte Technologieën
- **RevealJS 4.3.1:** Presentatie framework
- **Google Fonts:** Nunito lettertype
- **CSS Grid/Flexbox:** Responsive layout
- **CSS Animaties:** Subtiele bewegingen

### Browser Ondersteuning
- Chrome/Edge (aanbevolen)
- Firefox
- Safari
- Werkt op tablets en smartboards

### Offline Gebruik
De presentatie werkt offline omdat alle resources via CDN worden geladen. Voor volledig offline gebruik:
1. Download RevealJS lokaal
2. Pas pad in `index.html` aan
3. Download Google Fonts lokaal

## 📋 Checklist voor Gebruik

### Voor de Presentatie
- [ ] Presentatie getest in browser
- [ ] Smartboard getest
- [ ] Internet connectie gecontroleerd
- [ ] Backup plan klaar
- [ ] Aurélie heeft geoefend

### Dag van Presentatie
- [ ] URL klaar: `https://[username].github.io/[repository-name]`
- [ ] Smartboard aangezet
- [ ] Browser geopend
- [ ] Fullscreen geactiveerd
- [ ] Eerste slide zichtbaar

## 🎨 Aanpassingen Maken

### Kleuren Wijzigen
Pas kleuren aan in `style.css`:
```css
/* Hoofdkleuren */
:root {
    --primary-color: #27ae60;
    --secondary-color: #2980b9;
    --accent-color: #e74c3c;
}
```

### Slides Toevoegen
Voeg nieuwe slides toe in `index.html`:
```html
<section data-background-color="#kleur">
    <h2>Nieuwe Slide Titel</h2>
    <p>Inhoud hier...</p>
</section>
```

### Animaties Aanpassen
Wijzig animatie-instellingen in JavaScript sectie:
```javascript
Reveal.initialize({
    transition: 'slide', // slide, fade, convex, concave
    transitionSpeed: 'default' // default, fast, slow
});
```

## 🐛 Problemen Oplossen

### Presentatie Laadt Niet
1. Controleer internet verbinding
2. Probeer andere browser
3. Check browser console voor errors
4. Gebruik lokale versie als backup

### Navigatie Werkt Niet
1. Klik eerst op presentatie
2. Probeer verschillende toetsen
3. Gebruik muis/touch als alternatief
4. Herlaad pagina

### Afbeeldingen Tonen Niet
1. Controleer bestandspaden
2. Zorg dat afbeeldingen bestaan
3. Check bestandsrechten
4. Placeholders werken altijd als backup

## 📞 Ondersteuning

Voor technische vragen of problemen:
1. Check deze README eerst
2. Test in verschillende browsers
3. Maak GitHub issue aan
4. Vraag om hulp van technisch persoon

## 🌟 Succes!

Veel succes met de presentatie, Aurélie! Je gaat het geweldig doen! 

De presentatie is gemaakt met liefde en zorg, net zoals Studio Ghibli films. Laat je passie voor deze magische verhalen zien! ✨

---

*Made with ❤️ for Aurélie's first presentation*
