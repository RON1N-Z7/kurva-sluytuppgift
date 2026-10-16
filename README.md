# Smakbudet

Smakbudet är en responsiv webbprototyp för en tjänst som samlar restauranger och lokala matställen på ett ställe. Besökare kan utforska olika matkategorier, se exempel på restauranger och rätter samt läsa om projektet och jämföra matleveranstjänster.

## Funktioner

- Startsida med utvalda restauranger och länkar till matkategorier.
- Menysidor för italiensk mat, snabbmat, asiatisk mat och vegetarisk mat.
- Exempelmenyer med rättbeskrivningar, priser och uppskattade leveranstider.
- Sidor med information om Smakbudet, projektgruppen och en jämförelse av leveranstjänster.
- Responsiv navigation med en mobilmeny.
- Tillgänglighetsdetaljer som alternativa bildtexter och länkar för att hoppa till huvudinnehållet.

## Teknik

- HTML5
- CSS3
- JavaScript för mobilmenyn

Projektet är en statisk frontendprototyp och använder ingen backend eller databas. Restauranger, priser och leveranstider är exempeldata; det går inte att lägga en faktisk beställning.

## Kom igång

Klona repot och öppna `index.html` i en webbläsare:

```bash
git clone <repository-url>
cd <repository-folder>
```

Öppna sedan `index.html`. Du kan också öppna projektmappen i Visual Studio Code och använda tillägget Live Server för lokal förhandsvisning.

## Projektstruktur

```text
.
├── index.html          # Startsida
├── pizza.html          # Italiensk mat
├── snabbmat.html       # Snabbmat
├── asian.html          # Asiatisk mat
├── veg.html            # Vegetarisk mat
├── omOss.html          # Om Smakbudet
├── jamforelse.html     # Jämförelse av tjänster
├── kontakt.html        # Projektgruppens kontaktuppgifter
├── css/                # Stilmallar
└── Images/             # Bilder och övriga tillgångar
```

Vissa typsnitt och bilder hämtas från externa tjänster och kräver internetanslutning.
