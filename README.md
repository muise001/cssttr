# Marijn's Website (week 1 en 2)

Voor deze opdracht van CSSTTR moeten wij een website maken die te gebruiken is door iemand met spasme. Aangezien deze persoon liever geen muis gebruikt, moet hij door de website heen kunnen '**Tab**ben'. Ook moeten wij gebruik maken van CSS Grids en mogen wij geen JavaScript gebruiken.

![Eerste Design](design.jpeg "Eerste Design")

# Stijl
### Blokken
Ik heb een blokken-design gemaakt. Hier heb ik voor gekozen omdat alles dan in een oogopslag te zien is waar het staat. En er een logisch tab-pad inkomt. 

### Research
Om CSS Grids beter te leren begrijpen heb ik [deze video](https://www.youtube.com/watch?v=HgwCeNVPlo0) gekeken en aantekeningen gemaakt. Ook heb ik [CSS Grid Garden](http://cssgridgarden.com/#nl) gespeeld tot level 27. Verder heb ik gebruik gemaakt van de pseudo-class ":target". Deze had ik nooit eerder gebruikt.

# Progressie
### Wat gaat goed?
Werken met CSS vind ik moeilijk. Ik ken gelukkig de nodige trucjes om alles te centreren. Met grids werken gaan na de research die ik ernaar gedaan heb vrij goed. Ik heb zelfs een grid in een grid.... Grid-ception?
Ook ben ik blij dat ik gestopt ben met "clueless programmeren". In het begin ging ik namelijk alles tegelijkertijd stijlen, waardoor uiteindelijk niets goed uitzag. Nu heb ik een design waar ik wel blij mee ben en hopelijk mooie animaties en paden voor kan maken.

### Wat kan beter?
**In de klas**

Ik merk dat ik soms moeite heb om me te concentreren. Dat komt omdat ik nog niet helemaal thuis ben in CSS, dus er ook minder zin in heb. Gelukkig gaat dit sinds m'n nieuwe design beter, aangezien ik nu weet wat ik ga maken. Ook ben ik veel tijd kwijtgeraakt om uit te vogelen wat de logica en de verhouding was tussen de content. 

**In CSS**

  * Van animaties heb ik weinig kennis, dus kost het veel tijd. Gelukkig weet ik precies hoe ik wat wil animeren.
  * Ik vind het moeilijk om goede kleuren te vinden om in m'n design te zetten
  * Sinds het skelet van het design staat weet ik niet zeker of ik dit design nog wil.
  
# Eindproduct
  De website werkt. Je kan er goed doorheen met tab en sommige elementen worden groter als je erin Tabt. De vormgeving is helaas niet zo geworden als ik hoopte. Daarom heb ik eind week 2 een redesign gemaakt, maar ik had te weinig tijd om dit werkend te maken. Daarom ben ik verder gaan bouwen aan een "Slecht" design.
  
 **Proces** 
 In de laatste weken ging het werken goed. Helaas was ik dinsdag afwezig wegens ziekte. Ik ben begonnen met een design. Dit leek op papier een mooi design. Toen ik hem af had, was ik niet tevreden, dus heb ik een nieuwe tekening gemaakt op het zelfde design met meer detail. Dit heb ik toegepast. Toen alles af was, ben ik gaan kijken naar de kleuren die ik wilde gebruiken. Ik heb zeker 8 verschillende kleurenpaletten gemaakt en toegepast, maar er was er niet een die "goed uit de verf" kwam. Uiteindelijk heb ik voor de minst lelijke gekozen.
 
 **Tijdindeling**
 De meeste tijd ben ik kwijt geraakt aan het piekeren over waarom die onlogische elementen in de site moesten en tekenen. Ik was vaak aan het her-designen. Dit heeft veel tijd gekost
 
 **Eindresultaat**
 Ik ben al met al niet tevreden met het eindresultaat, omdat de vormgeving niet mooi is. Waar ik wel blij mee ben, is dat ik veel heb geleerd over css selectoren en animatie. De tabroute werkt goed. Zelf vind ik het ondanks dat een onvoldoende.
 
# Herkansing
Nadat ik CSSTTR niet had gehaald, bestloot ik om mijn website voor "web design" te recycelen. Dat was lastig aangezien er in deze website heel veel classes waren gebruikt. Des al niet te min is het me gelukt om het grootste deel om te schrijven naar "normale" (eigenlijk "abnormale") CSS selectoren. Wederom is de website volledig geoptimaliseerd voor Marijn. Dit houdt in dat je overal met de tab-toets doorheen kan. 

**Eissen**
- [ ] **Geen classes of id's**
  * Ik heb uiteindelijk wegens tijdsnood niet alle classes eruit kunnen halen, maar meer dan de helft van m'n css is omgescrhreven. Ik heb gebruik gemaakt van veel verschillende type selectors en had soms Css die er zo : ```nav input[type="checkbox"]:checked + label[for="checkuboxu"]:before``` uitzag.
- [x] **Pseudo Random**
  * Er moest ook iets in dat Pseudo-random was. Dit zou een animatie kunnen zijn of de verloop van een "random background". De random background was het meest voor de hand liggende en het makkelijkst te maken. Ondanks ik tegen het concept "random background" ben, ben ik tevreden met het eindresultaat... Het was uiteindelijk niet zo lelijk als ik dacht.
- [x] **Custom Checkbox**
  * Ook heb ik een custom checkbox gemaakt. Hier was ik relatief lang mee bezig. Uiteindelijk was het echter vrij makkelijk... maar dat is met alles zo, als je iets voor het eerst doet. Ik heb een `<input type="checkbox>` een `opacity : 0` gegeven en heb een label gestyled, zodat deze werkt en eruitziet als checkbox. Ik ben blij met het resultaat.
- [x] **Blur**
  * Blur was een hele korte en makkelijke oefening. Ook deze heb ik toegevoegd
- [x] **Custom Cursor**
  * In Illustrator heb ik een custom cursor gemaakt die volledig in de stijl is van de website. Nadat het me eindelijk gelukt is om mijn .png om te zetten naar een .ico en hem daarna 4x in size te verkleinen, was hij eindelijk zichtbaar op de pagina. Hoe leuk je een cursor ook maakt... ik raad niemand aan om een eigen cursor te maken, maar het was wel een goede oefening
- [x] **Grid**  
  * Ook moest er in de site een CSS-grid zitten. Aangezien mijn website al aardig werkte met flex-box, had ik geen idee waar ik mijn grid op toe moest voegen. Toen dacht ik aan de eerste les waarbij Vasillis vertelde dat ze vroeger alles stylden met tabellen. Ik had een reusachtig tabel. Toen heb ik die omgeschreven naar Grid... Je moet toch een beetje met je tijd meegaan
- [x] **Bigger Hitradius on small button**
  * Kleine knoppen zijn soms lastig te raken. Maar dat is makkelijk op te lossen... Dacht ik. Na het doen van research over hoe je het beste een hitbox kon vergroten, zeiden de meeste mensen dat je "gewoon" de padding van je knop moest vergroten. Maar dat ziet er natuurlijk niet uit. Anderen zeiden weer dat je het makkelijk met background-clip kon doen, maar ook dat bleek niet waar. Uiteindelijk dacht ik aan de custom checkbox, waarbij ik met gebruik van een label een andere checkbox heb kunnen maken. Uiteindelijk heb ik een grote label om een knop heen gedaan en dit werkt voortreffelijk!
- [x] **Custom Hovers en Focus**
  * Om zoveelmogelijk samenhang tussen de website en de interactie te creeren heb ik de "default focus-state" weggegooit. Ik ben gaan klooien met animaties, transforms en transitions om focus-states te maken die er niet alleen beter uitzien bij het design, maar ook goed werken en duidelijk zijn.
- [x] **Form Validation** 
  * Als je wilt laten zien dat iemand een formulier goed invult, dan is het handig om form-validation toe te passen. Dit heb ik gedaan. Ik heb zelfs een super mooie animatie toegevoegd, maar helaas door de "default input styling" van Chrome is deze niet te zien. Maar ik heb hem wel... of niet... of wel... Helaas zal je dat nooit weten. De uiteindelijke zichtbare form-validation maakt de borders van de input-velden groen of rood. Ook kan je het formulier niet eerder submitten, dan dat alle inputs ingevuld zijn.
- [x] **Ampersand** 
  * Altijd al een gaaf "&"-teken in je website willen hebben? Nee? Ik ook niet. Maar hij zit er wel in, en ben achteraf toch wel overdonderd door de charme van dat ding.

Naast dit bovenstaande lijstje zijn er nog zo'n honderd bijzondere dingen aan mijn website. [Neem zelf maar even een kijkje](https://www.google.nl/)





 
  
 > Emiel Muis
