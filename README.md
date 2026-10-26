# Worlds Seeds — voorbeeldontwerp

Eén statische pagina als voorbeeld van een zadenwebshop, opgezet in dezelfde structuur als
[mullerseeds.nl](https://mullerseeds.nl/): categorienavigatie met uitklapmenu's, hero, USP's,
categorietegels, productkaarten met artikelnummer en staffelprijs, kortingsstaffel, A–Z zadenindex,
over ons, contactformulier en footer.

Bedoeld om aan de klant te laten zien, nog niet om live te gaan.

## Bestanden

- `index.html` — de volledige pagina (HTML, CSS en JS in één bestand, een volwaardig
  HTML-document met eigen `<head>` en viewport-regel)
- `img/` — 15 foto's

Geen build-stap, geen dependencies. Dubbelklik `index.html` om hem lokaal te bekijken.

## Wat werkt

- Zoeken filtert de productlijst (zowel het veld in de header als dat boven de lijst)
- Staffelcalculator: 1.000 / 5.000 / 10.000 zaden → prijs per zaad en ordertotaal
- Winkelwagen telt regels en bedrag op
- Uitklapmenu's, mobiel menu, A–Z index, catalogusformulier, kopieerknoppen
- Taalkeuze Nederlands, Engels, Armeens (Հայերեն) en Russisch; de keuze wordt onthouden in de browser

## Nog te vervangen voor oplevering

- Bedrijfsnaam, teksten, prijzen, artikelnummers en contactgegevens zijn voorbeeldmateriaal
- De foto's zijn vrije-licentiefoto's van Wikimedia Commons (verantwoording staat in de footer).
  Vervang ze door eigen productfoto's: zelfde bestandsnaam in `img/` en klaar.
- De gele balk bovenaan de pagina markeert dit als voorbeeld en kan eruit

## Tweede voorbeeld: `wijnhandel-demo/`

Een los voorbeeld in een heel ander genre en een heel andere vormgeving: **Clos & Kelder**, een
verzonnen Belgische wijnhandel, in de lijn van [vineo.be](https://www.vineo.be/). Donkere
uitstraling, webshop met kleurfilter, spijs-en-wijnkiezer, proeverijen met reservering,
cadeaubon en een taalkeuze Nederlands, Frans, Engels en Russisch. Zelfde opzet: één `index.html` plus een map `img/`.

Via GitHub Pages komt dit voorbeeld op `/wijnhandel-demo/` te staan. Wil je er een losse site van
maken, verplaats de map dan naar een eigen repo.

## Aanpassen

Kleuren, lettertypen en afrondingen staan als tokens bovenaan het `:root`-blok in `index.html`.
De vertalingen staan in de objecten `EN`, `HY` en `RU` onderin het script; elke tekst met een
`data-i18n`-attribuut in de HTML heeft daar een regel.
