# Overzicht informatiemodel IMIBRO

## Naam en Acroniemen

IMIBRO - Informatiemodel voor de Integrale Bronregistratie Objecten (IBRO)

## Definitie

In de Integrale Bronregistratie Objecten (IBRO) worden de gegevens vastgelegd omtrent gesynchroniseerde objecten uit de BAG, BGT en WOZ.
Het conceptueel informatiemodel IMIBRO definieert het informatiedomein van de IBRO en vormt de basis voor logische gegevensmodellen in het kader van de IBRO.

## Beschrijving

In [[EMSO]] is de basis gelegd voor een conceptueel informatiemodel voor integrale objectregistratie. Dit informatiemodel is verder uitgewerkt in het kader van de IBRO.

### Semantische kern

De semantische kern van IMIBRO is gebaseerd op [[NEN3610-2022]] en vormt de basis voor het conceptueel informatiemodel. Het model is opgebouwd uit een aantal domeinen, die samen het informatiedomein van de IBRO vormen.

De objecttypen die gedefinieerd zijn in IMIBRO zijn dan ook verdere invulling van de objecttypen die in [[NEN3610-2022]] zijn gedefinieerd. Deze objecttypen zijn uitgewerkt conform de principes beschreven in [[EMSO]] en gebruikmakend van [[MIM12]].

![Kern](model-docs/media/kern-overzicht.png "Overzicht semantische kern IMIBRO").

#### Levensfasen

Objecten kunnen zich in verschillende fasen van ontwikkeling bevinden. Zo'n fase van ontwikkeling van een object duiden we aan met het begrip levensfase. De verschillende levensfasen van een object tezamen vormen de levenscyclus van een object. Welke levensfasen worden onderscheiden is afhankelijk van het specifieke objecttype. In het informatiemodel komen vier hoofdsoorten objecttypen voor: reële objecten, functionele ruimten, registratieve ruimten en geografische ruimten. Elk van deze soorten objecttypen kent dezelfde indeling in hoofdfasen en meestal dezelfde indeling in levensfasen. Voor de meeste objecttypen van een bepaald soort objecttype zullen de statussen die het object in principe kan aannemen dan ook allemaal gelijk zijn, omdat deze in de regel voortvloeien uit de aard van het soort objecttype. Zo kan een object dat administratief wordt gevormd nooit een status "in aanbouw" kennen. Genuanceerde verschillen worden daarbij niet doorvertaald naar specifieke benamingen van statussen. [[EMSO]]

