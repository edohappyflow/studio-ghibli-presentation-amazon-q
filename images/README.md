# Afbeeldingen voor Studio Ghibli Presentatie

## Benodigde Afbeeldingen

### 1. Studio Ghibli Logo
- **Bestandsnaam:** `studio-ghibli-logo.png`
- **Afmetingen:** 400x200px (ongeveer)
- **Gebruik:** Titelslide
- **Beschrijving:** Officieel Studio Ghibli logo

### 2. Totoro
- **Bestandsnaam:** `totoro.jpg` of `totoro.png`
- **Afmetingen:** 300x300px
- **Gebruik:** Totoro karakter slide
- **Beschrijving:** Afbeelding van Totoro, bij voorkeur staand of zittend

### 3. Ponyo (Animated GIF)
- **Bestandsnaam:** `ponyo.gif`
- **Afmetingen:** 300x300px
- **Gebruik:** Ponyo karakter slide
- **Beschrijving:** Bewegende afbeelding van Ponyo, bijvoorbeeld zwemmend of rennend

### 4. Gigi
- **Bestandsnaam:** `gigi.jpg` of `gigi.png`
- **Afmetingen:** 300x300px
- **Gebruik:** Gigi karakter slide
- **Beschrijving:** Afbeelding van Gigi de zwarte kat

### 5. Kleine Karakters (Optioneel)
- **Bestandsnamen:** `totoro-small.png`, `ponyo-small.png`, `gigi-small.png`
- **Afmetingen:** 100x100px
- **Gebruik:** Eindslide
- **Beschrijving:** Kleine versies voor de afsluiting

## Afbeeldingen Toevoegen

### Stap 1: Afbeeldingen Plaatsen
1. Download de gewenste afbeeldingen
2. Hernoem ze volgens bovenstaande bestandsnamen
3. Plaats ze in deze `images/` map

### Stap 2: HTML Aanpassen
Vervang de placeholder divs in `index.html`:

#### Titelslide Logo
```html
<!-- Vervang: -->
<div class="studio-ghibli-logo">🎬</div>

<!-- Door: -->
<img src="images/studio-ghibli-logo.png" alt="Studio Ghibli Logo" class="studio-ghibli-logo">
```

#### Totoro Afbeelding
```html
<!-- Vervang: -->
<div class="placeholder-image totoro">🌳 TOTORO 🌳</div>

<!-- Door: -->
<img src="images/totoro.jpg" alt="Totoro" class="character-img">
```

#### Ponyo GIF
```html
<!-- Vervang: -->
<div class="placeholder-gif ponyo">🐠 PONYO GIF 🐠<br><small>(Animated gif komt hier)</small></div>

<!-- Door: -->
<img src="images/ponyo.gif" alt="Ponyo" class="character-img">
```

#### Gigi Afbeelding
```html
<!-- Vervang: -->
<div class="placeholder-image gigi">🐱 GIGI 🐱</div>

<!-- Door: -->
<img src="images/gigi.jpg" alt="Gigi" class="character-img">
```

### Stap 3: CSS Aanpassen
Voeg deze CSS toe aan `style.css`:

```css
/* Afbeelding styling */
.character-img {
    width: 300px;
    height: 300px;
    object-fit: cover;
    border-radius: 20px;
    box-shadow: 0 6px 20px rgba(0,0,0,0.2);
    transition: transform 0.3s ease;
}

.character-img:hover {
    transform: scale(1.05);
}

.studio-ghibli-logo img {
    max-width: 400px;
    height: auto;
}
```

## Copyright Informatie

### Belangrijk!
- Studio Ghibli afbeeldingen zijn auteursrechtelijk beschermd
- Gebruik alleen voor educatieve doeleinden (schoolpresentatie)
- Niet voor commercieel gebruik
- Geef altijd bronvermelding

### Bronnen voor Afbeeldingen
- **Officiële Studio Ghibli website**
- **Wikipedia (Creative Commons afbeeldingen)**
- **Fan art (met toestemming)**
- **Screenshots uit films (fair use voor educatie)**

### Bronvermelding
Voeg toe aan de laatste slide:
```
Afbeeldingen gebruikt met dank aan Studio Ghibli
Voor educatieve doeleinden - Groep 4 presentatie
```

## Alternatieve Oplossingen

### Als je geen afbeeldingen kunt vinden:
1. **Gebruik de huidige placeholders** - Ze zijn kleurrijk en duidelijk
2. **Teken zelf** - Aurélie houdt van tekenen!
3. **Gebruik emoji** - Simpel maar effectief
4. **Maak collages** - Combineer verschillende elementen

### Placeholder Verbeteren
Je kunt de huidige placeholders mooier maken door:
- Meer emoji's toe te voegen
- Kleuren aan te passen
- Tekst te verbeteren
- Animaties toe te voegen

## Checklist

- [ ] Studio Ghibli logo gevonden
- [ ] Totoro afbeelding gedownload
- [ ] Ponyo GIF gevonden
- [ ] Gigi afbeelding gedownload
- [ ] Afbeeldingen hernoemd
- [ ] Afbeeldingen geplaatst in images/ map
- [ ] HTML aangepast
- [ ] CSS toegevoegd
- [ ] Presentatie getest
- [ ] Copyright gecontroleerd

---

*Tip: Test altijd de presentatie na het toevoegen van afbeeldingen om er zeker van te zijn dat alles goed werkt!*
