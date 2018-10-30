# Guapa-TestOpdracht-v2

Vanwege een fatale computercrash en het verlies van de database ben ik in een nieuwe Magento installatie en repository verder gegaaan. De eerste repository en daarbij behorende commits kunnen bekeken worden op https://github.com/Ahura81/guapa_test

Trello board: https://trello.com/b/qHy2dQDe/guapatest


Opdracht:

Criteria:

- Magento 2 installatie
- Magento Blank thema
- Knot module namespacing (voorbeeld: Knot_{module-naam})
- Twee aparte modules (per opdracht één)

Tips & tricks:

- Alle cache typen op status "enabled", behalve de "Blocks HTML output" en "Page Cache"
- Zet je applicatie in "developer mode" tijdens het ontwikkelen
- Optioneel: Installeer en configureer je sample data
- Let op: Magento heeft veel componenten al op de plank liggen. Hierover is enorm veel documentatie beschikbaar (zie Magento   DevDocs). Neem andere modules, die ongeveer dat doen waarnaar jij op zoek bent, goed door om zo bij de juiste aanvliegroute   uit te komen

Subtaak #1: 
Previous tab op PDP Elke product pagina bevat onderin twee tabbladen genaamd “Details” en “Reviews”. Er moet een extra tab  bijgebouwd worden genaamd “Previous”, waarin de producten komen te staan die je als laatst hebt bekeken. De looks hiervan kunnen gebaseerd worden op het grid van de categorie pagina met maximaal vier naast elkaar.

Belangrijk: Als je producten meerdere malen hebt bekeken, dan hoeft die maar 1x in de grid zichtbaar te worden.

Subtaak #2: 
Previous tab op CAP Als je bent ingelogd als klant, moet er op de account pagina een extra tab bijgebouwd worden waarin dezelfde content zichtbaar wordt maar dan in een tabelvorm. Hier wil je de laatste 10 producten zichtbaar maken.

De product informatie die zichtbaar moet zijn:

- Naam 
- SKU
- Prijs
- Bekijk product knop Belangrijk: Als je producten meerdere malen hebt bekeken, dan hoeft die maar 1x in de grid zichtbaar te worden.

Subtaak #3: 
Publicatie en screencast Maak tussentijds meerdere git commits met duidelijke omschrijvingen. Push de gemaakte code naar een publieke Github repository. Daarnaast wordt er een screencast verwacht waarin je stapsgewijs je eindproduct demonstreert. Fleur je screencast indien mogelijk op met achtergrondmuziek naar keuze.
