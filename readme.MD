# oe-oebjecten-contact-card-start

## Opgave
Maak een lijst van contact-kaartjes.
Lees de gegevens uit `data.js` uit en maak kaartjes voor alle contactpersonen die erin zitten.
Je maakt per contactpersoon in `data.js` een kaartje met zijn contactgevens en geeft deze weer. Bekijk `index.html` om te zien wat de structuur van het kaartje is.

## Uitbreiding
**Dit is een belangrijke uitbreidingsopdracht richting het examen!**

Wanneer er op een kaartje geklikt wordt, dan lees toon je de gegevens van de aangeklikte contactpersoon in een `alert()`;
Ga als volgt te werkt:
* Elke contactpersoon heeft een uniek `id`
* Koppel het `id` van de contactpersoon aan het `id`-attribuut van het kaartje z'n avatar
* Wanneer er op een avatar geklikt wordt, dan check je het `id` van de avatar om vervolgens met de `find()`-methode te weten te komen welke contactpersoon aangeklikt werd. Je toont vervolgens zo de naam van de aangetikte persoon in de `alert()`;