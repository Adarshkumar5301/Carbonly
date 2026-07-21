# Carbonly

A browser-based carbon comparison tool. Capture or upload a photo, confirm the item, view a source-labelled footprint estimate, compare a lower-impact option, and keep a private local record of choices.

## Run

Open `index.html` in a modern browser. On phones, the photo control can launch the rear camera. No account, server, or tracker is required for the core app; saved choices remain in the browser.

## Sources and method

- **Food** — global average life-cycle emissions from Poore & Nemecek (2018), processed by [Our World in Data](https://ourworldindata.org/grapher/ghg-per-kg-poore). Food quantities in Carbonly are 100 g portions, so the published per-kilogram factor is divided by ten.
- **Travel and electricity** — the [UK Government 2026 greenhouse-gas conversion factors](https://www.gov.uk/government/publications/greenhouse-gas-reporting-conversion-factors-2026). The electricity figure combines generation, transmission/distribution, and upstream factors for the UK, so it should not be used as a global grid factor.

These are comparison estimates, not product-specific life-cycle assessments. Food impacts can vary substantially by producer, location, and practice.

## Photo recognition

The app captures and previews real photos but requires the user to confirm what is shown. Reliable recognition of arbitrary objects needs an external vision service and a secure server-side API key; no secret is embedded in this static application.
