# Website Sportwetenschappen (kopie van sportfolio-test)

`index.html` is de volledige site in één bestand. Open het in een browser of zet het op een webserver.

## Video's en documenten koppelen

De oorspronkelijke Google Site toont video's en documenten vanuit Google Drive. Hun Drive-links zijn niet publiek uit te lezen, dus ze staan nu als "nog te koppelen" op de site.

Zo koppel je er een:

1. Zoek in `index.html` de bestandsnaam, bijvoorbeeld `koprol voorwaarts eindvorm.mp4`.
2. Kopieer in Google Drive de deellink van dat bestand (zet delen op "Iedereen met de link" binnen de school of publiek).
3. Neem het ID uit de link: het stuk tussen `/d/` en `/view`.
4. Voeg het toe als derde waarde:
   `V("eindvorm 1: koprol voorwaarts","koprol voorwaarts eindvorm.mp4","HIER_HET_ID")`

Heb je het videobestand zelf? Zet het in de map `video/` naast `index.html` en gebruik `"video/bestandsnaam.mp4"` als derde waarde.

Video's worden dan in de pagina afgespeeld. Documenten (`F(...)`) krijgen een knop "Openen".

## Pagina's toevoegen

Elke pagina is één regel `pg("id", "bovenliggende-id", "Titel", [inhoud])`. Het menu, het kruimelpad en de zoekfunctie worden er automatisch uit opgebouwd.

## Wat afwijkt van het origineel

- De pagina "ademhaling" (zwemmen, remediëring borstcrawl) is herschreven op basis van de inhoud. De letterlijke tekst kon niet uitgelezen worden.
- Bij "Blok 4 herenbrug" en "Blok 4 sprong" stond op de originele site de titel "Blok 4 grond". In de kopie staat de juiste titel.
- Bij "bevrijdingscombinaties" hoort de video van "pols langs zijkant" in het origineel bij "aanval met mes langs boven". Dat is zo overgenomen.
- Afbeeldingen worden rechtstreeks van de Google Site geladen. Download ze best en zet ze naast `index.html` als de site echt online gaat.
