# Overzicht

## Naam en Acroniemen

IMIBRO - Informatiemodel voor de Integrale Bronregistratie Objecten (IBRO)

## Definitie

In de Integrale Bronregistratie Objecten (IBRO) worden de gegevens vastgelegd omtrent gesynchroniseerde objecten uit de BAG, BGT en WOZ.
Het conceptueel informatiemodel IMIBRO definieert het informatiedomein van de IBRO en vormt de basis voor logische gegevensmodellen in het kader van de IBRO.

## Beschrijving

In [[EMSO]] is de basis gelegd voor een conceptueel informatiemodel voor integrale objectregistratie. Dit informatiemodel is verder uitgewerkt in het kader van de IBRO.

### Semantische kern

De semantische kern van IMIBRO is gebaseerd op [[NEN3610-2022]] en vormt de basis voor het conceptueel informatiemodel. Het model is opgebouwd uit een aantal domeinen, die samen het informatiedomein van de IBRO vormen.

De objecttypen die gedefinieerd zijn in IMIBRO zijn dan ook verdere invulling van de objecttypen die in [[NEN3610-2022]] zijn gedefinieerd.

![Algemeen](model-docs/media/algemeen-overzicht.png "Overzicht semantische kern IMIBRO").

#### Levensfasen

Objecten kunnen zich in verschillende fasen van ontwikkeling bevinden. Zo’n fase van ontwikkeling van een object duiden we aan met het begrip levensfase. De verschillende levensfasen van een object tezamen vormen de levenscyclus van een object. Welke levensfasen worden onderscheiden is afhankelijk van het specifieke objecttype. In het informatiemodel komen vier hoofdsoorten objecttypen voor: reële objecten, functionele ruimten, registratieve ruimten en geografische ruimten. Elk van deze soorten objecttypen kent dezelfde indeling in hoofdfasen en meestal dezelfde indeling in levensfasen. Voor de meeste objecttypen van een bepaald soort objecttype zullen de statussen die het object in principe kan aannemen dan ook allemaal gelijk zijn, omdat deze in de regel voortvloeien uit de aard van het soort objecttype. Zo kan een object dat administratief wordt gevormd nooit een status "in aanbouw" kennen. Genuanceerde verschillen worden daarbij niet doorvertaald naar specifieke benamingen van statussen. [[EMSO]]

