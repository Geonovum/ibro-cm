# Wijzigingen ten opzichte van DiS Geo : Eisen aan model samenhangende objectenregistratie

Dit conceptueel informatiemodel is een verdere uitwerking van het informatiemodel dat in 2021 is gepresenteerd in de publicatie "DiS Geo: Eisen aan model samenhangende objectenregistratie" [[EMSO]].

Het volgende is eeen overzicht van de belangrijkste wijzigingen ten opzichte [[EMSO]]:

## Wijziginen aan levensfasen {#wijzigingen-levensfasen}

In [[EMSO]] kennen alle objecttypen de levensfase `Afgevoerd`. Dit in IMIBRO niet meer het geval. De levensfase `Afgevoerd` beschrrijft in [[EMSO]] de fase van een object wat ten onrechte is opgevoerd in de registratie, of waarvan is vastgesteld dat het ontwerp of plan voor het realiseren van het object niet geleid heeft tot feitelijke realisatie van het object.

De bedoeling van de levensfase is om het levenscyclus van een object in de werkelijkheid zo goed mogelijk te beschrijven. Het wel of niet beschreven zijn van een object in een registratie is hier geen onderdeel van. Met die reden is besloten om dat aspect niet meer in de levensfasen in IMIBRO op te nemen. Dit aspect kan wel beschreven worden in een logisch model, waar bepaald wordt hoe de registratiestatus van een object eruitziet.

In plaats van de status `Afgevoerd` is in IMIBRO de status `Niet gerealiseerd` opgenomen. Dit is een status die kan worden toegekend aan objecten waarvan het ontwerp of plan uiteindelijk niet is gerealiseerd.

## Wijzigingen aan Water {#wijzigingen-water}

### Wijziging aan bestaande objecttypen {#wijzigingen-water-objecttypen}

| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Watergang](https://docs.geostandaarden.nl/disgeo/emso/#watergang) | Attribuutsoort `watervoerend` is verwijderd. | Verwijderd vanwege toevoeging objecttype [Greppel](#informatiemodel_imibro_conceptueel_domein_water_objecttype_greppel). (Zie [[[#wijzigingen-water-objecttypen-nieuw]]]) |

### Nieuwe objecttypen {#wijzigingen-water-objecttypen-nieuw}

| Objecttype | Reden |
| ---------- | ------------- |
| [Greppel](#informatiemodel_imibro_conceptueel_domein_water_objecttype_greppel) | Greppel is als apart objecttype naast [Watergang](#informatiemodel_imibro_conceptueel_domein_water_objecttype_watergang) geïntroduceerd. Dit sluit ook aan op [[IMBOR]], [[GWSW]] en [[BGT12]]. |

### Verwijderde objecttypen {#wijzigingen-water-objecttypen-verwijderd}

| Objecttype | Reden |
| ---------- | ------------- |
| [Bron](https://docs.geostandaarden.nl/disgeo/emso/#bron) | Verwijderd omdat het objecttype heel beperkt wordt opgenomen in huidige registraties. |

## Wijzigingen aan Groen {#wijzigingen-groen}

### Wijzinging aan bestaande objecttypen {#wijzigingen-groen-objecttypen}

| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Houtsingel](https://docs.geostandaarden.nl/disgeo/emso/#houtsingel) | Attribuutsoort `geometrie` krijgt datatype `GM_Surface` (vlak). | Dit sluit aan op [[IMBOR]]. |
| [Struik](https://docs.geostandaarden.nl/disgeo/emso/#struiken) | Attribuutsoort `indicatieHaag` is verwijderd. | Verwijderd vanwege toevoeging objecttype [Haag](#informatiemodel_imibro_conceptueel_domein_groen_objecttype_haag). (Zie [[[#wijzigingen-groen-objecttypen-nieuw]]]) |

### Nieuwe objecttypen {#wijzigingen-groen-objecttypen-nieuw}

| Objecttype | Reden |
| ---------- | ------------- |
| [Haag](#informatiemodel_imibro_conceptueel_domein_groen_objecttype_haag) | Haag is als apart objecttype naast Struiken geïntroduceerd. Dit sluit ook aan op [[IMBOR]] en [[BGT12]]. |

### Verwijderde objecttypen {#wijzigingen-groen-objecttypen-verwijderd}

| Objecttype | Reden |
| ---------- | ------------- |
| [Bomenrij](https://docs.geostandaarden.nl/disgeo/emso/#bomenrij) | Verwijderd omdat het objecttype een aanvullende structuur is op Bomen in [[IMBOR]].      |
| [Tuunwal](https://docs.geostandaarden.nl/disgeo/emso/#tuunwal) | Verwijderd omdat het objecttype heel beperkt wordt opgenomen in huidige registraties. |

## Wijzigingen aan Gebouw {#wijzigingen-gebouwen}

### Wijziging aan bestaande objecttypen {#wijzigingen-gebouw-objecttypen}

| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Gebouw](https://docs.geostandaarden.nl/disgeo/emso/#gebouw) | Hernoemd naar [Pand](#informatiemodel_imibro_conceptueel_domein_gebouwen_objecttype_pand). | Aansluiting op het Gemeentelijk Gebouwinformatiemodel, waar is gekozen voor de naam Pand in plaats van de naam Gebouw zoals in de SOR. De BAG afbakeningscriteria blijven behouden. Dit om de BAG bijhouding niet te verstoren. |

### Nieuwe objecttypen {#wijzigingen-gebouw-objecttypen-nieuw}

| Objecttype | Reden |
| ---------- | ------------- |
| [Panddeel](#informatiemodel_imibro_conceptueel_domein_gebouwen_objecttype_panddeel) | Aansluiting op het Gemeentelijk Gebouwinformatiemodel. |
| [Functiezone](#informatiemodel_imibro_conceptueel_domein_gebouwen_objecttype_functiezone) | Aansluiting op het Gemeentelijk Gebouwinformatiemodel. |
| [Gebruikzone](#informatiemodel_imibro_conceptueel_domein_gebouwen_objecttype_gebruikzone) | Aansluiting op het Gemeentelijk Gebouwinformatiemodel. |

### Verwijderde objecttypen {#wijzigingen-gebouw-objecttypen-verwijderd}

| Objecttype | Reden |
| ---------- | ------------- |
| [Gebouwcomponent](https://docs.geostandaarden.nl/disgeo/emso/#gebouwcomponent) | Aansluiting op het Gemeentelijk Gebouwinformatiemodel. |
| [Toegangsdeur](https://docs.geostandaarden.nl/disgeo/emso/#toegangsdeur) | Aansluiting op het Gemeentelijk Gebouwinformatiemodel. |
| [Open Bouwwerk](https://docs.geostandaarden.nl/disgeo/emso/#open-bouwwerk) | Aansluiting op het Gemeentelijk Gebouwinformatiemodel. |
| [Gebouwzone](https://docs.geostandaarden.nl/disgeo/emso/#gebouwzone) | Aansluiting op het Gemeentelijk Gebouwinformatiemodel. |

## Wijzigingen aan Kunstwerk {#wijzigingen-kunstwerken}

### Wijziging aan bestaande objecttypen {#wijzigingen-kunstwerken-objecttypen}
| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Kunstwerk](https://docs.geostandaarden.nl/disgeo/emso/#kunstwerk) | Het type kunstwerk `Flyover` is ene subtype van `Viaduct` geworden. | Een flyover is een deelverzameling van viaduct. |

## Wijzigingen in Overige constructies {#wijzigingen-overige-constructies}

### Nieuwe objecttypen {#wijzigingen-overige-constructies-objecttypen-nieuw}

| Objecttype | Reden |
| ---------- | ------------- |
| [Erfconstructie](#informatiemodel_imibro_conceptueel_domein_overige_constructies_objecttype_erfconstructie) | Aansluiting op Gemeentelijk Gebouwinformatiemodel. |

## Wijzigingen aan Transportuimten

Het model voor tranportuimten is hergebaseerd op het generieke INSPIRE netwerkmodel [[INSPIRE-D2.10.1]].

### Wijziging aan bestaande objecttypen {#wijzigingen-transportuimten-objecttypen}

| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Wegknoop](https://docs.geostandaarden.nl/disgeo/emso/#weg) | Het objecttype `Wegknoop` is een specialisatie geworden van [Transportknoop](#informatiemodel_imibro_conceptueel_domein_transportnetwerk_objecttype_transportknoop). | Dit sluit aan op het generieke INSPIRE netwerkmodel [[INSPIRE-D2.10.1]]. |
| [Wegknoop](https://docs.geostandaarden.nl/disgeo/emso/#weg) | In de definitie van de domeinwaarde `Verkeersplein`, behorende bij attribuutsoort `Type knoop`, is het gedeelte "uit tenminste 3 richtingen" verwijderd. | Het is niet altijd het geval dat er sprake is van verkeer uit tenminste 3 richtingen, bijvoorbeeld bij een verkeersplein in aanbouw. Net zoals bij de definitie van `Rotonde` is gekozen om dit weg te laten. |
| [Wegverbinding](https://docs.geostandaarden.nl/disgeo/emso/#wegverbinding) | Het objecttype `Wegverbinding` is een specialisatie geworden van [Transportverbinding](#informatiemodel_imibro_conceptueel_domein_transportnetwerk_objecttype_transportverbinding). | Dit sluit aan op het generieke INSPIRE netwerkmodel [[INSPIRE-D2.10.1]]. |
| [Wegverbinding](https://docs.geostandaarden.nl/disgeo/emso/#wegverbinding) | De naam van domeinwaarde `Fietspad`, behorende bij attribuutsoort `Type baan`, is gewijzigd naar `Fietspadbaan`. | Hiermee wordt onderscheid gemaakt tussen de domeinwaarde `Fietspad` als subtypering van [Wegverbinding](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_wegverbinding) versus `Fietspad` als subtypering van [Baanverbinding](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_baanverbinding). |
| [Wegverbinding](https://docs.geostandaarden.nl/disgeo/emso/#wegverbinding) | De naam van domeinwaarde `Ruiterpad`, behorende bij attribuutsoort `Type baan`, is gewijzigd naar `Ruiterpadbaan`. | Hiermee wordt onderscheid gemaakt tussen de domeinwaarde `Ruiterpad` als subtypering van [Wegverbinding](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_wegverbinding) versus `Ruiterpad` als subtypering van [Baanverbinding](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_baanverbinding). |
| [Wegverbinding](https://docs.geostandaarden.nl/disgeo/emso/#wegverbinding) | De naam van domeinwaarde `Veerverbinding`, behorende bij attribuutsoort `Type baan`, is gewijzigd naar `Veerverbindingbaan`. | Hiermee wordt onderscheid gemaakt tussen de domeinwaarde `Veerverbinding` als subtypering van [Wegverbinding](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_wegverbinding) versus `Veerverbinding` als subtypering van [Baanverbinding](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_baanverbinding). |
| [Wegverbinding](https://docs.geostandaarden.nl/disgeo/emso/#wegverbinding) | De naam van domeinwaarde `Voetpad`, behorende bij attribuutsoort `Type baan`, is gewijzigd naar `Voetpadbaan`. | Hiermee wordt onderscheid gemaakt tussen de domeinwaarde `Voetpad` als subtypering van [Wegverbinding](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_wegverbinding) versus `Voetpad` als subtypering van [Baanverbinding](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_baanverbinding). |
| [Wegverbinding](https://docs.geostandaarden.nl/disgeo/emso/#wegverbinding) | Domeinwaarde `Tegenovergestelde richting` is toegevoegd aan het waardetype van attribuutsoort `rijrichting`. | Met de aansluiting op het generieke INSPIRE netwerkmodel [[INSPIRE-D2.10.1]], is het noodzakelijk om deze toevoeging te maken. Een verbinding kan één kan op gedefinieerd worden, maar kan functioneel een tegenovergestelde rijrichting toegewezen krijgen. |
| [Spoorverbinding](https://docs.geostandaarden.nl/disgeo/emso/#spoorverbinding) | De naam van domeinwaarde `Nationaal Spoor`, behorende bij attribuutsoort `Type spoor`, is gewijzigd naar `Nationale Spoorverbinding`. | Consistentere naamgeving van subtyperingen. |
| [Spoorverbinding](https://docs.geostandaarden.nl/disgeo/emso/#spoorverbinding) | De naam van domeinwaarde `Lokaal Spoor`, behorende bij attribuutsoort `Type spoor`, is gewijzigd naar `Lokale Spoorverbinding`. | Consistentere naamgeving van subtyperingen. |

### Nieuwe objecttypen {#wijzigingen-transportuimten-objecttypen-nieuw}

| Objecttype | Reden |
| ---------- | ------------- |
| [Transportknoop](#informatiemodel_imibro_conceptueel_domein_transportnetwerk_objecttype_transportknoop) | Dit objecttype is toegevoegd om transportruimten te verbinden met het generieke INSPIRE netwerkmodel [[INSPIRE-D2.10.1]]. |
| [Transportverbinding](#informatiemodel_imibro_conceptueel_domein_transportnetwerk_objecttype_transportverbinding) | Dit objecttype is toegevoegd om transportruimten te verbinden met het generieke INSPIRE netwerkmodel [[INSPIRE-D2.10.1]]. |
| [Baanverbinding](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_baanverbinding) | Dit objecttype is toegevoegd om de hiërarchische structuur van het wegennetwerk te ondersteunen. |
| [Strookverbinding](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_strookverbinding) | Dit objecttype is toegevoegd om de hiërarchische structuur van het wegennetwerk te ondersteunen. |
| [Baanknoop](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_baanknoop) | Dit objecttype is toegevoegd om de hiërarchische structuur van het wegennetwerk te ondersteunen. |
| [Strookknoop](#informatiemodel_imibro_conceptueel_domein_wegennetwerk_objecttype_strookknoop) | Dit objecttype is toegevoegd om de hiërarchische structuur van het wegennetwerk te ondersteunen. |

## Wijzigingen aan Overige constructies {#wijzigingen-overige-constructies}

### Wijziging aan bestaande objecttypen {#wijzigingen-overige-constructies-objecttypen}
| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Afvalcontainer](https://docs.geostandaarden.nl/disgeo/emso/#afvalcontainer) | Attribuutsoort `geometrie` krijgt datatype `GM_Point` (punt) | Vlak is hier niet van toepassing. |
| [Installatie](https://docs.geostandaarden.nl/disgeo/emso/#installatie) | Van de domeinwaarde `Kast`, behorende bij attribuutsoort `Type installatie`, is specifieker vastgelegd, dat de attribuutsoort `geometrie` het datatype `GM_Point` (punt) heeft. | Lijn of vlak zijn hier niet van toepassing. |
| [Installatie](https://docs.geostandaarden.nl/disgeo/emso/#installatie) | Van de domeinwaarde `Sirene`, behorende bij attribuutsoort `Type installatie`, is specifieker vastgelegd, dat de attribuutsoort `geometrie` het datatype `GM_Point` (punt) heeft. | Lijn of vlak zijn hier niet van toepassing. |
| [Installatie](https://docs.geostandaarden.nl/disgeo/emso/#installatie) | Van de domeinwaarde `Verlichtingsarmatuur`, behorende bij attribuutsoort `Type installatie`, is specifieker vastgelegd, dat de attribuutsoort `geometrie` het datatype `GM_Point` (punt) heeft. | Lijn of vlak zijn hier niet van toepassing. |
| [Installatie](https://docs.geostandaarden.nl/disgeo/emso/#installatie) | Van de domeinwaarde `Windturbine`, behorende bij attribuutsoort `Type installatie`, is specifieker vastgelegd, dat de attribuutsoort `geometrie` het datatype `GM_Point` (punt) heeft. |
| [Installatie](https://docs.geostandaarden.nl/disgeo/emso/#installatie) | Van de domeinwaarde `Lift`, behorende bij attribuutsoort `Type installatie`, is specifieker vastgelegd, dat de attribuutsoort `geometrie` het datatype `GM_Surface` (vlak) heeft. | Punt of lijn zijn hier niet van toepassing. |
| [Installatie](https://docs.geostandaarden.nl/disgeo/emso/#installatie) | Van de domeinwaarde `Oplaadpunt`, behorende bij attribuutsoort `Type installatie`, is specifieker vastgelegd, dat de attribuutsoort `geometrie` het datatype `GM_Point` (punt) heeft. |
| [Installatie](https://docs.geostandaarden.nl/disgeo/emso/#installatie) | Van de domeinwaarde `Pomp`, behorende bij attribuutsoort `Type installatie`, is specifieker vastgelegd, dat de attribuutsoort `geometrie` het datatype `GM_Point` (punt) heeft. |
| [Installatie](https://docs.geostandaarden.nl/disgeo/emso/#installatie) | Van de domeinwaarde `Zonnepanelen`, behorende bij attribuutsoort `Type installatie`, is specifieker vastgelegd, dat de attribuutsoort `geometrie` het datatype `GM_Surface` (vlak) heeft. | Punt of lijn zijn hier niet van toepassing. |

### Nieuwe objecttypen {#wijzigingen-overige-constructies-objecttypen-nieuw}

| Objecttype | Reden |
| ---------- | ------------- |
| [Hoogspanningsmast](#informatiemodel_imibro_conceptueel_domein_overige_constructies_objecttype_hoogspanningsmast) | Toegevoegd als subtype van [Mast](https://docs.geostandaarden.nl/disgeo/emso/#mast) voor de aansluiting op de [[BGT12]]. |
| [Installatiemast](#informatiemodel_imibro_conceptueel_domein_overige_constructies_objecttype_installatiemast) | Toegevoegd als subtype van [Mast](https://docs.geostandaarden.nl/disgeo/emso/#mast) voor de aansluiting op de [[BGT12]]. |

## Wijzigingen in Functionele zoneringen {#wijzigingen-functionele-zoneringen}

Het concept functionele zone(ring) is vervangen door functionele ruimte, omdat er geen duidelijk verschil was met het concept functionele ruimte uit [[NEN3610-2022]].

### Wijziging aan bestaande objecttypen {#wijzigingen-functionele-zoneringen-objecttypen}

| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Reducering](https://docs.geostandaarden.nl/disgeo/emso/#reducering) | De naam van domeinwaarde `Fijnstof`, behorende bij attribuutsoort `Type reducering`, is gewijzigd naar `Fijnstofreducering`. | Consistentere naamgeving van subtyperingen. |
| [Reducering](https://docs.geostandaarden.nl/disgeo/emso/#reducering) | De naam van domeinwaarde `Geluid`, behorende bij attribuutsoort `Type reducering`, is gewijzigd naar `Geluidreducering`. | Consistentere naamgeving van subtyperingen. |
| [Begraafplaats](https://docs.geostandaarden.nl/disgeo/emso/#begraafplaats) | `Begraafplaats` is een subtype van [Complex](https://docs.geostandaarden.nl/disgeo/emso/#complex) geworden. | Dit sluit aan op [[IMBOR]]. |
| [Schoolterrein](https://docs.geostandaarden.nl/disgeo/emso/#schoolterrein) | `Schoolterrein` is een subtype van [Complex](https://docs.geostandaarden.nl/disgeo/emso/#complex) geworden. | Dit sluit aan op [[IMBOR]]. |


## Wijzigingen aan Registratieve ruimten {#wijzigingen-registratieve-ruimten}

### Wijziging aan bestaande objecttypen {#wijzigingen-registratieve-ruimten-objecttypen}

| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Benoemde plaats](https://docs.geostandaarden.nl/disgeo/emso/#benoemde-plaats) | De naam van het attribuutsoort `type`, is gewijzigd naar `type te plaatsen object`. | De domeinwaarden voor deze eigenschap zijn geen typeringen van benoemde plaats, maar typeringen van de te plaatsen objecten op die plaats. |


## Wijzigingen aan Geografische ruimten {#wijzigingen-geografische-ruimten}

### Wijziging aan bestaande objecttypen {#wijzigingen-geografische-ruimten-objecttypen}
| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Reliëfzone](https://docs.geostandaarden.nl/disgeo/emso/#reliefzone) | Attribuutsoort `geometrie` krijgt datatype `GM_Surface` (vlak) | Zones zijn altijd vlakken. |
