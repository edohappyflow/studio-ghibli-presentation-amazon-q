# Git Workflow - Studio Ghibli Presentatie

## 🌿 Branch Structuur

### `main` - Productie Versie
- **Doel:** Stabiele, geteste versie voor Aurélie's presentatie
- **Gebruik:** GitHub Pages deployment
- **Status:** Altijd werkend en presentatie-klaar

### `development` - Ontwikkeling
- **Doel:** Nieuwe features en wijzigingen
- **Gebruik:** Experimenteren en verbeteren
- **Status:** Kan instabiel zijn tijdens ontwikkeling

### Feature Branches (optioneel)
- `feature/images` - Echte afbeeldingen toevoegen
- `feature/animations` - Extra animaties
- `feature/audio` - Geluid effecten
- `feature/quiz-improvements` - Quiz verbeteringen

## 🔄 Workflow Stappen

### 1. Wijzigingen Maken
```bash
# Ga naar development branch
git checkout development

# Maak wijzigingen in bestanden
# Test lokaal in browser

# Voeg wijzigingen toe
git add .
git commit -m "✨ Beschrijving van wijziging"
```

### 2. Testen en Valideren
```bash
# Test presentatie lokaal
open index.html

# Controleer alle slides
# Test navigatie
# Valideer responsive design
```

### 3. Naar Productie (main)
```bash
# Ga naar main branch
git checkout main

# Merge development
git merge development

# Push naar GitHub (voor GitHub Pages)
git push origin main
```

## 📝 Commit Message Conventies

### Emoji Prefixes
- 🎬 **Presentatie:** Nieuwe slides of grote wijzigingen
- ✨ **Features:** Nieuwe functionaliteit
- 🎨 **Styling:** CSS en design wijzigingen
- 🐛 **Bugfix:** Fout reparaties
- 📝 **Docs:** Documentatie updates
- 🔧 **Config:** Configuratie wijzigingen
- 🖼️ **Images:** Afbeelding updates
- 🚀 **Deploy:** Deployment gerelateerd

### Voorbeelden
```bash
git commit -m "🎬 Nieuwe Totoro slide toegevoegd met animaties"
git commit -m "✨ Quiz interactiviteit verbeterd"
git commit -m "🎨 Studio Ghibli kleuren aangepast"
git commit -m "🐛 Navigatie bug op mobile opgelost"
git commit -m "📝 README instructies uitgebreid"
git commit -m "🖼️ Ponyo GIF toegevoegd"
```

## 🏷️ Versie Tags

### Semantische Versioning
- **v1.0.0** - Eerste complete versie
- **v1.1.0** - Nieuwe features (bijv. echte afbeeldingen)
- **v1.0.1** - Bug fixes
- **v2.0.0** - Grote wijzigingen

### Tag Maken
```bash
# Tag huidige versie
git tag -a v1.0.0 -m "🎬 Eerste complete Studio Ghibli presentatie"

# Push tags naar GitHub
git push origin --tags
```

## 🚀 GitHub Integration

### Repository Setup
```bash
# Voeg GitHub remote toe
git remote add origin https://github.com/[username]/studio-ghibli-presentation.git

# Push eerste keer
git push -u origin main
git push origin development
```

### GitHub Pages Deployment
- **Branch:** `main` wordt automatisch gedeployed
- **URL:** `https://[username].github.io/studio-ghibli-presentation`
- **Update tijd:** 2-5 minuten na push

## 📋 Dagelijkse Workflow

### Voor Wijzigingen
```bash
# 1. Check huidige status
git status

# 2. Ga naar development
git checkout development

# 3. Pull laatste wijzigingen (als je met team werkt)
git pull origin development
```

### Na Wijzigingen
```bash
# 1. Voeg bestanden toe
git add .

# 2. Commit met duidelijke message
git commit -m "✨ Beschrijving van wijziging"

# 3. Test lokaal
open index.html

# 4. Push naar development
git push origin development
```

### Voor Presentatie
```bash
# 1. Merge naar main
git checkout main
git merge development

# 2. Test finale versie
open index.html

# 3. Deploy naar GitHub Pages
git push origin main

# 4. Tag versie
git tag -a v1.0.0 -m "🎬 Klaar voor Aurélie's presentatie"
git push origin --tags
```

## 🔍 Nuttige Git Commando's

### Status Checken
```bash
git status              # Huidige status
git log --oneline       # Commit geschiedenis
git branch -a           # Alle branches
git diff                # Wijzigingen bekijken
```

### Branch Management
```bash
git checkout main       # Naar main branch
git checkout development # Naar development branch
git checkout -b feature/nieuwe-feature # Nieuwe branch maken
git branch -d feature/oude-feature     # Branch verwijderen
```

### Wijzigingen Ongedaan Maken
```bash
git checkout -- bestand.html    # Bestand terugzetten
git reset HEAD~1                 # Laatste commit ongedaan maken
git stash                        # Wijzigingen tijdelijk opslaan
git stash pop                    # Wijzigingen terughalen
```

## 🛡️ Backup Strategie

### Lokale Backups
```bash
# Maak backup van hele project
cp -r . ../studio-ghibli-backup-$(date +%Y%m%d)

# Export git repository
git bundle create studio-ghibli-backup.bundle --all
```

### Cloud Backups
- **GitHub:** Automatische backup in cloud
- **GitLab:** Mirror repository (optioneel)
- **Bitbucket:** Extra backup locatie

## 📊 Project Geschiedenis Tracken

### Belangrijke Milestones
- **v1.0.0:** Eerste complete presentatie
- **v1.1.0:** Echte afbeeldingen toegevoegd
- **v1.2.0:** Audio effecten toegevoegd
- **v2.0.0:** Interactieve elementen uitgebreid

### Release Notes Template
```markdown
## v1.1.0 - Afbeeldingen Update

### ✨ Nieuwe Features
- Echte Studio Ghibli afbeeldingen
- Ponyo animated GIF
- Verbeterde character slides

### 🎨 Styling
- Betere afbeelding positioning
- Responsive image scaling

### 🐛 Bug Fixes
- Mobile navigatie verbeterd
- Loading tijd geoptimaliseerd
```

## 🎯 Voor Aurélie

### Eenvoudige Workflow
1. **Wijzigingen maken:** Bewerk bestanden
2. **Testen:** Open `index.html` in browser
3. **Opslaan:** `git add . && git commit -m "Beschrijving"`
4. **Online zetten:** `git push origin main`

### Hulp Nodig?
- **Status checken:** `git status`
- **Geschiedenis:** `git log --oneline`
- **Hulp:** `git help [commando]`

---

## 🌟 Voordelen van Git

### Voor dit Project
- **Versiebeheer:** Alle wijzigingen bijgehouden
- **Backup:** Nooit werk kwijt
- **Samenwerking:** Meerdere mensen kunnen helpen
- **Deployment:** Automatisch naar GitHub Pages
- **Geschiedenis:** Zie wat wanneer is veranderd

### Voor Aurélie's Leerproces
- **Experimenteren:** Veilig nieuwe dingen proberen
- **Terugkeren:** Altijd terug naar werkende versie
- **Delen:** Makkelijk presentatie delen
- **Professioneel:** Leren werken zoals echte developers

**Git maakt de presentatie professioneel en veilig! 🚀**
