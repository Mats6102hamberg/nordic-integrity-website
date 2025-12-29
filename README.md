# Nordic Integrity System AB 

Officiell hemsida för **Enterprise Research Shield** (ERS)

## Projektbeskrivning

ERS (Enterprise Research Shield) är ett enterprise-säkerhetssystem för känsliga dokument, utvecklat av Nordic Integrity Systems AB. Systemet möjliggör säker analys och avkodning av känslig information utan att data lämnar kundens kontrollerade miljö.

### Nyckelfunktioner

- **ERS Memory Vault** – Isolerad lokal inlärning och analys
- **Koda Trust Score** – Kontinuerlig säkerhetsmätning i realtid
- **Självläkande system** – Automatisk driftshantering
- **Naturligt språk** – Loggar på svenska, engelska och tyska
- **Data containment** – All data stannar i kundens miljö
- **Virusskyddsintegration** – Samverkan med befintliga antiviruslösningar

## Företagsinformation

**Nordic Integrity Systems AB**
_"Insikter utan insyn."_

ERS är specifikt utformat för sjukvård, myndigheter och organisationer där sekretess är lagstadgad. Passar utmärkt för medelstora, stora och globala företag.

## Språkstöd

Webbplatsen har inbyggt språkstöd för:
- 🇸🇪 Svenska (standard)
- 🇬🇧 Engelska

Språkväxling sker via knappar i navigationsfältet, och användarens val sparas lokalt i webbläsaren.

## Nedladdningsbara dokument

Projektet innehåller PDF-filer tillgängliga för nedladdning direkt från webbplatsen:

### Kort översikt (OnePagers)
- 🇸🇪 [`docs/ERS-OnePager-SV.pdf`](docs/ERS-OnePager-SV.pdf) - Svenska
- 🇬🇧 [`docs/ERS-OnePager-EN.pdf`](docs/ERS-OnePager-EN.pdf) - Engelska
- 🇩🇪 [`docs/ERS-OnePager-DE.pdf`](docs/ERS-OnePager-DE.pdf) - Tyska

### Fullständig information (Informationsblad)
- 🇸🇪 [`docs/ERS-Informationsblad-SV.pdf`](docs/ERS-Informationsblad-SV.pdf) - Svenska
- 🇬🇧 [`docs/ERS-Informationsblad-EN.pdf`](docs/ERS-Informationsblad-EN.pdf) - Engelska
- 🇩🇪 [`docs/ERS-Informationsblad-DE.pdf`](docs/ERS-Informationsblad-DE.pdf) - Tyska

## Teknisk information

- **Typ**: Single-page application (SPA)
- **Format**: Standalone HTML-fil med inbäddad CSS och JavaScript
- **Beroenden**: Google Fonts (DM Sans, Playfair Display)
- **Hosting**: GitHub Pages
- **Jekyll**: Inaktiverad (via `.nojekyll`)

## Installation för utveckling

Projektet är en statisk webbsida och kräver ingen byggprocess:

```bash
# Klona repositoryt
git clone https://github.com/[ditt-användarnamn]/ers-website.git

# Öppna direkt i webbläsare
open index.html
```

För lokal utveckling kan du använda en enkel HTTP-server:

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve

# Sedan besök: http://localhost:8000
```

## Deploy till GitHub Pages

1. Pusha till GitHub
2. Gå till Repository Settings → Pages
3. Välj Source: `main` branch, `/ (root)` folder
4. Webbplatsen publiceras på: `https://[ditt-användarnamn].github.io/ers-website/`

## Kontaktinformation

**Mats Hamberg**
Grundare och ansvarig VD
📧 info@nordicintegrity.se
📞 070-037 74 59

---

© 2025 Nordic Integrity Systems AB. Alla rättigheter förbehållna.
