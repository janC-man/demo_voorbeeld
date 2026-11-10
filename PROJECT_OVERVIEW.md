# Ligger in beeld

## Doel
Een interactieve rekentool die tijdens de les zichtbaar maakt hoe belastingen een ligger beïnvloeden.

## Doelgroep
In de eerste versie gebruikt de leerkracht de app om voorbeelden aan leerlingen te tonen. Later kunnen leerlingen de app zelf gebruiken voor oefeningen en om hun antwoorden te controleren.

## Eerste versie
- De lengte van een ligger instellen, met een scharnier links en roloplegging rechts.
- Een overkraging links, rechts of aan beide kanten instellen.
- Met schuifbalken één schuine puntlast en één lijnlast instellen. De puntlast heeft een grootte, richting en aangrijppunt. De lijnlast heeft een grootte, beginpunt en eindpunt.
- De normaalkracht-, dwarskracht-, moment- en doorbuigingslijn tonen en meteen aanpassen wanneer de instellingen veranderen.
- HEA 100 als standaardprofiel gebruiken, met de ligger gebogen om de sterke as (`I = 349,2 cm⁴`) en staal als materiaal (`E = 210 GPa`).

## Nog niet
- Leerlingoefeningen, antwoorden controleren en voortgang bijhouden.
- Meerdere puntlasten of lijnlasten tegelijk.

## Platform
Een website die in de browser werkt, zodat de leerkracht ze eenvoudig tijdens de les kan openen en later met leerlingen kan delen.

## Frameworks en bouwstenen
React met Vite voor het interactieve scherm en de schuifbalken. De app rekent in de browser en heeft geen server nodig.

## Opslag
Er worden geen instellingen of andere gegevens bewaard. De waarden gelden alleen zolang de pagina open is.

## Vormgeving
Gebruikt het design system in `design-system/`, met een duidelijke weergave van de ligger en de kracht- en vervormingsdiagrammen.

## Eisen
- De lengte, afstanden en F- en q-belastingen kunnen met schuifbalken gewijzigd worden.
- De app toont de normaal-, dwarskracht- en momentlijn en de doorbuigingslijn.

## Publicatie
De website komt op GitHub Pages. Elke merge naar `main` publiceert de site automatisch via een workflow.
