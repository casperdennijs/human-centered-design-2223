# Digitale kledingkast

![digitale kledingkast](https://github.com/casperdennijs/human-centered-design-2223/assets/56598338/9fbe93ed-6bd3-43e5-9ea2-131220cd7305)

## Onderzoeksvraag

**Passende kleding uitzoeken**

Je representatief kunnen kleding in verschillende omstandigheden is voor iedereen belangrijk, ook voor Petra. Wat is casual, zakelijk, feestelijk of geschikt voor een begrafenis? Petra heeft een kast vol kleren die ze graag op het juiste moment wil kunnen gebruiken. Hoe vind je de juiste kleurencombinaties als je het niet kunt zien? Ontwerp een systeem dat de ordening van de kast voor Petra inzichtelijk maakt op kleur en stijl.

## Probleemdefinitie

Petra vind het belangrijk wat zij voor kleding draagt en hoe ze zich vertoond tegenover andere mensen. Doordat ze blind is kan ze zelf niet zien hoe iets haar staat en wat een goede combinatie kan zijn. Hiervoor heeft ze dan iemand ervoor nodig, maar wil ze graag het heft zelf in handen hebben. Voor de opdracht is het dan ook de bedoeling om haar kledingkast te digitaliseren, zodat ze zelf makkelijk en overzictelijk kan horen wat ze allemaal in bezit heeft en keuzes eruit te kunnen maken.

## Oplossing

Ik heb een mobiele applicatie gemaakt waarbij ze makkelijk informatie over haar kleding kan ophalen. Petra is ondanks ze blind is heel goed met haar mobiel gebruiken en daar heb ik op ingespeeld. Met een simpele layout probeer ik haar binnen enkele handelingen de informatie te krijgen die ze wilt. Ze kan per categorie horen welke kledingstukken ze heeft die vervolgens door haar screenreader wordt voorgelezen. Ik heb alle kledingstukken zo geplaatst dat het lijkt op je apps in je homescreen. Aangezien deze layout al vrij bekend is zal dit hopelijk helpen sneller op gemak te voelen met het gebruik.

## Link prototype
https://casperdennijs.github.io/human-centered-design-2223/

----

# Documentatie van de Design Principles, User Needs, Testen en Testresultaten.

## Test #1

**Vooraf:**

Voorafgaand op de eerste test zijn we geintroduceerd met dit vak en de opdracht. Hier kregen we de basis informatie over de personen en zijn we ingedeeld in groepen. Ik kwam in groepje Petra terecht. Na de opdracht te hebben gekregen en de situatie van Petra te hebben geleerd werd het tijd om een eerste prototype te bedenken. Ik had hier nogal moeite mee om ik totaal geen idee had wie Petra verder is en wat haar behoeftes zijn. Uiteindelijk heb ik een hele simpele prototype gemaakt waarbij in HTML op volgorde kleding in een lijstje stond, deze zijn geordend op de aanname dat ze haar kledingkast zelf in een vaste order bij houd.

**Gedurende:**

Tijdens de test werden we officieel geintroduceerd met Petra zelf. Het groepje had een aantal vragen voorbereid om te voorkomen dat deze dubbel gesteld zouden worden. Hierin werd al vrij snel duidelijk dat mijn prototype geen nut gaat hebben. Ze heeft namelijk geen vaste ordening van het opbergen van haar kleding in haar kledingkast en daar was mijn prototype volledig op gebaseerd als aanname. Verder wou ze wel graag haar kledingkast digitaal hebben en kunnen matchen met wat ze heeft en daar feedback op krijgen. Ze wilt zelfstandiger kunnen zijn in het kiezen van kleren, maar moet wanneer nodig het wel makkelijk en snel met andere kunnen delen.

**Achteraf:**

Na de test heb ik besloten om mijn eerste prototype volledig te gaan schrappen en te gaan focussen op navigatie en layout. Gedurende test ging Petra namelijk met haar mobiel te werk en kwam naar voren dat ze ondanks ze blind is wel heel goed gebruik ervan te kunnen maken en daar wil op in gaan spelen. Ik ben begonnen met een overzicht van kleding met navigatie naar verschillende categorieen. Wanneer je op een kledingstuk klikt begint de screenreader voor te lezen wat de kledingstuk inhoud, zoals kleur, stijl en wat het is.

## User Needs

- Kleur en stijl vind ze het aller belangrijkste, de rest kan ze zelf vaak onderscheiden
- Ze wil graag haar kledingkast gedigitaliseerd hebben
- Snel en makkelijk te moeten gebruiken en goed werkende in combinatie met screenreader
- Moet kleding combinaties kunnen delen met andere voor feedback
- Basis feedback kunnen krijgen van de applicatie zelf

## Design Principles

**1. Study situation**

Petra is vanaf haar geboorte blind en kan dus helemaal niks zien, hierdoor kan zij dus geen schermen gebruiken die anders wel altijd gebruikt worden. Gedurende de eerste test kwam heel sterk naar voren welke apparaten ze gebruikt en hoe ze deze gebruikt. Hierbij zou je wellicht denken dat een smartphone lastig zou kunnen zijn, maar Petra liet het tegendeel zien, ondanks dat ze blind kan ze heel goed en snel overweg met haar mobiel met ondersteuning van een screenreader. Ze weet snel haar doel te bereiken en was dan ook niet beperkt in het feit dat ze niets kan zien. In mijn prototype wil ik rekening houden met haar expertise in het gebruik van haar mobiel en wil ik daar op inspelen.

**2. Prioritise identity**

Ik ga de applicatie voor mobiel maken, omdat Petra hier snel en handig in kan werken. Ik ga me hierbij focussen op de layout en navigatie, aangezien ze zelf al snel is wil ik het gebruik ook vlot laten verlopen zodat ze niet hoeft te wachten. Hierdoor heeft ze ook snel haar informatie en kan ze snel door naar de volgende stap.

**3. Ignore conventions**

Standaard design patronen bij het maken van een applicatie kan ik nu helemaal negeren. Veel punten waar je visueel bij moet denken zijn namelijk helemaal niet van toepassing omdat Petra niet kan zien. Ik kan me dus volledig gaan focussen op accessibility en daar meer over leren. De werking van een screenreader, wat er voor gelezen wordt en hoe je in code kan zorgen dat er niet onnodige spullen opgenoemd worden. Ook hoe je bijvoorbeeld op laptop kan tabben door elementen die dit normaal niet kunnen door tabindex toe te passen en dan met aria-labels ze volgens hardop voor te lezen.

**4. Add nonsense**

Ik heb niet echt "nonsense" hoeven toe te passen. Ik heb mijn prototype zo straight to the point gemaakt en tijdens de test kwam naar voren dat de navigatie duidelijk was, maar kleding omschrijvingen nog uitgebreider konden.

## Test #2

**Vooraf:**

Op basis van de eerste test heb ik een prototype gemaakt van de digitale kledingkast, hierin kan je door verschillende basis categorieen heen navigeren om kleding te vinden. Hiervoor heb ik alleen HTML en CSS gebruikt en heb ik me verdiept in hoe screenreaders werken op het web. Nou klein beetje zoeken kwam ik erachter dat je met aria-labels vrij snel al een gewenst resultaat kan bieden.

**Gedurende:**

Tijdens de tweede test heeft iedereen zijn prototype laten zien en getest en heb ik veel verschillende dingen gezien. Mijn prototype was vrij simpel dus had een korte test voorbereid, ik wou namelijk graag weten hoe ze de navigatie ervaarde en hoe ze de informatie vond over de kledingstukken en of dit fijn te gebruiken is. Na de test was ze vrij tevreden met hoe het gebruikt kan worden en had ze als voornaamste feedback dat de informatie die voorgelezen werd nog te weinig was.

**Achteraf:**

Na afloop van de test ben ik doorgegaan met de prototype en heb ik kleine aanpassingen toegepast en verbeteringen gemaakt aan de informatie die opgelezen werden.

## User Scenario

**Who is the user I’m designing for?**

De product die ik ga maken is ontworpen voor Petra Huidink-de Jong. Petra is een persoon die blind is geboren en dus helemaal niks kan zien. Ook Petra heeft net zoals iedereen gewoon een dagelijks leven waarbij ze onderandere bezig is als beleidsmedewerker Toegankelijkheid en Mobiliteit bij Cliëntenbelang Amsterdam en ze haar eigen vertaalbureau heeft.

Petra vind het belangrijk wat zij voor kleding draagt en hoe ze zich vertoond tegenover andere mensen. Doordat ze blind is kan ze zelf niet zien hoe iets haar staat en wat een goede combinatie kan zijn. Hiervoor heeft ze dan iemand ervoor nodig, maar wil ze graag het heft zelf in handen hebben. Voor de opdracht is het dan ook de bedoeling om haar kledingkast te digitaliseren, zodat ze zelf makkelijk en overzictelijk kan horen wat ze allemaal in bezit heeft en keuzes eruit te kunnen maken.

**What does this user want on my site?**

<details>
<summary>Passende kleding uitzoeken</summary>
<p>Je representatief kunnen kleding in verschillende omstandigheden is voor iedereen belangrijk, ook voor Petra. Wat is casual, zakelijk, feestelijk of geschikt voor een begrafenis? Petra heeft een kast vol kleren die ze graag op het juiste moment wil kunnen gebruiken. Hoe vind je de juiste kleurencombinaties als je het niet kunt zien? Ontwerp een systeem dat de ordening van de kast voor Petra inzichtelijk maakt op kleur en stijl.</p>
</details>

Petra wil graag een systeem waarin ze haar eigen kleding in kan terug vinden. Ze kan momenteel doormiddel van voelen wel herkennen welk kledingstuk wat is, maar hierbij is kleur en stijl dan nog een redelijk groot vraagstuk. Door het digitaliseren kan het in het systeem al haar kleding bijgehouden worden en worden deze vervolgens hardop voorgelezen. Hierdoor krijg Petra alle benodigde informatie over dat bepaalde kledingstuk en waar het in het kledingkast bevind zodat ze de goede pakt.

**How is this user going to achieve her goals?**

Petra weet ondanks ze blind is heel goed haar mobiele telefoon te gebruiken. Daar wil ik op inspelen en de applicatie op dat apparaat te maken. Verder wil ik het zo simpel mogelijk houden en met zo min mogelijke gedoe erbij. Als layout heb ik het dan ook geprobeerd om apps na te bootsen zoals je op de homepagina van je mobiel zou hebben. Wanneer je dan over een plaatje heen gaat noemt het alle belangrijke kledingstuk op die ze wilt weten. Met de informatie die ze vervolgens vergaard kan ze bepalen of ze dit wil dragen of toch voor een ander kledingstuk goed. Of kan dan alsnog nog iemand anders ter advies vragen.

**Why does this user come to my site?**

Petra wilt op een snelle en makkelijke manier graag weten welke kleding ze heeft en hoe deze eruit zien. Ik hoop met deze applicatie die zo makkelijk mogelijk te maken door in te spelen op het feit dat goed weet hoe ze haar mobiel weet te gebruiken. Door simpele en duidelijk navigatie toe te passen wil ik ook zorgen dat ze zo min mogelijk tijd hoeft in te leveren om tot haar antwoord te komen.

## Conclusie