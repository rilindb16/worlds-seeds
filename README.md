# Worlds Seeds — voorbeeldontwerp

Eén statische pagina als voorbeeld van een zadenwebshop, opgezet in dezelfde structuur als
[mullerseeds.nl](https://mullerseeds.nl/): categorienavigatie met uitklapmenu's, hero, USP's,
categorietegels, productkaarten met artikelnummer en staffelprijs, kortingsstaffel, A–Z zadenindex,
over ons, contactformulier en footer.

Bedoeld om aan de klant te laten zien, nog niet om live te gaan.

## Bestanden

- `index.html` — de volledige pagina (HTML, CSS en JS in één bestand)
- `img/` — 15 foto's

Geen build-stap, geen dependencies. Dubbelklik `index.html` om hem lokaal te bekijken.

## Wat werkt

- Zoeken filtert de productlijst (zowel het veld in de header als dat boven de lijst)
- Staffelcalculator: 1.000 / 5.000 / 10.000 zaden → prijs per zaad en ordertotaal
- Winkelwagen telt regels en bedrag op
- Uitklapmenu's, mobiel menu, A–Z index, catalogusformulier, kopieerknoppen
- Taalkeuze Nederlands ↔ Armeens (Հայերեն); de keuze wordt onthouden in de browser

## Nog te vervangen voor oplevering

- Bedrijfsnaam, teksten, prijzen, artikelnummers en contactgegevens zijn voorbeeldmateriaal
- De foto's zijn vrije-licentiefoto's van Wikimedia Commons (verantwoording staat in de footer).
  Vervang ze door eigen productfoto's: zelfde bestandsnaam in `img/` en klaar.
- De gele balk bovenaan de pagina markeert dit als voorbeeld en kan eruit

## Aanpassen

Kleuren, lettertypen en afrondingen staan als tokens bovenaan het `:root`-blok in `index.html`.
De Armeense vertalingen staan in het object `HY` onderin het script; elke tekst met een
`data-i18n`-attribuut in de HTML heeft daar een regel.