De mogelijke levensfasen per objectype zijn hier terug te vindien in het hoofdstuk [[[#enumeraties]]].

<aside class="note">
In [[EMSO]] kenden alle objecttypen de mogelijke status `Afgevoerd`. Dit is in IMIBRO niet meer het geval. Zie [[[#wijzigingen-levensfasen]]] voor een toelichting.
</aside>

#### Geometrie

Voor de aspecten van geometrie in IMIBRO is aangesloten op hetgeen in [[EMSO]] is beschreven.

### De informatiedomeinen

IMIBRO is opgebouwd uit een aantal informatiedomeinen. In deze sectie worden verschillende domeinen toegelicht.

#### Netwerken

Voor het modelleren van netwerken, in het bijzonder transportnetwerken, is IMIBRO gemodelleerd als een extensie op het generieke INSPIRE netwerkmodel [[INSPIRE-D2.10.1]]. Ten behoeve van de IBRO is een selectie uit het netwerkmodel overgenomen, vertaald naar het Nederlands, en gemodelleerd conform [[MIM12]].

![Netwerk](model-docs/media/netwerk.png "Overzicht netwerken")

Voor de inhoud van het informatiemodel betreffende netwerken in IMIBRO, zie de sectie [[[#domein-netwerk]]].

##### Netwerkstructuur

Een netwerk bestaat uit een samenhangende verzameling van netwerkelementen, die elk een functie vervullen binnen het netwerk. Binnen transportnetwerken zijn dit doorgaans knopen (keuzepunten) en verbindingen (trajecten tussen knopen). Deze structuur maakt het mogelijk om beweging en routing binnen het netwerk te modelleren.

- Een knoop vertegenwoordigt een belangrijke positie in het netwerk, zoals een kruispunt of wissel, en heeft altijd een geometrische representatie als punt.
- Een verbinding verbindt twee knopen met elkaar en vormt een homogeen pad. De geometrie van een verbinding is een lijn (curve).

Alle netwerkelementen zijn gerelateerd aan het overkoepelende netwerk waarin ze zich bevinden. Dit netwerk representeert de functionele structuur van de reële infrastructuur, zoals wegen of spoorwegen, en is daarmee onlosmakelijk verbonden met de fysieke werkelijkheid.

##### Relaties met objecten en eigenschappen

Een transportnetwerk beschrijft de functionele inrichting van de reële infrastructuur en is daar onlosmakelijk mee verbonden. Bij de aanleg van nieuwe infrastructuur vormt het functionele ontwerp vaak de basis voor het fysieke ontwerp en de realisatie.

Een netwerk is iets abstracts, maar kan voor visualisatie en positionering gekoppeld worden aan geometrie van de reële infrastructuur. Dit gebeurt via directe geometrietoekenning aan het netwerkelement of verwijzing naar geometrieën van fysieke objecten, zoals wegen of spoorlijnen.

Daarbij geldt het volgende ontwerpprincipe:

_Knopen en verbindingen bevinden zich binnen de contouren van de bijbehorende reële objecten._

Eigenschappen en objecten die relevant zijn voor het functioneren van het netwerk, zoals maximumsnelheden, straatnamen of objecten zoals haltes en verkeersborden, worden gekoppeld aan verbindingen binnen het netwerk. Wanneer deze eigenschappen slechts op een deel van de verbinding van toepassing zijn, gebruiken we lineaire netwerkverwijzingen (linear referencing) om de locatie van verandering aan te geven zonder de verbinding zelf op te splitsen.

##### Netwerkverwijzingen

Om eigenschappen of verschijnselen op of langs een verbinding vast te leggen, bijvoorbeeld snelheidslimieten, of het voorkomen van bepaalde verkeersborden, worden netwerkverwijzingen gebruikt. Dit zijn administratieve verwijzingen naar specifieke delen van een verbinding, zonder dat de verbinding zelf hoeft te worden opgesplitst.

Er kunnen verschillende soorten netwerkverwijzingen bestaan. In IMIBRO beperken we ons tot twee soorten netwerkverwijzingen:

- Simpele puntverwijzing: verwijst naar een specifiek punt op een verbinding, aangeduid met een afstand tot het begin van de verbinding (eventueel met een offset links/rechts van de middellijn).
- Simpele lineaire verwijzing: verwijst naar een deel van een verbinding, gespecificeerd met een begin- en eindpositie langs de verbinding, eveneens met een optionele offset.

> Voorbeeld:
>
> Op een wegverbinding van 1 km geldt vanaf 200 meter een maximumsnelheid van 70 km/h. In plaats van de verbinding op te delen, wordt deze snelheidswijziging administratief vastgelegd via lineaire verwijzing.

Door gebruik van deze verwijzingen kan het netwerkmodel rijk en gedetailleerd worden ingericht, zonder dat de onderliggende structuur onnodig complex wordt gemaakt. Dit ondersteunt toepassingen als verkeersanalyse, routering, beheer van infrastructuur en beleidsontwikkeling.

##### Transportnetwerken

Transportnetwerken zijn een subtype van netwerken, specifiek gericht op het modelleren van infrastructuur voor transport en mobiliteit. In IMIBRO worden twee transportnetwerken onderscheiden: wegen en spoorwegen. Netwerken zijn een verdere uitwerking van de virtuele objecten transportruimten in het basismodel [[NEN3610-2022]].

Iedere transportruimte kan een hyperverbinding hebben met functionele ruimten die een logische samenhang kennen met de tranportruimte, zoals parkeerplaatsen of bushaltes. Deze hyperverbindingen zijn geen fysieke verbindingen, maar abstracte verwijzingen tussen de objecten en de transportruimte.

Daarnaast kan een transportruimte ook op reëele objecten liggen, zoals verharde wegen.

<aside class="note">
In IMIBRO is deze relatie expliciet gemodelleerd, maar bij verdere uitwerking in een logisch gegevensmodel kan deze relatie impliciet worden gemaakt en concreet worden ingevuld door een netwerverwijzing te leggen vanuit het reëele object naar de transportruimte. Dit is afhankelijk van de implementatiecontext en de specifieke eisen van de toepassing.
</aside>

![Netwerk](model-docs/media/transportnetwerk.png "Overzicht transportruimten")

###### Wegennetwerken

Een wegennetwerk is een type transportnetwerk dat specifiek gericht is op het modelleren van wegen. Het betreft de invulling van het [[NEN3610-2022]] type Wegverkeerruimte. Het beschrijft de functionele structuur van weginfrastructuur ten behoeve van verkeer.

![Netwerk](model-docs/media/wegennetwerk-overzicht.png "Overzicht wegennetwerken")

Het model is hiërarchisch opgebouwd en onderscheidt verschillende niveaus van wegonderdelen, elk bedoeld voor specifieke verkeersstromen en -gebruikers.

- Wegverbindingen vormen de hoofdelementen van het netwerk. Ze representeren doorgaans verharde of onverharde wegen en kunnen meerdere routenummers dragen. Wegverbindingen kunnen openbaar of niet-openbaar zijn.
- Baanverbindingen zijn delen van een weg die bestemd zijn voor specifieke verkeersdeelnemers, zoals rijbanen of afritten. Ze zijn altijd onderdeel van een wegverbinding.
- Strookverbindingen zijn gemarkeerde delen van een baan, zoals rijstroken, en vormen het fijnmazigste onderdeel van de verkeersruimte.

Deze verbindingen worden met elkaar verbonden via transportknopen:

- Wegknopen vormen begin-, eind- of keuzepunten in het netwerk en zijn gekoppeld aan wegverbindingen.
- Baanknopen en strookknopen markeren respectievelijk de start- en eindpunten van baan- en strookverbindingen.

Alle verbindingen vallen onder het type Wegverkeerruimteverbinding, en hebben daarmee een rijrichting. Deze structuur maakt het mogelijk om verschillende verkeersstructuren (wegen, banen, stroken) gedetailleerd te modelleren.

Een wegverbinding of wegknoop kan verbonden zijn met een of meerdere openbare ruimten.

<aside class="note">
De relatie vanuit wegverbinding en wegknoop met openbare ruimte is expliciet gemodelleerd in IMIBRO, maar kan in een logisch gegevensmodel impliciet worden gemaakt en concreet worden ingevuld met een netwerkverwijzing vanuit de openbare ruimte naar de wegverbinding of wegknoop. Dit is afhankelijk van de implementatiecontext en de specifieke eisen van de toepassing.
</aside>

Tot slot kunnen hectometerpunten als netwerkeigenschappen aan baanverbindingen worden gekoppeld doormiddel van een netwerkverwijzing.

Zie de sectie [[[#domein-wegennetwerk]]] voor een gedetailleerd overzicht van de verschillende typen verbindingen en knopen binnen een wegennetwerk.

###### Spoorwegennetwerken

Het spoorwegennetwerk is een type transportnetwerk dat specifiek gericht is op het modelleren van spoorwegen. Het betreft de invulling van het [[NEN3610-2022]] type Spoorverkeerruimte.

![Netwerk](model-docs/media/spoorwegennetwerk.png "Overzicht spoorwegennetwerken")

Het beschrijft de verkeerskundige inrichting van het spoorvervoer in Nederland. Het model richt zich op de functionele structuur van spoorwegen, met een onderscheid tussen knooppunten en verbindingen.

- Spoorverbindingen vormen de basiselementen van het spoornetwerk. Ze beschrijven de functionele verbinding tussen twee knopen en vertegenwoordigen het traject waarover treinen zich verplaatsen.
- Spoorwegknopen representeren de punten in het netwerk waar spoorverbindingen samenkomen of eindigen. Dit zijn typische begin-, eind- of keuzepunten voor spoorverkeer, zoals wissels, stations of eindpunten van een lijn.

Zowel de spoorverbindingen als spoorwegknopen vallen zijn specialisaties van Spoorverkeerruimte, waarmee ze als functionele onderdelen van het spoorsysteem worden beschouwd. Spoorverbindingen zijn daarnaast ook een type Transportverbinding, terwijl spoorwegknopen ook onder Transportknoop vallen.

Zie de sectie [[[#domein-spoorwegennetwerk]]] voor een meer details over het domein spoorwegennetwerk.
