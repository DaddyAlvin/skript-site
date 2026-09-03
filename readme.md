# Mineskript – webbsida för skriptnedladdning

Mineskript är en webbplats utvecklad av **Sandgrens dev** för att distribuera skript för Hypixel SkyBlock[cite: 1]. Webbsidan erbjuder en responsiv miljö för nedladdning av skriptfiler samt information om installation, felsökning och funktionalitet[cite: 6, 8].

## Funktioner

- **Säker filmappning:** JavaScript-modulen `filestorage.js` döljer de faktiska filvägarna i HTML-koden.
- **Interaktiv modal:** Visar installationsinstruktioner när en användare startar en nedladdning[cite: 6, 7].
- **Versionshantering:** Erbjuder både den senaste versionen (`v3.14`) och den stabila versionen (`v3.1`)[cite: 6].
- **Modulär CSS:** Källkoden är uppdelad i separata stilfiler för grundstilar, komponenter, nedladdningssidan och flödesscheman.
- **Responsiv design:** Layouten anpassar sig efter olika skärmstorlekar och mobila enheter[cite: 2, 3, 5, 10].

## Filstruktur

### HTML

- `index.html` – Startsida med ett visuellt flödesschema[cite: 3, 10].
- `download.html` – Nedladdningssida med kort för tillgängliga skriptversioner[cite: 6].
- `guide.html` – Steg-för-steg guide för installation och användning[cite: 1, 3, 4, 6, 8].
- `extrainfo.html` – Information om förutsättningar, felsökning och versionsskillnader[cite: 8].
- `about.html` – Presentationssida för utvecklaren Sandgrens dev och projektets mål[cite: 1].
- `contact.html` – Kontaktsida med e-post och telefonnummer till Alvin Sandgren[cite: 4].

### JavaScript

- `download.js` – Skapar tillfälliga nedladdningslänkar och hanterar bekräftelsemodaler[cite: 7].
- `filestorage.js` – Innehåller `fileMapping`, som pekar ut `.ahk`-filer baserat på versions-ID[cite: 9].

### CSS

- `base.css` – Typografi, bakgrund samt stilar för header och footer[cite: 2].
- `components.css` – Stilar för navigeringsknappar, informationskort, modaler och videokontainrar[cite: 3].
- `download.css` – Stilar för nedladdningskort, badges och interaktiva nedladdningsknappar[cite: 5].
- `flowchart.css` – Stilregler och visuella kopplingslinjer för flödesschemat[cite: 10].

## Installation och lokal utveckling

Eftersom projektet använder ES6-moduler (`import`/`export` i JavaScript) krävs en lokal webbserver för utveckling[cite: 7].

1. Klona repositoryt:
   ```bash
   git clone [https://github.com/DaddyAlvin/Script-download-page.git](https://github.com/DaddyAlvin/Script-download-page.git)


## TeknikstackHTML5:
Semantisk uppbyggnad med anpassade meta-taggar och data-*-attribut.  

CSS3: Flexbox, CSS Grid, media queries och CSS-variabler[cite: 2, 3, 5, 10].

JavaScript (ES6 Modules): Modulär kodstruktur med import och export för nedladdningshantering[cite: 7, 9].

## Kontakt och supportUtvecklare: 
Alvin Sandgren / Sandgrens dev 
E-post: info@skript.se  
Telefon: 070-29 55 107  
GitHub Repository: DaddyAlvin/Script-download-page