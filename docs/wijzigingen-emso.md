# Wijzigingen ten opzichte van DiS Geo : Eisen aan model samenhangende objectenregistratie 

Dit conceptueel informatiemodel is een verdere uitwerking van het informatiemodel dat in 2021 is gepresenteerd in de publicatie "DiS Geo: Eisen aan model samenhangende objectenregistratie" [[EMSO]].

Het volgende is eeen overzicht van de belangrijkste wijzigingen ten opzichte [[EMSO]]:

## Wijzigingen in Water {#wijzigingen-water}

### Wijziging aan bestaande objecttypen {#wijzigingen-water-objecttypen}

| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Watergang](https://docs.geostandaarden.nl/disgeo/emso/#watergang) | Attribuutsoort `watervoerend` is verwijderd. | Verwijderd vanwege toevoeging objecttype [Greppel](#informatiemodel_imibro_conceptueel_domein_water_objecttype_greppel). (Zie [[[#wijzigingen-water-objecttypen-nieuw]]]) |

### Nieuwe objecttypen {#wijzigingen-water-objecttypen-nieuw}

| Objecttype | Reden |
| ---------- | ------------- |
| [Greppel](#informatiemodel_imibro_conceptueel_domein_water_objecttype_greppel) | Greppel is als apart objecttype naast [Watergang](#informatiemodel_imibro_conceptueel_domein_water_objecttype_watergang) geïntroduceerd. Dit sluit ook aan op [[IMBOR]], [[GWSWS]] en [[BGT]]. |

### Verwijderde objecttypen {#wijzigingen-water-objecttypen-verwijderd}

| Objecttype | Reden |
| ---------- | ------------- |
| [Bron](https://docs.geostandaarden.nl/disgeo/emso/#bron) | Verwijderd omdat het objecttype heel beperkt wordt opgenomen in huidige registraties. |

## Wijzigingen in Groen {#wijzigingen-groen}

### Wijzinging aan bestaande objecttypen {#wijzigingen-groen-objecttypen}

| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Houtsingel](https://docs.geostandaarden.nl/disgeo/emso/#houtsingel) | Attribuutsoort `geometrie` krijgt datatype `GM_Surface`. | Dit sluit aan op [[IMBOR]]. |
| [Struik](https://docs.geostandaarden.nl/disgeo/emso/#struiken) | Attribuutsoort `indicatieHaag` is verwijderd. | Verwijderd vanwege toevoeging objecttype [Haag](#informatiemodel_imibro_conceptueel_domein_groen_objecttype_haag). (Zie [[[#wijzigingen-groen-objecttypen-nieuw]]]) | 

### Nieuwe objecttypen {#wijzigingen-groen-objecttypen-nieuw}

| Objecttype | Reden |
| ---------- | ------------- |
| [Haag](#informatiemodel_imibro_conceptueel_domein_groen_objecttype_haag) | Haag is als apart objecttype naast Struiken geïntroduceerd. Dit sluit ook aan op [[IMBOR]] en [[BGT]]. |

### Verwijderde objecttypen {#wijzigingen-groen-objecttypen-verwijderd}

| Objecttype | Reden |
| ---------- | ------------- |
| [Bomenrij](https://docs.geostandaarden.nl/disgeo/emso/#bomenrij) | Verwijderd omdat het objecttype een aanvullende structuur is op Bomen in [[IMBOR]].      |
| [Tuunwal](https://docs.geostandaarden.nl/disgeo/emso/#tuunwal) | Verwijderd omdat het objecttype heel beperkt wordt opgenomen in huidige registraties. |

## Wijzigingen in Gebouw {#wijzigingen-gebouwen}

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

## Wijzigingen in Kunstwerk {#wijzigingen-kunstwerken}

### Wijziging aan bestaande objecttypen {#wijzigingen-kunstwerken-objecttypen}
| Objecttype | Wijziziging | Reden |
| ---------- | ---------- | ------------- |
| [Kunstwerk](https://docs.geostandaarden.nl/disgeo/emso/#kunstwerk) | Het type kunstwerk `Flyover` is ene subtype van `Viaduct` geworden. | Een flyover is een deelverzameling van viaduct. |

## Wijzigingen in Overige constructies {#wijzigingen-overige-constructies}

### Nieuwe objecttypen {#wijzigingen-overige-constructies-objecttypen-nieuw}

| Objecttype | Reden |
| ---------- | ------------- |
| [Erfconstructie](#informatiemodel_imibro_conceptueel_domein_overige_constructies_objecttype_erfconstructie) | Aansluiting op Gemeentelijk Gebouwinformatiemodel. |

## Wijzigingen in Transportuimten

Het model voor tranportuimten is hergebaseerd op het generieke INSPIRE netwerkmodel [[INSPIRE-D2.10.1]]. 