De mogelijke levensfasen per objecttype zijn hier terug te vinden in het hoofdstuk [[[#enumeraties]]].

<aside class="note">
In [[EMSO]] kennen alle objecttypen de mogelijke status `Afgevoerd`. Dit is in IMIBRO niet meer het geval. Zie [[[#wijzigingen-levensfasen]]] voor een toelichting.
</aside>

#### Geometrie

Voor de aspecten van geometrie in IMIBRO is aangesloten op hetgeen in [[EMSO]] is beschreven.

#### Overwegingen

In dit informatiemodel is er geen keuze gemaakt in het wel of niet abstract zijn van objecttypen. Dit is een bewuste keuze, omdat het informatiemodel IMIBRO niet bedoeld is om direct in een database of applicatie te worden geïmplementeerd, maar dient als basis voor verdere uitwerking. De keuze of een objecttype abstract of concreet is wordt pas gemaakt in de logische gegevensmodellen.

### De informatiedomeinen

IMIBRO is opgebouwd uit een aantal informatiedomeinen. In deze sectie worden verschillende domeinen toegelicht.

#### Groen

Het domein Groen in IMIBRO beschrijft de groene objecttypen in onze leefomgeving, zoals bossen, bomen en struiken

Binnen dit domein is [[[#informatiemodel_imibro_conceptueel_domein_groen_objecttype_begroeiing]]] de hoofdklasse. [[[#informatiemodel_imibro_conceptueel_domein_groen_objecttype_begroeiing]]] is een verdere invulling van het objecttype Begroeiing uit [[NEN3610-2022]].

Daarnaast sluit de opdeling van typen binnen het domein groen aan op de indeling van het [[IMBOR]].

![Groen](model-docs/media/groen-overzicht.png "Overzicht groen")

#### Bodem

Het domein bodem beschrijft het objecttype [onbegroeide grond](#informatiemodel_imibro_conceptueel_domein_bodem_objecttype_onbegroeide_grond). Dit is een oppervlakte die niet bedekt is met enige vorm van begroeiing, water, verharding, gebouwen of andere constructies. Het is een specialisatie van het objecttype `Bodem` uit [[NEN3610-2022]].

![Bodem](model-docs/media/bodem-overzicht.png "Overzicht bodem")

#### Water

In IMIBRO is beschrijft het domein water verschillende typen oppervlaktewater. Een oppervlaktewaterobject is een massa van water dat de bodem bedekt, of in normale omstandigheden kan bedekken. [[NEN3610-2022]].

![Water](model-docs/media/water-overzicht.png "Overzicht water")

De verschillende hoofdtypen oppervlaktewater die onderscheiden worden zijn [watervlakte](#informatiemodel_imibro_conceptueel_domein_water_objecttype_watervlakte), [watergang](#informatiemodel_imibro_conceptueel_domein_water_objecttype_watergang), [getijdengebied](#informatiemodel_imibro_conceptueel_domein_water_objecttype_getijdengebied) en [greppel](#informatiemodel_imibro_conceptueel_domein_water_objecttype_greppel).

#### Gebouwen

Het domein Gebouwen binnen IBRO vormt een centrale bron voor consistente en betrouwbare gebouwinformatie binnen gemeenten. Het legt de basis voor het kunnen registreren en gebruiken van gegevens over gebouwen in landelijke voorzieningen zoals de BAG, BGT en WOZ, en in gemeentelijke werkprocessen.
Het model is voorbereid op een toekomst waarin driedimensionale (3D) gebouwinformatie steeds belangrijker wordt en het gebruik van BIM in vergunningverlening eerder regel dan uitzondering is.

Binnen dit domein worden gebouwen op een gedetailleerde manier en op verschillende niveaus beschreven. Zo bestaat een [pand](#informatiemodel_imibro_conceptueel_domein_gebouwen_objecttype_pand) uit één of meerdere [panddelen](#informatiemodel_imibro_conceptueel_domein_gebouwen_objecttype_panddeel), die kunnen verschillen in bouwjaar of constructie. Daarnaast worden functiezones onderscheiden op basis van het vergunde gebruik (zoals wonen, werken of onderwijs) en gebruikzones op basis van het feitelijke gebruik (zoals bijvoorbeeld woning of winkelruimte). Deze scheiding maakt het mogelijk om gebouwen zowel fysiek als functioneel nauwkeurig te beschrijven.
Op deze wijze wordt de beschrijving van een gebouw in de IBRO opgebouwd uit verschillende gegevens "bouwsteentjes".
De gebouwgegevens die nodig zijn voor het vullen of genereren van de registratie van gebouwde objecten in de bestaande landelijke registraties BAG, BGT (en deels) WOZ zijn vervolgens af te leiden of te genereren op basis van deze bouwstenen. In sommige gevallen gaat het dan om het gebruik van een enkele bouwsteen. In andere gevallen is voor de afleiding een combinatie van één of meerdere van deze bouwstenen nodig.

![Gebouwen](model-docs/media/gebouwen-overzicht.png "Overzicht gebouwen")


Het domein Gebouw sluit nauw aan op nationale standaarden zoals [[NEN3610-2022]], [[NEN2580-2007]] (voor oppervlaktebepalingen) en is afgestemd op bredere landelijke ontwikkelingen, zoals [[EMSO]], het Federatief Datastelsel (FDS), en initiatieven rondom de indieningsvereisten voor de inzet van BIM bij de geautomatiseerde ondersteuning van het vergunningverleningproces.

In [[[#fig-gebouw-vanuit-fysiek-perspectief]]] is een voorbeeld van een gebouw vanuit fysiek perspectief weergegeven. In het fysieke perspectief zijn de contouren van het pand en de bijbehorende panddelen weergegeven. Een pand bestaat altijd uit minimaal één panddeel van het type [basisconstructie](#informatiemodel_imibro_conceptueel_domein_gebouwen_objecttype_basisconstructie), maar bestaat meestal ook uit meerdere panddelen. In dit voorbeeld is ook een afdak (carport) als panddeel zichtbaar.
De schuur in dit voorbeeld is een op zichzelf staand pand.

![Gebouw vanuit fysiek perspectief](media/gebouwen-voorbeeld-1.png "Gebouw vanuit fysiek perspectief")

Een gebouw kan ook vanuit een functioneel perspectief ([[[#fig-gebouw-vanuit-functieperspectief]]]) worden bekeken. In dit perspectief zijn de verschillende [functiezones](#informatiemodel_imibro_conceptueel_domein_gebouwen_objecttype_functiezone) zichtbaar. Een functiezone is een clustering van aaneengesloten ruimten met dezelfde functie, zoals deze is vastgesteld in het kader van de vergunningverlening. Een functiezone bevindt zich altijd op één [bouwlaag](#informatiemodel_imibro_conceptueel_domein_gebouwen_objecttype_bouwlaag) van een pand. Een bouwlaag kan meerdere functiezones hebben.

![Gebouw vanuit functieperspectief](media/gebouwen-voorbeeld-2.png "Gebouw vanuit functieperspectief")

Vanuit gebruiksperspectief ([[[#fig-gebouw-vanuit-gebruiksperspectief]]]) wordt een gebouw ingedeeld in [gebruikzones](#informatiemodel_imibro_conceptueel_domein_gebouwen_objecttype_gebruikzone). Dit is een clustering van aaneengesloten ruimten, waarvoor geldt dat deze deel uitmaakt van een zelfstandige eenheid van gebruik en zoals deze zich voordoet in de werkelijkheid (het feitelijke gebruik). Gebruikzones liggen altijd binnen één pand en op één of meer bouwlagen. Een pand kan meerdere gebruikzones hebben.

![Gebouw vanuit gebruiksperspectief](media/gebouwen-voorbeeld-3.png "Gebouw vanuit gebruiksperspectief")

Op deze wijze wordt een gebouw, zowel op basis van het fysiek voorkomen, als op basis van de vergunde situatie en op basis van het feitelijk gebruik, beschreven.

#### Verharding

Het domein Verharding beschrijft de verharde oppervlakken in de fysieke leefomgeving, zoals wegen, fietspaden, trottoirs, pleinen en parkeerplaatsen.

![Verharding](model-docs/media/verharding-overzicht.png "Overzicht verharding")

Verhardingen hebben een samenhang met functionele ruimten, zoals transportruimten. Zo kunnen [wegverbindingen](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_wegverbinding) en [-knopen](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_wegknoop) functioneel gekoppeld zijn aan verhardingen, om zo de verkeersstructuur en -stromen en de fysieke inrichting van de openbare ruimte te representeren.

#### Kunstwerken

Het domein Kunstwerken beschrijft de kunstwerken in de fysieke leefomgeving, zoals bruggen, tunnels en sluizen.
Kunstwerken zijn civiel-technische constructies voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen.

![Kunstwerken](model-docs/media/kunstwerken-overzicht.png "Overzicht kunstwerken")

De hoofdtypen kunstwerken die onderscheiden worden zijn [overbrugging](#informatiemodel_imibro_conceptueel_domein_kunstwerken_objecttype_overbrugging), [ondertunneling](#informatiemodel_imibro_conceptueel_domein_kunstwerken_objecttype_ondertunneling), [waterstaatkundig kunstwerk](#informatiemodel_imibro_conceptueel_domein_kunstwerken_objecttype_waterstaatkundig_kunstwerk) en [Kunstwerkdeel](#informatiemodel_imibro_conceptueel_domein_kunstwerken_objecttype_kunstwerkdeel).

#### Overige constructies

Het domein overige constructies beschrijft constructies die geen gebouw, verharding, of kunstwerk zijn, maar wel een belangrijke rol spelen in de fysieke leefomgeving. Dit kunnen bijvoorbeeld objecten zijn zoals afvalcontainer, putdeksels, lantaarnpalen of andere infrastructuur.

![Overige constructies](model-docs/media/overige_constructies-overzicht.png "Overzicht overige constructies")

#### Netwerk

Netwerken, in het bijzonder transportnetwerken, zijn in IMIBRO opgenomen als een extensie op het generieke INSPIRE netwerkmodel [[INSPIRE-D2.10.1]]. Ten behoeve van de IBRO is een selectie uit het netwerkmodel overgenomen, vertaald naar het Nederlands, en gemodelleerd conform [[MIM12]].

![Netwerk](model-docs/media/netwerk.png "Overzicht Netwerk")

Voor de inhoud van het informatiemodel betreffende Netwerk in IMIBRO, zie de sectie [[[#domein-netwerk]]].

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

##### Transportnetwerk

Het Transportnetwerk is een nadere uitwerking van Netwerk, specifiek gericht op het modelleren van infrastructuur voor transport en mobiliteit. In IMIBRO worden twee transportnetwerken onderscheiden: wegen en spoorwegen. Het netwerk is een verdere uitwerking van het virtuele object Transportruimte in het basismodel [[NEN3610-2022]].

Iedere transportruimte kan een hyperverbinding hebben met functionele ruimten die een logische samenhang kennen met de transportruimte, zoals parkeerplaatsen of bushaltes. Deze hyperverbindingen zijn geen fysieke verbindingen, maar abstracte verwijzingen tussen de objecten en de transportruimte.

Daarnaast kan een transportruimte ook op reële objecten liggen, zoals verharde wegen.

<aside class="note">
In IMIBRO is deze relatie expliciet gemodelleerd, maar bij verdere uitwerking in een logisch gegevensmodel kan deze relatie impliciet worden gemaakt en concreet worden ingevuld door een netwerkverwijzing te leggen vanuit het reëel object naar de transportruimte. Dit is afhankelijk van de implementatiecontext en de specifieke eisen van de toepassing.
</aside>

![Netwerk](model-docs/media/transportnetwerk-overzicht.png "Overzicht transportruimten")

###### Wegennetwerk

Een wegennetwerk is een type transportnetwerk dat specifiek gericht is op het modelleren van wegen. Het betreft de invulling van het [[NEN3610-2022]] type Wegverkeerruimte. Het beschrijft de functionele structuur van weginfrastructuur ten behoeve van verkeer.

![Wegennetwerk](model-docs/media/wegennetwerk-overzicht.png "Overzicht wegennetwerk")

Het model is hiërarchisch opgebouwd en onderscheidt verschillende niveaus van wegonderdelen, elk bedoeld voor specifieke verkeersstromen en -gebruikers.

- Wegverbindingen vormen de hoofdelementen van het netwerk. Ze representeren doorgaans verharde of onverharde wegen en kunnen meerdere routenummers dragen. Wegverbindingen kunnen openbaar of niet-openbaar zijn.
- Baanverbindingen zijn delen van een weg die bestemd zijn voor specifieke verkeersdeelnemers, zoals rijbanen of afritten. Ze zijn altijd onderdeel van een wegverbinding.
- Strookverbindingen zijn gemarkeerde delen van een baan, zoals rijstroken, en vormen het fijnmazigste onderdeel van de verkeersruimte.

Deze verbindingen worden met elkaar verbonden door transportknopen:

- Wegknopen vormen begin-, eind- of keuzepunten in het netwerk en zijn gekoppeld aan wegverbindingen.
- Baanknopen en strookknopen markeren respectievelijk de start- en eindpunten van baan- en strookverbindingen.

Alle verbindingen vallen onder het type Wegverkeerruimteverbinding, en hebben daarmee een rijrichting. Deze structuur maakt het mogelijk om verschillende verkeersstructuren (wegen, banen, stroken) gedetailleerd te modelleren.

Een wegverbinding of wegknoop kan verbonden zijn met één of meerdere openbare ruimten.

<aside class="note">
De relatie vanuit wegverbinding en wegknoop met openbare ruimte is expliciet gemodelleerd in IMIBRO, maar kan in een logisch gegevensmodel impliciet worden gemaakt en concreet worden ingevuld met een netwerkverwijzing vanuit de openbare ruimte naar de wegverbinding of wegknoop. Dit is afhankelijk van de implementatiecontext en de specifieke eisen van de toepassing.
</aside>

Tot slot kunnen hectometerpunten als netwerkeigenschappen aan baanverbindingen worden gekoppeld door middel van een netwerkverwijzing.

Zie de sectie [[[#domein-wegennetwerk]]] voor een gedetailleerd overzicht van de verschillende typen verbindingen en knopen binnen een wegennetwerk.

###### Spoorwegennetwerken

Het spoorwegennetwerk is een type transportnetwerk dat specifiek gericht is op het modelleren van spoorwegen. Het betreft de invulling van het [[NEN3610-2022]] type Spoorverkeerruimte.

![Netwerk](model-docs/media/spoorwegennetwerk-overzicht.png "Overzicht spoorwegennetwerken")

Het beschrijft de verkeerskundige inrichting van het spoorvervoer in Nederland. Het model richt zich op de functionele structuur van spoorwegen, met een onderscheid tussen knooppunten en verbindingen.

- Spoorverbindingen vormen de basiselementen van het spoornetwerk. Ze beschrijven de functionele verbinding tussen twee knopen en vertegenwoordigen het traject waarover treinen zich verplaatsen.
- Spoorwegknopen representeren de punten in het netwerk waar spoorverbindingen samenkomen of eindigen. Dit zijn typische begin-, eind- of keuzepunten voor spoorverkeer, zoals wissels, stations of eindpunten van een lijn.

Zowel de spoorverbindingen als spoorwegknopen zijn specialisaties van Spoorverkeerruimte, waarmee ze als functionele onderdelen van het spoorsysteem worden beschouwd. Spoorverbindingen zijn daarnaast ook een type Transportverbinding, terwijl spoorwegknopen ook onder Transportknoop vallen.

Zie de sectie [[[#domein-spoorwegennetwerk]]] voor meer details over het domein spoorwegennetwerk.

#### Functionele ruimten

Functionele ruimten zijn ruimten die een functie kennen. In dit domein worden de functionele ruimten beschreven die niet al zijn opgenomen in andere domeinen.

![Functionele ruimten](model-docs/media/functionele_ruimten-overzicht.png "Overzicht functionele ruimten")

#### Bestuurlijke gebieden

Het domein bestuurlijke gebieden beschrijft de bestuurlijke indeling van Nederland. Dit betreft de indeling in gemeenten, wijken, buurten en andere bestuurlijke eenheden.

Het conceptuele informatiemodel voor bestuurlijke gebieden is wel opgenomen in IMIBRO, maar wordt in een apart traject verder ontwikkeld. Zie [[IMSOR-BG]] voor de huidige beschrijving van het informatiemodel.

#### Registratieve ruimten

In het domein registratieve ruimten worden registratieve ruimten binnen een gemeentegebied gedefinieerd, zoals adresseerbare objecten, wijken, buurten en woonplaatsen. Deze objecttypen zijn van administratief belang, zoals bijvoorbeeld voor het adresseren van objecten.

<aside class="note">
Voor het objecttype adresseerbaar object is in het informatiemodel het specifieker type benoemde plaats opgenomen. Dit betekent niet dat alle adresseerbare objecten ook benoemde plaatsen zijn. Naast benoemde plaatsen zijn er ook andere adresseerbare objecten bijvoorbeeld gerelateerd aan de bebouwde omgeving (bijvoorbeeld de verblijfsobjecten uit de BAG [[BAG10]]).
</aside>

![Registratieve ruimten](model-docs/media/registratieve_ruimten-overzicht.png "Overzicht registratieve ruimten")

#### Geografische ruimten

Onder het domein geografische ruimten vallen ruimten die bekendstaan onder een vanuit historie of gebruik bekende benaming of een fysisch-geografische samenhang kennen [[NEN3610-2022]].

![Geografische ruimten](model-docs/media/geografische_ruimten-overzicht.png "Overzicht geografische ruimten")

De hoofdtypen zijn [bebouwingskern](#informatiemodel_imibro_conceptueel_domein_geografische_ruimten_objecttype_bebouwingskern), [streek](#informatiemodel_imibro_conceptueel_domein_geografische_ruimten_objecttype_streek), [landschappelijk gebied](#informatiemodel_imibro_conceptueel_domein_geografische_ruimten_objecttype_landschappelijk_gebied) en [reliëfzone](#informatiemodel_imibro_conceptueel_domein_geografische_ruimten_objecttype_reliefzone).
