# Vil du bli min valentin? 💕

En interaktiv Valentine's-app der "Nei"-knappen rømmer fra musepekeren.

## Slik bruker du den

### 1. Legg inn din personlige melding og bilde

Åpne `index.html` og endre disse to variablene øverst i `<script>`-blokken:

```js
const PERSONAL_MESSAGE = "Din personlige melding her";
const IMAGE_PATH = "bilde.jpg";
```

- **PERSONAL_MESSAGE** – Meldingen som vises på feiringsskjermen
- **IMAGE_PATH** – Filnavn eller URL til bildet du vil vise (legg bildefilen i samme mappe som `index.html`)

### 2. Deploy

#### Alternativ 1: GitHub Pages (anbefalt)
1. Opprett et GitHub-repo (kan være privat med Pages aktivert)
2. Push `index.html` og `bilde.jpg`
3. Gå til repo → Settings → Pages → velg `main` branch
4. Del URL-en med henne

#### Alternativ 2: Netlify Drop
1. Gå til https://app.netlify.com/drop
2. Dra og slipp mappen med `index.html` og bildet
3. Få en URL å dele

#### Alternativ 3: Send filen direkte
1. Legg `index.html` og `bilde.jpg` i samme mappe
2. Zip mappen og send til henne
3. Hun pakker ut og åpner `index.html` i nettleseren
