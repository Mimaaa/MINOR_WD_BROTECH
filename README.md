# Browser Technologies

## Opdracht 1.1

De twee dingen die ik heb gekozen zijn:

1. Custom Fonts
2. NO-JS

De websites die ik vaak bezoek/gebruik:

1. Tweakers
2. Moodle
3. MarktetingFacts

### Het experiment op Tweakers

#### Custom Fonts

- Er is geen afwijking of probleem te vinden. Ze hebben in de css een duidelijke fallback aangegeven (systeem fonts)

#### NO-JS

- Er gebeuren geen opvallende dingen. Ik kan de website blijven gebruiken zoals het bedoeld is. Het enige dat niet werkt is dat ik info-banners niet weg kan klikken. Ik kan nog wel blijven reageren op artikelen.

#### Oplossing

Een modal maken op basis van css als fallback

### Het experiment op Moodle

#### Custom Fonts

- Er gebeurt niet zoveel bijzonders.

#### NO-JS

- Er gebeurt niet zoveel bijzonders.
- Het my-profile submenu verdwijnt en de menu-items worden naast de profiel-foto als icoontjes getoond.

#### Oplossing

- Geen oplossing vereist

### Het experiment op MarketingFacts

#### Custom Fonts

- Ze gebruiken font-icons voor de social-media icoontjes en andere menu-items. Na het uitzetten van de custom fonts zijn deze niet meer zichtbaar.

#### NO-JS

- Het hele menu wordt uitgeklapt en dat neemt de hele pagina in beslag.
- Als je een comment wil plaatsen dan zie je gelijk de rode tekst tevoorschijn komen in plaats van dat die naderhand wordt getoond.


#### Oplossing

- SVG’s gebruiken ipv font-icons
- Een css menu ter fallback of een betere indeling van de content
- Gebruik maken van de css/html check

### Overige websites

Omdat de bovenstaande sites niet echt bijzonderheden naar voren brachten heb ik andere sites bekeken:

#### Airbnb

Airbnb werkt gedeeltelijk. Je kan zoeken op steden en het aanbod zien, maar je kan de kamer niet boeken, maar je kan dan weer niet de taal en valuta wijzigen.

#### Booking

Booking website blijft wel goed werken wanneer JS is uitgeschakeld, maar je kan niet boeken.

#### Virgin America

Virgin America heeft bij de Webby Awards de beste prijs voor UX gekregen, maar als je JS uitschakelt krijg je een witte pagina te zien.

#### The Guardian

The Guardian heeft bij de Webby Awards de beste prijs gekregen voor UX en wanneer ik JS uitschakel dan blijft de pagina nog redelijk goed werken. Enkele elementen zijn niet meer te zien/gebruiken (ex. weer).

## Opdracht 1.2

### 1. Javascript uitzetten

Ik heb gekeken naar wat er gebeurd als ik Javascript op de www.cmd-amsterdam.nl website uitschakel en er gebeuren teveel slechte dingen.

#### Homepage

Als Javascript aanstaat dan zie je dat er een mooie grote slider aanwezig is waarin een mooie grote foto staat, maar zodra ik Javascript uitzet dan is de hele slider verdwenen - wat vrij logisch is aangezien de slider op Javascript werkt - maar dat de foto verdwijnt lijkt mij niet zo heel handig, aangezien de foto toch een bepaalde sfeer overbrengt.

Met JS:

![alt text](https://github.com/Mimaaa/MINOR_WD_BROTECH/blob/master/img/hpjs.png "Javascript ingeschakeld")

Zonder JS:

![alt text](https://github.com/Mimaaa/MINOR_WD_BROTECH/blob/master/img/hpnojs.png "Javascript uitgeschakeld")

Oplossing:

Ter fallback zou het kunnen helpen om een fallback te maken waarin je zegt: als de slider niet wordt ingeladen laat dan een normale foto zien.

Bij het inladen van de slider.js worden ook twee buttons ingeladen die belangrijk voor de interactie kunnen zijn. Deze kunnen natuurlijk ook met html/css getoond worden.

#### Studentenwerk pagina

De homepage is dus al niet bestand tegen wanneer JS het begeeft, maar ik was toch benieuwd wat er zou gebeuren als ik een andere pagina zou bezoeken. Dat verliep ook niet zo lekker. Toen ik de studenwerk pagina bezocht kreeg ik alleen onderstaande te zien in plaats van een mooie interactieve pagina zoals die wordt getoond wanneer JS aanstaat.

![alt text](https://github.com/Mimaaa/MINOR_WD_BROTECH/blob/master/img/studentenwerk-nojs.png "Studentenwerk-pagina zonder JS")

#### Overige

Nog wat andere dingen die mij opvielen zijn dat je ook niet kan zoeken op de website wanneer JS het niet meer doet.

### 2. Custom Fonts

Het enige wat er gebeurt is dat de custom icon fonts niet meer werken. In dit geval het zoek-icoon - dat vrij belangrijk is, maar eveneens de social media iconen. 

Op de studentenwerk pagina doen de hartjes het ook niet meer. 

Oplossing:

De oplossing is natuurlijk het gebruik maken van SVG's in plaats van custom fonts.

### 3. Kleur

Ik heb de tool Sim Daltonism gebruikt om te kijken wat er gebeurd als mensen met kleurenblindheid de website bezoeken en of bijvoorbeeld bepaalde knoppen nog goed te gebruiken/zien zijn, maar ook om te zien wat er met de contrasten gebeurd.

Geen bijzonderheden dus.

### 4.  










