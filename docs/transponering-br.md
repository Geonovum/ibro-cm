# Transponering van IBRO naar de basisregistraties

Deze bijlage beschrijft hoe de elementen uit IBRO corresponderen met elementen uit de basisregistraties BAG en BGT, inclusief het optionele deel, IMGeo [[IMGEO22]]. Het is geen volledige lijst, maar biedt een eerste opsomming van (mogelijke) knelpunten in de transponering. Naar de WOZ is nog niet gekeken.

## Wegen

| BGT/IMGeo    | IBRO/EMSO | Opmerkingen |
| -------- | ------- | ------- |
| Wegdeel  | Wegverbinding en Verharding | In IBRO worden functie en fysiek voorkomen van wegdelen gescheiden in functionele ruimten en verharding. Om vanuit IBRO naar BGT te kunnen leveren moet dit weer samengevoegd worden tot 1 wegdeel. Het attribuut functie dient voor een deel ook vanuit de combinatie van Wegennetwerk en Verharding te worden samengesteld. |
| Calamiteitendoorsteek | *vervalt* | Optionele IMGeo inhoud. |
| Voetpad op trap | *vervalt*, transponering is naar Voetpad | Verplichte BGT inhoud. Het is echter niet  mogelijk om voetpad op trap te onderscheiden in IBRO. |
| Nadere classificaties van Open verharding | Elementenverharding | Nadere classificaties vervallen. Dit is optionele IMGeo inhoud, maar als een gemeente deze plus classificaties nu wel bijhoudt en aan de LV wil leveren is dit problematisch. |
| Nadere classificaties van `Half verhard` | `Halfverharding` | idem |
| `kruinlijn` | vervalt | Verplichte BGT inhoud. Het objecttype heeft 2.5D geometrie. Wellicht is de kruinlijn hieruit af te leiden. | 
| `opTalud` | vervalt | Verplichte BGT inhoud. Het objecttype heeft 2.5D geometrie. Wellicht is hieruit af te leiden dat het wegdeel op een talud ligt? Geldt ook voor Onbegroeid terreindeel, Begroeid terreindeel, Ondersteunend Wegdeel | 
| `geleideconstructie` | `geleideconstructie` | Optionele IMGeo inhoud. Problematisch als een gemeente deze nu aan BGT levert, omdat er in IMGeo ook twee Waterinrichtingselementen zijn, `remmingswerk` en `geleidewerk`, die in IBRO `geleideconstructie` worden. Deze zijn niet meer terug te mappen naar Waterinrichtingselement en Weginrichtingselement.| 

## Spoor

| BGT/IMGeo    | IBRO/EMSO | Opmerkingen |
| -------- | ------- | ------- |
| `sneltram`, `tram` | `lokaal spoor` | sneltram en tram zijn verplichte BGT inhoud. Als een gemeente beide heeft is er extra informatie nodig om lokaal spoor voor BGT levering uit te splitsen naar sneltram en tram.|
| `havenkraan` | *vervalt* | Dit is optionele IMGeo inhoud, maar als een gemeeente deze plus classificatie nu wel bijhoudt en aan de LV levert is dit problematisch.|

## Onbegroeid terrein

| BGT/IMGeo    | IBRO/EMSO | Opmerkingen |
| -------- | ------- | ------- |
| `erf` | onbepaald terrein | geen probleem want de populatie is 1 op 1|
| `strand en strandwal`, `zandverstuiving` | `onbegroeide grond` | Dit is optionele IMGeo inhoud, als een gemeente deze plus classificatie nu wel bijhoudt en aan de LV levert is dit problematisch. Op te lossen door geografische ruimten te gebruiken met classificatie `Strand` of `Zandverstuiving`.|
| `kruinlijn`, `opTalud` | vervalt | zelfde opmerking als bij `Wegdeel` |

## Groen

