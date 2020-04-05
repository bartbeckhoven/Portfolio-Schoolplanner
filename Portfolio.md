# Portfolio Schoolplanner
## Reflectie week 2  
Het plan van aanpak stond voor deze week op de planning om af te maken zodat we konden beginnen met het ontwikkelen van de applicatie. Samen met Jan-Kees heb ik het plan van aanpak  afgemaakt. Deze samenwerking verliep erg goed, we hebben samen alles doorgekeken of er nog dingen misten en dit vervolgens aangevuld. Later bleek er een probleem te zijn met onze github. Een bestand bleef continu veranderen en dit zorgde voor problemen. Jan-Kees en ik hebben met Joep een afspraak gemaakt om dit probleem samen met hem op te lossen.  

**Klassendiagram**  
Na het seniorgesprek met Joep bleek dat er in het klassendiagram een aantal gebreken waren. Ten opzichte van week 1 is er gekeken naar het klassendiagram wat we al hadden opgesteld. We kwamen voor een aantal keuzes staan. In welke klassen gaan we data opslaan en met welke klassen kan een klasse communiceren. Er is uiteindelijk gekozen om een centrale klasse "Lesson" te maken die in zijn attributen de bepaalde groep, vak, leraar en tijd bijhoudt. Deze keuze hebben we gemaakt met het idee dat de roostermodule uit een object alle informatie kan halen voor het tekenen van het rooster en later de simulatiemodule zo ook de NPC's naar de lokalen kan laten bewegen.

**!!!!!!!KLASSENDIAGRAM AFBEELDING**  

## Reflectie Week 3: Foutmeldingen
In de roostermodule kunnen lessen worden aangemaakt, er moeten nu alleen nog foutmeldingen worden gegeven als je een les wil toevoegen waarvan: klas, leraar of lokaal op dezelfde tijd al een les hebben, en als de begintijd van de les voor de eindtijd ligt.  
Op maandag is er normaal altijd een projectdag, alleen kon ik er helaas niet bijzijn wegens ziekte. Samen met Redouan heb ik op donderdag naar deze foutmeldingen gekeken en opgelost. Toen we vrijdag alles samen gingen voegen, bleek na een aantal tests dat de foutmeldingen toch niet goed geimplementeerd waren. Vrijdag heb ik toen samen met Jan-Kees nog eens goed gekeken naar een passende oplossing voor de foutmeldingen.  

Om de foutmeldingen te realiseren zijn we eerst gaan kijken naar welke waarde er gecheckt moesten worden. Er moest vooral telkens naar de lestijden gekeken worden en vervolgens of de klas, leraar of lokaal niet op die tijd al bezet waren. We hebben er uiteindelijk voor gekozen om dit via een heleboel if statements te gaan doen. Dit stuk code was echter niet erg netjes. In totaal hadden we 18 if statements onder elkaar die elk iets anders controleerde. Na wat testen dachten we dat alles naar behoren werkten maar na samenvoegen moesten we vrijdag opnieuw gaan zitten. We wisten dat de code een stuk robuuster en slimmer moest. Jan-Kees en ik hebben daarom gekozen voor een klein aantal if statements met een switch-case voor die de juiste foutmelding return geeft. Na het uitwerken is de code teruggedrongen tot een aantal van 3 if statements die communiceren met een switch case voor de juiste foutmeldingen.  

**!!!!! Afbeelding Code switch case!!!!!**

