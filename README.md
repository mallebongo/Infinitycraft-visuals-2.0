# TODO

## Visuals
### Combinatie data visualiseren
Hierin kan je dan zien hoe combinaties tot stand komen
Interactief zodat je kan zien hoe dingen makkelijk kunnen worden gemaakt

### Gewoon network van data maken
Dit lijkt meer op die twitch grafiek.
Een gewoon network waar we dan ook analyses over kunnen gaan doen
Wat zijn de groepen?
Zijn er bezondere clusters?
Zijn er elementen waar heel veel verschillende combinaties naar toe gaan. (Een soort sink)
Kleurtjes voor groepen

## Data
### Data netjes opslaan
Een ditionairie maken met {elme1,elem2 : uitkomst}
Alle data erin krijgen dus ook als ze dezelfde uitkomst hebben
als data niet kan worden samengevoegd dat er None komt te staan

### Data verkrijgen
#### Sleep systeem
Robuust systeem om elementen te slepen
Goed kunnen zien waar elementen staan
Welke elementen actief zijn
En wat er uit een combinatie komt

#### Welke combinaties gaan we doen?
We kunnen dit op verschillende manieren structureren en misschien is het wel leuk om verschillende dingen te proberen zodat we de grafiek op een andere manier zien groeien?
1. Eerst alles combineren met vuur. Dus vuur-vuur dan vuur-water vuur-aarde vuur-wind. en dan alles wat hieruit komt weer combineren met vuur. En als we dan alle combinaies op die manier hebben gedaan dan gaan we naar water-water water-aarde. En dan vuur-water en water-vuur is hetzelfde dus die eruit halen.
2. Random combinaties proberen maar geen dubbele combinaties
3. Eerst alle hoofd elemenenten proberen en dan elke stap dat we verder komen de volgende weer met alle hoofdelemetenen en dan de kinderen als tweede en zo verder. Dat we alle combinaties vanuit het midden doen.
4. Alle eigen combinaties proberen. Dus water-water en vuur-vuur en dan wat daaruit komt weer met zichzelf.
5. Een random kant op genereren elke keer als je weer wat nieuws hebt weer met alle oude dingen combineren om zo ver mogelijk van de start te komen.
