# Dwarsprofiel Maker

Interactieve tool om **grondprofielen (dwarsprofielen)** te tekenen en over een kaart te leggen —
inclusief ontgravingssleuf, bodemlagen, leidingen en grond**depots** (grondhopen).

👉 **Live: https://pietoff.github.io/Dwarsprofiel/**

Alles draait in de browser. Er wordt niets geüpload: de kaart die je inlaadt en de tekening
blijven volledig lokaal op je eigen computer.

## Wat kan je ermee

- **Achtergrondkaart** inladen als **PNG, JPG of PDF** (bijvoorbeeld een uitsnede uit GIS of een
  tekening-PDF) en het profiel eroverheen slepen en schalen. Bij een PDF met meerdere pagina's
  kies je welke pagina je gebruikt.

  > De PDF-lezer (pdf.js) wordt eerst naast `index.html` gezocht en anders van cdnjs gehaald.
  > Blokkeert je netwerk cdnjs, zet dan `pdf.min.js` en `pdf.worker.min.js` (pdf.js 3.11.174)
  > naast `index.html`; ze worden dan automatisch gebruikt. PNG/JPG werkt altijd zonder internet.
- **Bodemlagen** toevoegen met diepte van/tot, kleur en een omschrijving over meerdere regels.
- **Depots**: er zijn twee depots. Kies per laag naar welk depot de ontgraven grond gaat
  (of "Geen" als de laag niet wordt ontgraven). Elk depot wordt als driehoekige grondhoop naast
  de sleuf getekend, links of rechts, met een eigen naam. Meerdere lagen in één depot worden als
  gemengde hoop met gestapelde kleurbanden weergegeven; een leeg depot wordt niet getekend.
- **Leiding** in de sleuf tekenen met eigen kleur en naam.
- **Rode locatiepijl** over de kaart, met versleepbare uiteinden en instelbare dikte.
- **Toelichting** onder de legenda (standaard: de grond wordt na afloop in hetzelfde grondprofiel teruggeplaatst).
- **Exporteren** als **PNG of PDF**: het losse profiel, of de volledige kaart inclusief profiel en pijl.
  PDF op tekeninggrootte of passend op A4 (staand/liggend). Geen externe libraries — de PDF wordt in de browser zelf opgebouwd.

## Gebruik

Open de live-link hierboven, of download `index.html` en open het bestand lokaal in je browser.
Eén bestand, geen installatie, geen afhankelijkheden.

## Werkvolgorde

1. Laad een achtergrondkaart in.
2. Voeg de bodemlagen toe (van/tot, kleur, omschrijving) en wijs ze toe aan een depot.
3. Vink **Toon depots** aan en stel per depot de naam en de kant (links/rechts) in.
4. Sleep het profiel en de rode pijl naar de juiste plek op de kaart en stel de grootte in.
5. Download het resultaat als PNG of PDF.
