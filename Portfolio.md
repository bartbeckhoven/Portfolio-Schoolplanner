# Portfolio Schoolplanner
## Reflectie week 2  
Het plan van aanpak stond voor deze week op de planning om af te maken zodat we konden beginnen met het ontwikkelen van de applicatie. Samen met Jan-Kees heb ik het plan van aanpak  afgemaakt. Deze samenwerking verliep erg goed, we hebben samen alles doorgekeken of er nog dingen misten en dit vervolgens aangevuld. Later bleek er een probleem te zijn met onze github. Een bestand bleef continu veranderen en dit zorgde voor problemen. Jan-Kees en ik hebben met Joep een afspraak gemaakt om dit probleem samen met hem op te lossen.  

**Klassendiagram**  
Na het seniorgesprek met Joep bleek dat er in het klassendiagram een aantal gebreken waren. Ten opzichte van week 1 is er gekeken naar het klassendiagram wat we al hadden opgesteld. We kwamen voor een aantal keuzes staan. In welke klassen gaan we data opslaan en met welke klassen kan een klasse communiceren. Er is uiteindelijk gekozen om een centrale klasse "Lesson" te maken die in zijn attributen de bepaalde groep, vak, leraar en tijd bijhoudt. Deze keuze hebben we gemaakt met het idee dat de roostermodule uit een object alle informatie kan halen voor het tekenen van het rooster en later de simulatiemodule zo ook de NPC's naar de lokalen kan laten bewegen.

![Klassendiagram](https://github.com/bartbeckhoven/Portfolio-Schoolplanner/tree/master/Images/Schoolplanner.jpg)

## Reflectie Week 3: Foutmeldingen
In de roostermodule kunnen lessen worden aangemaakt, er moeten nu alleen nog foutmeldingen worden gegeven als je een les wil toevoegen waarvan: klas, leraar of lokaal op dezelfde tijd al een les hebben, en als de begintijd van de les voor de eindtijd ligt.  
Op maandag is er normaal altijd een projectdag, alleen kon ik er helaas niet bijzijn wegens ziekte. Samen met Redouan heb ik op donderdag naar deze foutmeldingen gekeken en opgelost. Toen we vrijdag alles samen gingen voegen, bleek na een aantal tests dat de foutmeldingen toch niet goed geimplementeerd waren. Vrijdag heb ik toen samen met Jan-Kees nog eens goed gekeken naar een passende oplossing voor de foutmeldingen.  

Om de foutmeldingen te realiseren zijn we eerst gaan kijken naar welke waarde er gecheckt moesten worden. Er moest vooral telkens naar de lestijden gekeken worden en vervolgens of de klas, leraar of lokaal niet op die tijd al bezet waren. We hebben er uiteindelijk voor gekozen om dit via een heleboel if statements te gaan doen. Dit stuk code was echter niet erg netjes. In totaal hadden we 18 if statements onder elkaar die elk iets anders controleerde. Na wat testen dachten we dat alles naar behoren werkten maar na samenvoegen moesten we vrijdag opnieuw gaan zitten. We wisten dat de code een stuk robuuster en slimmer moest. Jan-Kees en ik hebben daarom gekozen voor een klein aantal if statements met een switch-case voor die de juiste foutmelding return geeft. Na het uitwerken is de code teruggedrongen tot een aantal van 3 if statements die communiceren met een switch case voor de juiste foutmeldingen. Om het aantal if statements in te korten hebben we een extra 3 methodes toegevoegd die de check voor klas, leraar en lokaal doet.  

![Check](https://github.com/bartbeckhoven/Portfolio-Schoolplanner/tree/master/Images/check.jpg)  
![If-statements](https://github.com/bartbeckhoven/Portfolio-Schoolplanner/tree/master/Images/if.jpg)   
![Switch Case errormessage](https://github.com/bartbeckhoven/Portfolio-Schoolplanner/tree/master/Images/error.jpg)  

## Reflectie Week 4: Tiled Map  
Deze week moet de tiled map gemaakt worden. Hiervoor moet in een applicatie genaamd tiled een map worden gemaakt vanuit een tileset. Het zoeken van deze tileset heeft het meeste tijd in beslag genomen aangezien het lastig was een gratis set te vinden die alle attributen had die wij nodig hadden voor onze schoolmap. Uiteindelijk hebben we gekozen voor een oude pokémon tileset omdat deze set alles had wat we nodig hadden. Na het vinden van de tileset moesten er een aantal keuzes gemaakt worden: Hoeveel lokalen hebben we nodig, hoe breed worden de gangen, waar en hoeveel toiletten en hoe groot bijvoorbeeld de aula moet worden.  
Omdat we in de simulatie later geen opstoppingen willen hebben is er gekozen voor wat bredere gangpaden en kleinere NPC's later. Omdat we een aantal leerlingen van 100 hebben zijn we voor een lokaal aantal van 8 gekozen. Hierdoor is er genoeg plek voor elke leerling om te zitten, en een plek voor de leraar.  

## Reflectie Week 5  
De definitieve versie van het plan van aanpak moet worden ingeleverd en op het moment missen er nog een aantal dingen. Samen met Jan-Kees hebben we ons gericht op het compleet maken van het plan van aanpak. We zijn begonnen met een work breakdown structure want die moest nog gemaakt worden. In dit stadium van het project is het niet echt veel keuzes maken, en zeker niet in het plan van aanpak, dit moet namelijk aan een aantal critera voldoen. Na deze week is het plan van aanpak af en hebben we dit compleet ingeleverd.

## Reflectie Week 8  
Wegens het coronavirus kunnen we niet samenkomen en moet alles via teams gedaan worden. Dit was even wennen en heeft zeker een grote impact op de snelheid van werken. Alles wat nog moeten worden gedaan gebeurd in dezelfde klassen en methode waardoor we met 3 man tegelijk naar een scherm moeten kijken om te werken. Hierdoor is de productiviteit erg laag en duren de projectdagen lang. We hebben deze week de koppeling van de roostermodule naar de simulatiemodude zo goed als afgekregen. We moeten nu nog maar een paar dingen afmaken voor de deadline. Dit zijn wat kleine dingen die in een middag kunnen worden gedaan.

## Reflectie Week 9
Deze week staat in het teken van de puntjes op de i zetten zodat alles gereed is voor inlevering. Ik moet het klassendiagram up to date maken met de huidige code, en dit in het technisch document zetten. Om de huidige code om te zetten naar UML kan in visual paradigm erg makkelijk geconverteerd worden. Ook wil ik deze week evalueren over hoe het project voor mij persoonklijk is verlopen, zodat ik volgende periode een aantal dingen kan verbeteren aan mijn werkhouding.

![Switch Case errormessage](https://github.com/bartbeckhoven/Portfolio-Schoolplanner/tree/master/Images/error.jpg)  