| BGT/IMGeo    | IBRO/EMSO | Opmerkingen |
| -------- | ------- | ------- |
| `houtwal` | `houtsingel` | Dit zijn twee verschillende dingen. Wel allebei lijnvormige beplanting maar een houtwal staat op een aarden wal en een houtsingel niet. Strikt genomen is dit geen goede transponering, maar een andere is er niet.|
| `open duinvegetatie` en `gesloten duinvegetatie` | gras- en kruidachtigen of struiken of onbegroeide grond | Open en gesloten duinvegetatie worden niet meer onderscheiden in IBRO. Dit is optionele IMGeo inhoud. Als een gemeente deze plus classificatie nu wel bijhoudt en aan de LV levert is dit problematisch.|
| `wijngaarden` en `klein fruit` | fruit- en kweekboom: fruitkwekerij met lage opstand | Wijngaarden en klein fruit zijn niet te onderscheiden in IBRO maar zijn optionele IMGeo inhoud.| 
| Plusclassificaties van `bouwland` | allemaal `akkerland` in IBRO | Optionele IMGeo inhoud|
| `bosplantsoen` | `bos` | Optionele IMGeo inhoud. Als een gemeente zowel Bos als Bosplantsoen heeft dan zou het lastig zijn om die weer bij BGT levering op te splitsen.  |
| `planten`, `struikrozen`, `heesters` en `bodembedekkers` | `struiken` | Optionele IMGeo inhoud. Als Rotterdam deze nu levert aan de BGT en wil blijven leveren is dit problematisch, want in IBRO kun je ze niet onderscheiden.|
| `kruinlijn`, `opTalud` | vervalt | zelfde opmerking als bij `Wegdeel` |

## Gebouwen en adressen

| BAG/BGT/IMGeo    | IBRO/EMSO | Opmerkingen |
| -------- | ------- | ------- |
| `Pand` | `Pand` | 1) Het betreft **grotendeels** dezelfde populatie. Dat deel van de populatie dat niet hetzelfde is, kan mapping problemen opleveren. 2) de geometrie is 3D, hier moet een 2D grondvlak (BGT) of bovenaanzichtgeometrie (BAG) uit afgeleid worden. |
| `OpenbareRuimte` | `OpenbareRuimte` | De populatie wordt kleiner: alleen namen van wegen en water worden nog opgenomen. Bij kunstwerken en andere objecten wordt in IBRO de naam bij het kunstwerk opgenomen. Bij IBRO is bij de openbare ruimte niet opgenomen om wat voor type het gaat, zoals in de BAG. Dit is af te leiden door geometrisch te kijken over wat voor fysiek object de openbare ruimte geometrie heen ligt. | 


## Overige bouwwerken / kunstwerken

| BGT/IMGeo    | IBRO/EMSO | Opmerkingen |
| -------- | ------- | ------- |
| `Overbruggingsdeel` | `Overbrugging` | Het betreft hier grotendeels de bestaande populatie overbruggingsdelen. Waar de populatie verschilt kan dat een probleem opleveren.| 
| `overbruggingIsBeweegbaar` | vervalt | Optionele IMGeo inhoud. Als een gemeente deze nu levert aan de BGT en wil blijven leveren is dit een probleem.| 
| `faunavoorziening` | vervalt | optionele IMGeo inhoud. Als een gemeente deze nu levert aan de BGT en wil blijven leveren is dit een probleem.| 
| `voedersilo` | vervalt | Optionele IMGeo inhoud, als een gemeente deze heeft en aan de LV levert is dit problematisch. | 
| `schuur` | `erfconstructie` | Optionele IMGeo inhoud. De IMGeo populatie schuren is aanvullend op de schuren die als BAG pand zijn geregistreerd. In  IBRO zijn dit erfconstructies. | 
| `draadraster` en `faunaraster` | `omheining` | optionele IMGeo inhoud. Als een gemeente deze nu levert aan de BGT en wil blijven leveren is dit een probleem.| 

## Functioneel gebied

| BGT/IMGeo    | IBRO/EMSO | Opmerkingen |
| -------- | ------- | ------- |
| meerdere plus classificaties | vervallen |  optionele IMGeo inhoud. Als een gemeente deze nu levert aan de BGT en wil blijven leveren is dit een probleem.| 
| `carpoolplaats` | `parkeerplaats` | optionele IMGeo inhoud. Carpoolplaats is niet meer van andere parkeerplaatsen te ondescheiden. Als een gemeente deze nu levert aan de BGT en wil blijven leveren is dit een probleem.| 

## Straatmeubilair 

| BGT/IMGeo    | IBRO/EMSO | Opmerkingen |
| -------- | ------- | ------- |
| meerdere plus classificaties van `Bak`, `Bord`, `Kast`, `Mast`, `Put`, `Straatmeubilair`, `Waterinrichtingselement`, `Paal`| vervallen / worden onder 1 classificatie gevat |  optionele IMGeo inhoud. Als een gemeente deze nu levert aan de BGT en wil blijven leveren is dit een probleem.|
| meerdere plus classificaties van `Paal` | worden onder 1 classificatie gevat |  optionele IMGeo inhoud. Als een gemeente deze nu levert aan de BGT en wil blijven leveren is dit een probleem.|
| `sensor` | vervalt |  optionele IMGeo inhoud. Als een gemeente deze nu levert aan de BGT en wil blijven leveren is dit een probleem.|
