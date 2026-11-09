# Good Luck to the Barley Mow · Prendre un verre de bière mon minou

A bilingual web book on brewing Canada's beers, from New France to today: the history of brewing in Canada, its sources, and 41 recipes you can scale to your own equipment.

Un livre Web bilingue sur le brassage des bières du Canada, de la Nouvelle-France à aujourd'hui : l'histoire, les sources et 41 recettes ajustables à votre équipement.

- **English:** https://www.davidpepin.ca/beer-history/en/
- **Français :** https://www.davidpepin.ca/beer-history/fr/

## What's in it

- Background chapters: humans and alcohol, how beer is made, and a simple brew-in-a-bag method for beginners.
- Canada's beers by era: traditional home brews; British and German influences and industrialization; Americanization and uniformity; the craft beer revival.
- 41 recipes, each a brew sheet. Set your batch volume, efficiency, boil-off and kettle size under **My equipment**, and the grain, hop and water amounts are recalculated. Metric or US imperial units. Recipes can be exported as BeerXML for Brewfather, BeerSmith and similar apps.
- A short glossary, and notes and references.
- Light and dark themes.

## How this repository works

Each language is one self-contained HTML page (text, recipe data and scripts inlined). There is no build step here: GitHub Pages serves the files as they are.

| Path | What it is |
|---|---|
| `en/index.html`, `fr/index.html` | The book, in each language |
| `en/og-image.png`, `fr/og-image.png` | Preview image for social media links |
| `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png` | Icons |

The pages are generated from a separate working folder (chapters in HTML, recipes in YAML, a Python build script) and copied here.

## Credits

Research, writing and direction: David Pepin. Coded with Claude (Anthropic). Part of [davidpepin.ca/projects](https://www.davidpepin.ca/projects/).

The published pages load Google Analytics (page views only, same property as davidpepin.ca). The tag only runs on davidpepin.ca, not when you open a file locally.
