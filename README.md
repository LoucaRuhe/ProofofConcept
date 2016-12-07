# ProofofConcept
Louca Ruhe - Technische uitdaging

Mijn uitdaging tijdens het vak maken zal zijn om mijn ideeën op een technische wijze uit te werken. Ik deed dit voorheen met invision zoals vele anderen ook doen. Mij lijkt het super tof om ook echt de interactie op een betere manier uit te kunnen werken. Dit hoop ik onder de knie te hebben zodat ik het ook kan gebruiken volgend jaar en in het vervolg na mijn studie. 


# Inleiding, wat wil je weten?

Tijdens het vak ontwerpen zijn wij aan de slag gegaan met key scenario's. Dit heeft er voor gezorgd dat ik een key scenario heb kunnen kiezen die ik daarmee ook technisch wil gaan uitwerken. Ik wil daarmee het volgende te weten komen:

Bestaat er iets zoals een voorgestelde oefeningen lijst bij het AMC? Hoe krijg ik dit technisch werkend?

Het idee hierbij is dat je naast de oefeningen zelf toevoegen ook oefening suggesties krijgt. Het eerste wat ik wil uitzoeken is of er een standaard lijst met oefeningen is voor bepaalde scenario's bij OCD. Zodra ik dit weet wil ik bekijken hoe ik dit technisch kan toevoegen. Als laatste wil ik het technisch ook daadwerlijk uit gaan proberen. 

# Hoe heb ik onderzoek aangepakt + de Resultaten

Ik ben gestart met het mailen naar Pieter om over een aantal vragen duidelijkheid te krijgen. De vragen waren als volgt:

1. Klopt het dat je OCD kunt onderverdelen in diverse OCD categorieën? En zo ja, welke categorieën?
2. Is er een lijst met voorgestelde oefeningen die gebaseerd zijn op klachten?
3. Is het mogelijk om een lijst te maken met voorgestelde oefeningen?

Op mijn vragen heb ik diezelfde dag nog antwoord gekregen. Zie hier de antwoorden van Pieter:

1. 1)Controledwang, 2)Smetvrees, 3)Agressieve seksuele of religieuze obsessies, 4)Magisch denken

2. We hebben geen lijst liggen met voorgestelde oefeningen.

3. we zouden wel wat voorbeelden kunnen maken maar denk dat het wel mooi zou zijn mocht die automatisch kunnen gegenereerd worden uit voorbeelden van anderen.

Met de antwoorden op mijn vragen ben ik gaan brainstormen over mogelijke oplossingen. Ik heb schetsen gemaakt van wat mij logisch lijkt wat er in iedergeval ingevuld moet worden door de gebruiker. Op deze manier kon ik gaan nadenken over de technische werking. 

Na de visuele uitwerking een beetje in mijn hoofd te hebben kwam de technische uitwerking kijken. Hiervoor kwamen een aantal vragen meteen in mij op.

1. Hoe sla ik de oefeningen op?
2. Hoe haal ik deze oefeningen weer terug en weergeef ze bij de suggesties, onderverdeeld bij de categorieen 
3. Na het kiezen van een voorgestelde oefening, hoe zorg ik er dan voor dat hij niet opnieuw in de database terecht komt?

Ook hier heb ik onderzoek naar gedaan op het web en heb rond gevraagd aan mensen die ik ken die hier ervaring in hebben. Uit mijn onderzoek ben ik achter een paar nieuwe dingen gekomen waarmee ik antwoord heb gekregen op mijn vragen. 

1. De oefeningen kunnen het beste worden opgeslagen in een database table.
2. Door de table op te halen kunnen ze weergeven worden op de suggesties pagina. 
3. Om er voor te zorgen dat de oefening niet nog een keer opgeslagen wordt moet je er een unieke ID aan geven. Zo bestaat de ID al in de database en wordt hij niet nog een keer opgeslagen.

Verder heb ik nog gekeken wat ik zelf kan aanleren om het zelf uit te kunnen werken. Waarschijnlijk zal dit PHP en MySQL worden.


# Conclusie

De hoofdvraag wat ik wilde weten was: 

Bestaat er iets zoals een voorgestelde oefeningen lijst bij het AMC? Hoe krijg ik dit technisch werkend?

Het antwoordt op mijn eerste vraag is dat er momenteel nog geen lijst met oefeningen bestaat. Wel is het een idee om de ingevulde oefeningen automatisch op te slaan zodra de gebruiker deze toevoegd. Dit zodat er een lijst ontstaat. 

Daarnaast was de vraag hoe ik dit het beste werkend kreeg. Ik kan het technisch werkend krijgen door er een database achter te gooien en de suggesties hier uit terug pakken. Dit wil ik zelf uit gaan voeren door PHP en MySQL te gaan gebruiken. 

Dit heb ik nog nooit gebruikt, maar ben bereid mij hier in te verdiepen om dit gedeelte technisch uit te kunnen werken. 
