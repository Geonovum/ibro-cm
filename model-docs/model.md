# Informatiemodel Conceptueel model IBRO
## Domein Groen
### Objecttypen

#### Begroeiing {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Begroeiing</td>
</tr>
<tr>
<th>Naam</th>
<td>Begroeiing</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Planten die op natuurlijke wijze zijn ontstaan of door mensen zijn aangeplant.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Ja</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>

</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Bos {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_bos}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Bos</td>
</tr>
<tr>
<th>Naam</th>
<td>Bos</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Begroeiing die een dusdanige aantal bomen betreft dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op de definities van bos in de BGT 1.2 en van Griend en Hakhout uit IMGeo 2.2</td>
</tr>
<tr>
<th>Toelichting</th>
<td>De definitie van Bos laat voldoende ruimte voor plaatselijke aanwezigheid van struiken.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing">Begroeiing</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_bos_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een bos</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Boom {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_boom}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Boom</td>
</tr>
<tr>
<th>Naam</th>
<td>Boom</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een overblijvende plant met verhoute stam en kroon</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven welke bomen verplicht in de registratie worden opgenomen. Ook zal dan nader worden uitgewerkt wat de exacte relatie is tussen boom, houtsingel, bomenrij en bos, hoe deze begrippen zich verhouden tot andere aan het landschap gerelateerde begrippen en op welke wijze de geometrie van deze begrippen wordt vormgegeven.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing">Begroeiing</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_boom_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een boom</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Houtsingel {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_houtsingel}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Houtsingel</td>
</tr>
<tr>
<th>Naam</th>
<td>Houtsingel</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Opgaande rijvormige begroeiing van bomen (enkelvoudige/meervoudige stammen) mét ondergroei van struiken</td>
</tr>
<tr>
<th>Toelichting</th>
<td> In een later stadium zullen registratieregels worden opgesteld waarin nader wordt uitgewerkt wat de exacte relatie is tussen boom, houtsingel, bomenrij en bos, hoe deze begrippen zich verhouden tot andere aan het landschap gerelateerde begrippen en op welke wijze de geometrie van deze begrippen wordt vormgegeven.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing">Begroeiing</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_houtsingel_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een Houtsingel</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### FruitOfKweekbomen {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_fruit_of_kweekbomen}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#FruitOfKweekbomen</td>
</tr>
<tr>
<th>Naam</th>
<td>FruitOfKweekbomen</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Begroeiing die het kweken van meerjarige siergewassen en bomen betreft ten behoeve van een later gebruik elders of voor het kweken van fruit</td>
</tr>
<tr>
<th>Toelichting</th>
<td>De hier bedoelde kwekerijen onderscheiden zich van kwekerijen van potplanten door de langdurige stand/teelt van gewassen</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing">Begroeiing</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_fruit_of_kweekbomen_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Struiken {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_struiken}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Struiken</td>
</tr>
<tr>
<th>Naam</th>
<td>Struiken</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Begroeiing van bodembedekkers en/of houtachtige en/of meerstammige overblijvende planten</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Dit omvat alle begroeiing die niet valt onder de overige reële objecten onder Begroeiing</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing">Begroeiing</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_struiken_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van struiken</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### GrasEnKruidachtigen {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_gras_en_kruidachtigen}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#GrasEnKruidachtigen</td>
</tr>
<tr>
<th>Naam</th>
<td>GrasEnKruidachtigen</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Begroeiing die een laagblijvende, aaneengesloten gras- en/of kruidachtige vegetatie betreft</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>IMBOR</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Onderscheid in gras voor agrarisch gebruik, dan wel voor natuurlijk gebruik of &#39;overig&#39; gebruik wordt niet gemaakt in dit informatiemodel. In een sectormodel kan onderscheid gemaakt worden op basis van sector specifieke kenmerken. De combinatie van reëel object Gras- en kruidachtigen en functioneel object Park of Sportterrein en/of sectorregistraties (bv IMNA, gewaspercelen, IMBOR) kan voorzien in informatiebehoefte aan specifieke grastypen zoals &#39;gazon&#39;, agrarisch/natuurlijk gras&#39; of &#39;sportveld&#39;.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing">Begroeiing</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_gras_en_kruidachtigen_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van veld met gras- en kruidachtigen</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Akkerland {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_akkerland}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Akkerland</td>
</tr>
<tr>
<th>Naam</th>
<td>Akkerland</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Terrein in gebruik als akker, met gewassen die in een teelt-roulatieschema zijn opgenomen</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Kan tijdelijk zonder gewas zijn of braak liggen</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing">Begroeiing</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_akkerland_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een terrein akkerland</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Moeras {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_moeras}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Moeras</td>
</tr>
<tr>
<th>Naam</th>
<td>Moeras</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Terrein met moerasvegetatie in stilstaand water van geringe diepte zonder merkbare toe- of afvloeiing.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het reëel object Moeras is opgenomen om de specifieke combinatie van water en kenmerkende moerasbegroeiing weer te geven ten behoeve van navigatie en toegankelijkheid. Deze gebieden kenmerken zich door een heel eigen verschijningsvorm, waarbinnen de begroeiing plaatselijk en tijdelijk kan veranderen, maar waar onderhoud gericht is op behoud van de typische verschijningsvorm van moerasland.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing">Begroeiing</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_moeras_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een moeras</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Rietland {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_rietland}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Rietland</td>
</tr>
<tr>
<th>Naam</th>
<td>Rietland</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Terrein overwegend begroeid met rietvegetatie</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het reëel object Rietland is opgenomen om de specifieke combinatie van water en kenmerkende begroeiing weer te geven ten behoeve van navigatie en toegankelijkheid. Deze gebieden kenmerken zich door een heel eigen verschijningsvorm, waarbinnen de begroeiing plaatselijk en tijdelijk kan veranderen, maar waar onderhoud gericht is op behoud van de typische verschijningsvorm van rietland.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing">Begroeiing</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_rietland_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een rietland</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Heide {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_heide}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Heide</td>
</tr>
<tr>
<th>Naam</th>
<td>Heide</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Terrein begroeid met heide en heideachtige vegetaties</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het reëel object Heide is opgenomen om de kenmerkende begroeiing weer te geven ten behoeve van navigatie en toegankelijkheid. Deze gebieden kenmerken zich door een heel eigen verschijningsvorm, waarbinnen de begroeiing plaatselijk en tijdelijk kan veranderen, maar waar onderhoud gericht is op behoud van de typische verschijningsvorm van heide.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing">Begroeiing</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_heide_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een heide</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### OnbegroeideGrond {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_onbegroeide_grond}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#OnbegroeideGrond</td>
</tr>
<tr>
<th>Naam</th>
<td>OnbegroeideGrond</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Oppervlakte die niet bedekt is met enige vorm van begroeiing, water, verharding, gebouwen of andere constructies</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Onbegroeide grond is bewust niet bedekt</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_onbegroeide_grond_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van onbegroeide grond</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Recreatiezone {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_recreatiezone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Recreatiezone</td>
</tr>
<tr>
<th>Naam</th>
<td>Recreatiezone</td>
</tr>
<tr>
<th>Definitie</th>
<td>Functionele ruimte die in gebruik is voor openlucht recreatie.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>IMGeo 2.2</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_zone">FunctioneleZone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_recreatiezone_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een recreatiezone.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_recreatiezone_attribuutsoort_naam">naam</a>
</td>
<td>
Breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_recreatiezone_attribuutsoort_type">type</a>
</td>
<td>
Categorisering van de verschillende soorten zones.</td>
<td>

</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Begraafplaats {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begraafplaats}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Begraafplaats</td>
</tr>
<tr>
<th>Naam</th>
<td>Begraafplaats</td>
</tr>
<tr>
<th>Definitie</th>
<td>Besloten gebied waar lichamen van overleden personen worden begraven. Ook worden op begraafplaatsen urnen met as van gecremeerde lichamen bewaard.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>IMGeo 2.2</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het betreft hier deels de bestaande populatie begraafplaats zoals deze is opgenomen in de basisregistratie grootschalige topografie.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_complex">Complex</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Haag {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_haag}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Haag</td>
</tr>
<tr>
<th>Naam</th>
<td>Haag</td>
</tr>
<tr>
<th>Definitie</th>
<td>TODO IMBOR definitie</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_begroeiing">Begroeiing</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_haag_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Schoolterrein {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_schoolterrein}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Schoolterrein</td>
</tr>
<tr>
<th>Naam</th>
<td>Schoolterrein</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_complex">Complex</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### GemengdBos {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_gemengd_bos}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#GemengdBos</td>
</tr>
<tr>
<th>Naam</th>
<td>GemengdBos</td>
</tr>
<tr>
<th>Alias</th>
<td>Gemengd bos</td>
</tr>
<tr>
<th>Definitie</th>
<td>Terrein begroeid met een dusdanig aantal naald- en loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_bos">Bos</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### GriendEnHakhout {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_griend_en_hakhout}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#GriendEnHakhout</td>
</tr>
<tr>
<th>Naam</th>
<td>GriendEnHakhout</td>
</tr>
<tr>
<th>Alias</th>
<td>Griend en hakhout</td>
</tr>
<tr>
<th>Definitie</th>
<td>Terrein begroeid met loofbomen, in een dicht groeiverband die periodiek wordt ingekort.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_bos">Bos</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Loofbos {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_loofbos}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Loofbos</td>
</tr>
<tr>
<th>Naam</th>
<td>Loofbos</td>
</tr>
<tr>
<th>Definitie</th>
<td>Terrein begroeid met een dusdanige aantal loofbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_bos">Bos</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Naaldbos {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_naaldbos}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Naaldbos</td>
</tr>
<tr>
<th>Naam</th>
<td>Naaldbos</td>
</tr>
<tr>
<th>Definitie</th>
<td>Terrein begroeid met een dusdanige aantal naaldbomen dat deze een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_bos">Bos</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Boomkwekerij {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_boomkwekerij}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Boomkwekerij</td>
</tr>
<tr>
<th>Naam</th>
<td>Boomkwekerij</td>
</tr>
<tr>
<th>Definitie</th>
<td>Terrein, overwegend in gebruik t.b.v. het opkweken van bomen (inclusief coniferen en sparren) en struiken, waarbij de hoogte van de aanplant niet van belang is.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_fruit_of_kweekbomen">FruitOfKweekbomen</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### FruitkwekerijMetLageOpstand {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_fruitkwekerij_met_lage_opstand}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#FruitkwekerijMetLageOpstand</td>
</tr>
<tr>
<th>Naam</th>
<td>FruitkwekerijMetLageOpstand</td>
</tr>
<tr>
<th>Alias</th>
<td>Fruitkwekerij met lage opstand</td>
</tr>
<tr>
<th>Definitie</th>
<td>Terrein begroeid met laagstamfruitbomen, druivenstokken of begroeid met heesters voor zachtfruit zoals bessen of frambozen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_fruit_of_kweekbomen">FruitOfKweekbomen</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### HoogstamBoomgaarden {#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_hoogstam_boomgaarden}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#HoogstamBoomgaarden</td>
</tr>
<tr>
<th>Naam</th>
<td>HoogstamBoomgaarden</td>
</tr>
<tr>
<th>Alias</th>
<td>Hoogstam boomgaarden</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Terrein begroeid met hoogstamfruitbomen.</td>
</tr>
<tr>
<th>Toelichting</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_fruit_of_kweekbomen">FruitOfKweekbomen</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>












## Domein Water
### Objecttypen

#### Watervlakte {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watervlakte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Watervlakte</td>
</tr>
<tr>
<th>Naam</th>
<td>Watervlakte</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een niet langgerekte verlaging in het aardoppervlak van natuurlijke of kunstmatige oorsprong, die permanent of periodiek water bevat.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>gebaseerd op Aquo-standaard</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het betreft hier enkel het aanwezige water bij het voorgeschreven waterpeil. Het bij dit waterpeil droog liggende gedeelte van de oever valt niet binnen de afbakening van dit object.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watervlakte_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een watervlakte.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watervlakte_attribuutsoort_indicatie_primair">indicatiePrimair</a>
</td>
<td>
Deze watervlakte is al dan niet een hoofdverbinding in het watersysteem.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Boolean</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Watergang {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watergang}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Watergang</td>
</tr>
<tr>
<th>Definitie</th>
<td>Langgerekte verlaging in het aardoppervlak van natuurlijke of kunstmatige oorsprong die permanent of periodiek water bevat.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>AQUO lex</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het betreft hier enkel het aanwezige water bij het voorgeschreven waterpeil. Het bij dit waterpeil droog liggende gedeelte van de oever valt niet binnen de afbakening van dit object.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watergang_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een watergang.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watergang_attribuutsoort_indicatie_primair">indicatiePrimair</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Boolean</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Getijdengebied {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_getijdengebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Getijdengebied</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geheel of gedeeltelijk droogvallende gronden die buitendijks gelegen zijn.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_getijdengebied_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een getijdengebied.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Oeverzone {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_oeverzone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Oeverzone</td>
</tr>
<tr>
<th>Definitie</th>
<td>Gebied op de grens van water en land waar het dynamisch samenspel van land en water plaatsvindt, lopend van waterpeil tot insteek.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan oeverzone moet worden gegeven. Ook zal dan gedetailleerder worden vastgelegd welke oeverzones in de registratie worden opgenomen. Het is niet de bedoeling om alle waterkanten verplicht te voorzien van een oeverzone. Het betreft het gedeelte van de oever dat bij het voorgeschreven waterpeil droog ligt.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_zone">FunctioneleZone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_oeverzone_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_oeverzone_attribuutsoort_indicatie_natuurvriendelijke_oever">indicatieNatuurvriendelijkeOever</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Boolean</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Waterbergingsgebied {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_waterbergingsgebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Waterbergingsgebied</td>
</tr>
<tr>
<th>Definitie</th>
<td>Gebied, niet zijnde een oppervlaktewaterlichaam of onderdeel daarvan, dat dient ter verruiming van de bergingscapaciteit van een of meer watersystemen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Waterwet</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_zone">FunctioneleZone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_waterbergingsgebied_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### GebruikszoneOppervlaktewater {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_gebruikszone_oppervlaktewater}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>GebruikszoneOppervlaktewater</td>
</tr>
<tr>
<th>Definitie</th>
<td>Begrensd oppervlaktewatergebied dat een bepaald gebruik kent.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_zone">FunctioneleZone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_gebruikszone_oppervlaktewater_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_gebruikszone_oppervlaktewater_attribuutsoort_type">type</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_codelijst_type_gebruikszone_oppervlaktewater">TypeGebruikszoneOppervlaktewater</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Greppel {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_greppel}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Greppel</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_greppel_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Meer {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_meer}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Meer</td>
</tr>
<tr>
<th>Naam</th>
<td>Meer</td>
</tr>
<tr>
<th>Definitie</th>
<td>Watervlakte (meestal zoet) die op natuurlijke wijze dan wel door menselijk ingrijpen (ingraving of afsluiting) is ontstaan.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watervlakte">Watervlakte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Plas {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_plas}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Plas</td>
</tr>
<tr>
<th>Naam</th>
<td>Plas</td>
</tr>
<tr>
<th>Definitie</th>
<td>Waterpartij, ontstaan door de winning van delfstoffen in dagbouw, die in contact staat met de vrije grondwaterspiegel.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watervlakte">Watervlakte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Ven {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_ven}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Ven</td>
</tr>
<tr>
<th>Naam</th>
<td>Ven</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Natuurlijk ontstaan meer op zandgrond.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watervlakte">Watervlakte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Vijver {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_vijver}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Vijver</td>
</tr>
<tr>
<th>Naam</th>
<td>Vijver</td>
</tr>
<tr>
<th>Definitie</th>
<td>Gegraven waterpartij, aangelegd in stedelijke omgeving of in een parklandschap.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watervlakte">Watervlakte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Zee {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_zee}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Zee</td>
</tr>
<tr>
<th>Naam</th>
<td>Zee</td>
</tr>
<tr>
<th>Definitie</th>
<td>Uitgestrekt oppervlak zout water.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watervlakte">Watervlakte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Beek {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_beek}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Beek</td>
</tr>
<tr>
<th>Naam</th>
<td>Beek</td>
</tr>
<tr>
<th>Definitie</th>
<td>Natuurlijke smalle watergang zonder getij, die veelal doorwaadbaar is en afwatert op een rivier.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watergang">Watergang</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Gracht {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_gracht}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Gracht</td>
</tr>
<tr>
<th>Naam</th>
<td>Gracht</td>
</tr>
<tr>
<th>Definitie</th>
<td>Gegraven watergang die hoofdzakelijk voorkomt in oude steden.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watergang">Watergang</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Kanaal {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_kanaal}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Kanaal</td>
</tr>
<tr>
<th>Naam</th>
<td>Kanaal</td>
</tr>
<tr>
<th>Definitie</th>
<td>Gegraven grote watergang die dient voor scheepvaart en/of watertransport.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watergang">Watergang</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Rivier {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_rivier}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Rivier</td>
</tr>
<tr>
<th>Naam</th>
<td>Rivier</td>
</tr>
<tr>
<th>Definitie</th>
<td>Water dat door atmosferische neerslag op hellende terreinen valt, vloeit, voor zover het niet verdampt of door planten wordt opgenomen, tezamen tot een watergang en stroomt naar laaggelegen streken.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watergang">Watergang</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Sloot {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_sloot}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Sloot</td>
</tr>
<tr>
<th>Naam</th>
<td>Sloot</td>
</tr>
<tr>
<th>Definitie</th>
<td>Watergang van beperkte breedte die stilstaand of langzaam stromend water bevat, en die is aangelegd met als doel het beheersen van het waterpeil.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_watergang">Watergang</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Schor {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_schor}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Schor</td>
</tr>
<tr>
<th>Naam</th>
<td>Schor</td>
</tr>
<tr>
<th>Definitie</th>
<td>Buitendijks aangeslibd land, dat bij gewone vloed niet meer onderloopt en doorgaans begroeid is.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_getijdengebied">Getijdengebied</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Slik {#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_slik}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Slik</td>
</tr>
<tr>
<th>Naam</th>
<td>Slik</td>
</tr>
<tr>
<th>Definitie</th>
<td>Buitendijks aangeslibde, onbegroeide grond die bij vrijwel elk hoogwater onderloopt.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_water_objecttype_getijdengebied">Getijdengebied</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>











### Codelijsten

#### TypeWatervlakte {#informatiemodel_conceptueel_model_ibro_domein_water_codelijst_type_watervlakte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeWatervlakte</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeWatergang {#informatiemodel_conceptueel_model_ibro_domein_water_codelijst_type_watergang}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeWatergang</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeGetijdengebied {#informatiemodel_conceptueel_model_ibro_domein_water_codelijst_type_getijdengebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeGetijdengebied</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeGebruikszoneOppervlaktewater {#informatiemodel_conceptueel_model_ibro_domein_water_codelijst_type_gebruikszone_oppervlaktewater}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeGebruikszoneOppervlaktewater</td>
</tr>
<tbody>
</tbody>
</table>



## Domein Algemeen
### Objecttypen

#### ReeelObject {#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#ReeelObject</td>
</tr>
<tr>
<th>Naam</th>
<td>ReeelObject</td>
</tr>
<tr>
<th>Alias</th>
<td>Reëel object</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geo-object dat zich geheel materieel manifesteert.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>

</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_object">Object</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object_attribuutsoort_status">status</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_codelijst_status_reeel_object">StatusReëelObject</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### FunctioneleRuimte {#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>FunctioneleRuimte</td>
</tr>
<tr>
<th>Definitie</th>
<td>Ruimte met een specifieke functie.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>

</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_object">Object</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_ruimte_attribuutsoort_status">status</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_codelijst_status_functionele_ruimte">StatusFunctioneleRuimte</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Complex {#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_complex}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Complex</td>
</tr>
<tr>
<th>Definitie</th>
<td>Functionele ruimte die een verzameling van één of meer gebouwen, constructies, verharding, water en begroeiing betreft die samen een eenheid vormen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_zone">FunctioneleZone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_complex_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een complex.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_complex_attribuutsoort_type">type</a>
</td>
<td>
Categorisering van de verschillende complexen.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_codelijst_type_complex">TypeComplex</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_complex_attribuutsoort_naam">naam</a>
</td>
<td>
Breed geaccepteerde benaming van een complex zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>



#### FunctioneleZone {#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_zone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>FunctioneleZone</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_ruimte">FunctioneleRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### GeografischeRuimte {#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_geografische_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>GeografischeRuimte</td>
</tr>
<tr>
<th>Definitie</th>
<td>Ruimte die bekendstaat onder een vanuit de historie of het gebruik bekende benaming of een fysisch-geografische samenhang, al dan niet met zijn omgeving, kent.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>

</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_geografische_ruimte_attribuutsoort_status">status</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_codelijst_status_geografische_ruimte">StatusGeografischeRuimte</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Object {#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_object}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Object</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>

</td>
</tr>
<tbody>
</tbody>
</table>
</section>



<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_object_relatiesoort_heeft">heeft</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerkverwijzing">Netwerkverwijzing</a>
</td>
<td>
0..*</td>
</tr>
</tbody>
</table>
</section>



### Keuzen tussen datatypen

#### LijnOfVlak {#informatiemodel_conceptueel_model_ibro_domein_algemeen_keuze_datatype__lijn_of_vlak}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>LijnOfVlak</td>
</tr>
<tbody>
</tbody>
</table>


<section class="notoc">
<h5>Overzicht datatypekeuzen</h5>
<table style="width: 100%">
<colgroup style="width: 50%"></colgroup>
<tbody>
<tr>
  <th>Datatype</th>
</tr>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Curve"> GM_Curve</a>
</td>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
</tbody>
</table>
</section>

#### VlakOfMultivlak {#informatiemodel_conceptueel_model_ibro_domein_algemeen_keuze_datatype__vlak_of_multivlak}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>VlakOfMultivlak</td>
</tr>
<tbody>
</tbody>
</table>


<section class="notoc">
<h5>Overzicht datatypekeuzen</h5>
<table style="width: 100%">
<colgroup style="width: 50%"></colgroup>
<tbody>
<tr>
  <th>Datatype</th>
</tr>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_MultiSurface"> GM_MultiSurface</a>
</td>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
</tbody>
</table>
</section>

#### PuntLijnOfVlak {#informatiemodel_conceptueel_model_ibro_domein_algemeen_keuze_datatype__punt_lijn_of_vlak}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>PuntLijnOfVlak</td>
</tr>
<tbody>
</tbody>
</table>


<section class="notoc">
<h5>Overzicht datatypekeuzen</h5>
<table style="width: 100%">
<colgroup style="width: 50%"></colgroup>
<tbody>
<tr>
  <th>Datatype</th>
</tr>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
</tbody>
</table>
</section>

#### PuntMultipuntLijnVlakOfMultivlak {#informatiemodel_conceptueel_model_ibro_domein_algemeen_keuze_datatype__punt_multipunt_lijn_vlak_of_multivlak}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>PuntMultipuntLijnVlakOfMultivlak</td>
</tr>
<tbody>
</tbody>
</table>


<section class="notoc">
<h5>Overzicht datatypekeuzen</h5>
<table style="width: 100%">
<colgroup style="width: 50%"></colgroup>
<tbody>
<tr>
  <th>Datatype</th>
</tr>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_MultiPoint"> GM_MultiPoint</a>
</td>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_MultiSurface"> GM_MultiSurface</a>
</td>
</tbody>
</table>
</section>






### Codelijsten

#### StatusReëelObject {#informatiemodel_conceptueel_model_ibro_domein_algemeen_codelijst_status_reeel_object}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>StatusReëelObject</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Fase van ontwikkeling waarin een reël object zich bevindt.</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Deze codelijst gaat verwijzen naar de collectie met reële levensfasen zodra deze gepubliceerd is. De collectie komt inhoudelijk overeen met https://staging-definities.geostandaarden.nl/sor/nl/page/levensfasen_reele_objecten</td>
</tr>
<tbody>
</tbody>
</table>


#### StatusFunctioneleRuimte {#informatiemodel_conceptueel_model_ibro_domein_algemeen_codelijst_status_functionele_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>StatusFunctioneleRuimte</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeComplex {#informatiemodel_conceptueel_model_ibro_domein_algemeen_codelijst_type_complex}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeComplex</td>
</tr>
<tbody>
</tbody>
</table>


#### StatusGeografischeRuimte {#informatiemodel_conceptueel_model_ibro_domein_algemeen_codelijst_status_geografische_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>StatusGeografischeRuimte</td>
</tr>
<tbody>
</tbody>
</table>



## Domein Registratieve ruimten
### Objecttypen

#### RegistratieveRuimte {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_registratieve_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>RegistratieveRuimte</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>

</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_registratieve_ruimte_attribuutsoort_status">status</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_enumeratie_status_registratieve_ruimte">StatusRegistratieveRuimte</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### BestuurlijkGebied {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>BestuurlijkGebied</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_registratieve_ruimte">RegistratieveRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een gebied op land dat door een openbaar lichaam wordt bestuurd.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_keuze_datatype__vlak_of_multivlak">VlakOfMultivlak</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_attribuutsoort_type">type</a>
</td>
<td>
Categorie waartoe het betreffende bestuurlijke gebied behoort.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_enumeratie_type_bestuurlijk_gebied">TypeBestuurlijkGebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_relatiesoort_wordt_bestuurd_door">wordtBestuurdDoor</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbaar_lichaam">OpenbaarLichaam</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_relatiesoort_ligt_in_bestuurlijk_gebied">ligtInBestuurlijkGebied</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
</td>
<td>
0..*</td>
</tr>
</tbody>
</table>
</section>

#### OpenbaarLichaam {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbaar_lichaam}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>OpenbaarLichaam</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een openbaar lichaam is, in de bestuurlijke indeling van het Koninkrijk der Nederlanden, een overheidsorganisatie met publiekrechtelijke rechtspersoonlijkheid, die bepaalde taken uitvoert binnen een bepaald ruimtelijk gebied of op een bepaald inhoudelijk gebied.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_overheidsorganisatie">Overheidsorganisatie</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbaar_lichaam_attribuutsoort_type">type</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_enumeratie_type_openbaar_lichaam">TypeOpenbaarLichaam</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbaar_lichaam_relatiesoort_bestuurt_gebied">bestuurtGebied</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
</td>
<td>
0..*</td>
</tr>
</tbody>
</table>
</section>

#### Overheidsorganisatie {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_overheidsorganisatie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Overheidsorganisatie</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>


<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_overheidsorganisatie_attribuutsoort_officiele_naam_incl_soort">officieleNaamInclSoort</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_overheidsorganisatie_attribuutsoort_organisatiecode">organisatiecode</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### BestuurlijkGebiedOpLand {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_op_land}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>BestuurlijkGebiedOpLand</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### BestuurlijkGebiedOpZee {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_op_zee}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>BestuurlijkGebiedOpZee</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Waterschap {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_waterschap}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Waterschap</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbaar_lichaam">OpenbaarLichaam</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>



<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_waterschap_relatiesoort_bestuurt_waterschapsgebied">bestuurtWaterschapsgebied</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_waterschapsgebied">Waterschapsgebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Veiligheidsregio {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_veiligheidsregio}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Veiligheidsregio</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbaar_lichaam">OpenbaarLichaam</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>



<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_veiligheidsregio_relatiesoort_bestuurt_veiligheidsregiogebied">bestuurtVeiligheidsregiogebied</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_veiligheidsregiogebied">Veiligheidsregiogebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Gemeente {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_gemeente}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Gemeente</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbaar_lichaam">OpenbaarLichaam</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>



<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_gemeente_relatiesoort_bestuurt_gemeentegebied">bestuurtGemeentegebied</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_gemeentegebied">Gemeentegebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Rijk {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_rijk}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Rijk</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbaar_lichaam">OpenbaarLichaam</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>



<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_rijk_relatiesoort_bestuurt_rijksgebied">bestuurtRijksgebied</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_rijksgebied">Rijksgebied</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_rijk_relatiesoort_bestuurt_territoriale_zee">bestuurtTerritorialeZee</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_territoriale_zee">TerritorialeZee</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_rijk_relatiesoort_bestuurt_aansluitende_zone">bestuurtAansluitendeZone</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_aansluitende_zone">AansluitendeZone</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_rijk_relatiesoort_bestuurt_exclusieve_economische_zone">bestuurtExclusieveEconomischeZone</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_exclusieve_economische_zone">ExclusieveEconomischeZone</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_rijk_relatiesoort_bestuurt_continentaal_plat">bestuurtContinentaalPlat</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_continentaal_plat">ContinentaalPlat</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Waterschapsgebied {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_waterschapsgebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Waterschapsgebied</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_op_land">BestuurlijkGebiedOpLand</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Veiligheidsregiogebied {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_veiligheidsregiogebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Veiligheidsregiogebied</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_op_land">BestuurlijkGebiedOpLand</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Gemeentegebied {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_gemeentegebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Gemeentegebied</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_op_land">BestuurlijkGebiedOpLand</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>



<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_gemeentegebied_relatiesoort_ligt_in_veiligheidsregiogebied">ligtInVeiligheidsregiogebied</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_veiligheidsregiogebied">Veiligheidsregiogebied</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_gemeentegebied_relatiesoort_ligt_in_provinciegebied">ligtInProvinciegebied</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_provinciegebied">Provinciegebied</a>
</td>
<td>
</td>
</tr>
</tbody>
</table>
</section>

#### Provincie {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_provincie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Provincie</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbaar_lichaam">OpenbaarLichaam</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>



<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_provincie_relatiesoort_bestuurt_provinciegebied">bestuurtProvinciegebied</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_provinciegebied">Provinciegebied</a>
</td>
<td>
</td>
</tr>
</tbody>
</table>
</section>

#### Provinciegebied {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_provinciegebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Provinciegebied</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_op_land">BestuurlijkGebiedOpLand</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>



<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_provinciegebied_relatiesoort_ligt_in_rijksgebied">ligtInRijksgebied</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_rijksgebied">Rijksgebied</a>
</td>
<td>
</td>
</tr>
</tbody>
</table>
</section>

#### Rijksgebied {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_rijksgebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Rijksgebied</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_op_land">BestuurlijkGebiedOpLand</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### TerritorialeZee {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_territoriale_zee}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TerritorialeZee</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_op_zee">BestuurlijkGebiedOpZee</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### AansluitendeZone {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_aansluitende_zone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>AansluitendeZone</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_op_zee">BestuurlijkGebiedOpZee</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### ExclusieveEconomischeZone {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_exclusieve_economische_zone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>ExclusieveEconomischeZone</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_op_zee">BestuurlijkGebiedOpZee</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### ContinentaalPlat {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_continentaal_plat}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>ContinentaalPlat</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_bestuurlijk_gebied_op_zee">BestuurlijkGebiedOpZee</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Woonplaats {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_woonplaats}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Woonplaats</td>
</tr>
<tr>
<th>Definitie</th>
<td>Door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorzien gedeelte van het grondgebied van de gemeente.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Artikel 1 Wet basisregistratie adressen en gebouwen</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Een woonplaats valt altijd volledig binnen een gemeente. De geometrie van alle woonplaatsen moeten het Europese deel van het grondgebied van Nederland op land volledig bedekken. Woonplaatsen mogen niet overlappen.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_registratieve_ruimte">RegistratieveRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_woonplaats_attribuutsoort_formele_naam">formeleNaam</a>
</td>
<td>
Benaming van een door het gemeentebestuur aangewezen woonplaats.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_woonplaats_attribuutsoort_alternatieve_naam">alternatieveNaam</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_woonplaats_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_keuze_datatype__vlak_of_multivlak">VlakOfMultivlak</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_woonplaats_relatiesoort_ligt_in">ligtIn</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_gemeentegebied">Gemeentegebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Wijk {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_wijk}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Wijk</td>
</tr>
<tr>
<th>Definitie</th>
<td>Aaneengesloten gedeelte van het grondgebied van een gemeente, waarvan de grenzen zo veel mogelijk zijn gebaseerd op sociaalgeografische kenmerken.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>GFO Basisgegevens</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Een wijk valt altijd volledig binnen een gemeente. De geometrie van alle wijken moeten het Europese deel van het grondgebied van Nederland op land volledig bedekken. Wijken mogen niet overlappen.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_registratieve_ruimte">RegistratieveRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_wijk_attribuutsoort_wijkcode">wijkcode</a>
</td>
<td>
Codering van een wijk zoals deze door het CBS wordt gebruikt.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_wijk_attribuutsoort_wijknaam">wijknaam</a>
</td>
<td>
Naam die aan een wijk is toegekend in een daartoe strekkend formeel gemeentelijk besluit.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_wijk_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een wijk.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_keuze_datatype__vlak_of_multivlak">VlakOfMultivlak</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_wijk_relatiesoort_ligt_in">ligtIn</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_gemeentegebied">Gemeentegebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Buurt {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_buurt}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Buurt</td>
</tr>
<tr>
<th>Definitie</th>
<td>Aaneengesloten gedeelte van een wijk, waarvan de grenzen zo veel mogelijk gebaseerd zijn op topografische elementen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>GFO Basisgegevens</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Een buurt valt altijd volledig binnen een wijk. De geometrie van alle buurten moeten het Europese deel van het grondgebied van Nederland op land volledig bedekken. Buurten mogen niet overlappen.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_registratieve_ruimte">RegistratieveRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_buurt_attribuutsoort_buurtcode">buurtcode</a>
</td>
<td>
Codering van een buurt zoals deze door het CBS wordt gebruikt.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_buurt_attribuutsoort_buurtnaam">buurtnaam</a>
</td>
<td>
Naam die aan een buurt is toegekend in een daartoe strekkend formeel gemeentelijk besluit.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_buurt_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_keuze_datatype__vlak_of_multivlak">VlakOfMultivlak</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_buurt_relatiesoort_ligt_in">ligtIn</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_wijk">Wijk</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### OpenbareRuimte {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbare_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>OpenbareRuimte</td>
</tr>
<tr>
<th>Definitie</th>
<td>Door het bevoegde gemeentelijke orgaan als zodanig aangewezen en van een naam voorziene buitenruimte die binnen één woonplaats is gelegen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Artikel 1 Wet basisregistratie adressen en gebouwen</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Openbare ruimten worden uitsluitend gekoppeld aan wegverbindingen en waterverbindingen door het bij deze verbindingen opnemen van een verwijzing naar de identificatiecode van de openbare ruimte waarbinnen deze verbinding is gelegen. De naamgeving van de andere objecttypen die momenteel nog van een formele openbare ruimte naam kunnen worden voorzien, wordt geregistreerd door het op vrijwillige basis bij deze objecttypen opnemen van een eigenschap “naam”. Het gaat daarbij om spoorverbindingen, kunstwerken, geografische gebieden en functionele gebieden. Door deze wijze van koppeling aan wegverbindingen en waterverbindingen worden openbare ruimten ook geometrisch vindbaar. Naam van een openbare ruimte wordt in de dagelijkse praktijk vaak straatnaam genoemd.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_registratieve_ruimte">RegistratieveRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbare_ruimte_attribuutsoort_type">type</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_codelijst_type_openbare_ruimte">TypeOpenbareRuimte</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbare_ruimte_attribuutsoort_formele_naam">formeleNaam</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbare_ruimte_attribuutsoort_alternatieve_naam">alternatieveNaam</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbare_ruimte_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbare_ruimte_relatiesoort_ligt_in">ligtIn</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_woonplaats">Woonplaats</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Nummeraanduiding {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_nummeraanduiding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Nummeraanduiding</td>
</tr>
<tr>
<th>Definitie</th>
<td>Door het bevoegde gemeentelijke orgaan als zodanig toegekende aanduiding van een verblijfsobject of een benoemde plaats.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Artikel 1 Wet basisregistraties adressen en gebouwen, Catalogus BAG 2018</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Nummeraanduiding maakt samen met woonplaats en openbare ruimte het officiële adres. Een nummeraanduiding is gelegen aan een openbare ruimte en heeft daartoe een verwijzing naar deze gerelateerde openbare ruimte.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_registratieve_ruimte">RegistratieveRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_nummeraanduiding_attribuutsoort_huisnummer">huisnummer</a>
</td>
<td>
Een huisnummer is een door of namens het gemeentebestuur ten aanzien van een adresseerbaar object toegekende nummering.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Integer</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_nummeraanduiding_attribuutsoort_huisletter">huisletter</a>
</td>
<td>
Een huisletter is een door of namens het gemeentebestuur ten aanzien van een adresseerbaar object toegekende toevoeging aan een huisnummer in de vorm van een alfanumeriek teken.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_nummeraanduiding_attribuutsoort_huisnummertoevoeging">huisnummertoevoeging</a>
</td>
<td>
Een huisnummertoevoeging is een door of namens het gemeentebestuur ten aanzien van een adresseerbaar object toegekende nadere toevoeging aan een huisnummer of een combinatie van huisnummer en huisletter.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_nummeraanduiding_attribuutsoort_postcode">postcode</a>
</td>
<td>
De postcode is een door PostNL vastgestelde code behorende bij een bepaalde combinatie van een straatnaam en een huisnummer.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_nummeraanduiding_relatiesoort_ligt_in">ligtIn</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_woonplaats">Woonplaats</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_nummeraanduiding_relatiesoort_ligt_aan">ligtAan</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbare_ruimte">OpenbareRuimte</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### BenoemdePlaats {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_benoemde_plaats}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>BenoemdePlaats</td>
</tr>
<tr>
<th>Definitie</th>
<td>Door het bevoegde gemeentelijk orgaan als zodanig aangewezen delen van een terrein en/of water waarvan het belang is daaraan een adres toe te kennen en dat bedoeld is voor het permanent plaatsen van een niet direct en niet duurzaam met de aarde verbonden object, het permanent afmeren van een drijvend object of het permanent aanwezig zijn van publiek toegankelijke technische voorzieningen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>	Gebaseerd op artikel 1 Wet basisregistratie adressen en gebouwen</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Door het hanteren van een generiek begrip benoemde plaats in plaats van standplaats en ligplaats, wordt het mogelijk ook andere objecten onder dit begrip te laten vallen. Van deze mogelijkheid is in eerste instantie gebruik gemaakt om ook onbemenste tankstations van een adres te kunnen voorzien. Door de wijziging van Benaming wordt ook de in de uitvoeringspraktijk bestaande verwarring met vergelijkbare begrippen in het kader van onder meer de Omgevingswet tegengegaan.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_registratieve_ruimte">RegistratieveRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_benoemde_plaats_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_benoemde_plaats_attribuutsoort_type">type</a>
</td>
<td>
Aard van het object dat op de benoemde plaats is of kan worden geplaatst.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_codelijst_type_benoemde_plaats">TypeBenoemdePlaats</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_benoemde_plaats_relatiesoort_heeft">heeft</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_nummeraanduiding">Nummeraanduiding</a>
</td>
<td>
1..*</td>
</tr>
</tbody>
</table>
</section>






### Enumeraties

#### TypeBestuurlijkGebied {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_enumeratie_type_bestuurlijk_gebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeBestuurlijkGebied</td>
</tr>
<tbody>
</tbody>
</table>


<section class="notoc">
<h5>Overzicht waarden</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 75%"></colgroup>
<tbody>
<tr>
  <th>Waarde</th>
  <th>Definitie</th>
</tr>
<tr>
<td>
aansluitende zone</td>
<td>
</td>
<tr>
<td>
continentaal plat</td>
<td>
</td>
<tr>
<td>
exclusieve economische zone</td>
<td>
</td>
<tr>
<td>
gemeentegebied</td>
<td>
</td>
<tr>
<td>
provinciegebied</td>
<td>
</td>
<tr>
<td>
rijksgebied</td>
<td>
</td>
<tr>
<td>
territoriale zee</td>
<td>
</td>
<tr>
<td>
veiligheidsregiogebied</td>
<td>
</td>
<tr>
<td>
waterschapsgebied</td>
<td>
</td>
</tbody>
</table>


</section>

#### StatusRegistratieveRuimte {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_enumeratie_status_registratieve_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>StatusRegistratieveRuimte</td>
</tr>
<tbody>
</tbody>
</table>


<section class="notoc">
<h5>Overzicht waarden</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 75%"></colgroup>
<tbody>
<tr>
  <th>Waarde</th>
  <th>Definitie</th>
</tr>
<tr>
<td>
Ontwerp</td>
<td>
</td>
<tr>
<td>
Niet gerealiseerd</td>
<td>
</td>
<tr>
<td>
Vastgesteld</td>
<td>
</td>
<tr>
<td>
Ingetrokken</td>
<td>
</td>
</tbody>
</table>


</section>

#### TypeOpenbaarLichaam {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_enumeratie_type_openbaar_lichaam}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeOpenbaarLichaam</td>
</tr>
<tbody>
</tbody>
</table>


<section class="notoc">
<h5>Overzicht waarden</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 75%"></colgroup>
<tbody>
<tr>
  <th>Waarde</th>
  <th>Definitie</th>
</tr>
<tr>
<td>
gemeente</td>
<td>
</td>
<tr>
<td>
provincie</td>
<td>
</td>
<tr>
<td>
rijk</td>
<td>
</td>
<tr>
<td>
veiligheidsregio</td>
<td>
</td>
<tr>
<td>
waterschap</td>
<td>
</td>
</tbody>
</table>


</section>



### Codelijsten

#### TypeOpenbareRuimte {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_codelijst_type_openbare_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeOpenbareRuimte</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeBenoemdePlaats {#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_codelijst_type_benoemde_plaats}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeBenoemdePlaats</td>
</tr>
<tbody>
</tbody>
</table>



## Domein Wegen
### Objecttypen

#### Verharding {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_verharding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Verharding</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een door egaliseren, verstevigen en/of verruwen voor het beoogde gebruik geschikt gemaakt oppervlak, bestaande uit in een of meer lagen over een bodem of onderliggende constructie aangelegd materiaal.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Een verhardingsvlak bestaat uit één Type verharding. Het gaat hierbij over het Type verharding waarmee het vlak overwegend is bedekt.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_verharding_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_verharding_attribuutsoort_type">type</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_verharding">TypeVerharding</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_verharding_attribuutsoort_status">status</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_codelijst_status_reeel_object">StatusReëelObject</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### OnbepaaldTerrein {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_onbepaald_terrein}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>OnbepaaldTerrein</td>
</tr>
<tr>
<th>Definitie</th>
<td>Fysiek begrensd en zichtbaar terrein dat bij een gebouw hoort, dat niet verder wordt gedetailleerd in andere reële objecten en dat bestaat uit een mengvorm van verharding, water, begroeiing en/of constructies.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op definitie van erf in BGT</td>
</tr>
<tr>
<th>Toelichting</th>
<td>In plaats van onbepaald terrein kan ter plaatse ook de reële topografie worden ingewonnen (vrijwillig).</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_onbepaald_terrein_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### VerkeerskundigFunctioneleZone {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_verkeerskundig_functionele_zone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>VerkeerskundigFunctioneleZone</td>
</tr>
<tr>
<th>Definitie</th>
<td>Functionele ruimte die een verkeerskundige functie kent.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_zone">FunctioneleZone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_verkeerskundig_functionele_zone_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een verkeerskundig functionele zone.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_verkeerskundig_functionele_zone_attribuutsoort_type">type</a>
</td>
<td>
Typering van een verkeerskundig functionele zones.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_verkeerskundig_functionele_zone">TypeVerkeerskundigFunctioneleZone</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_verkeerskundig_functionele_zone_attribuutsoort_naam">naam</a>
</td>
<td>
Breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_verkeerskundig_functionele_zone_relatiesoort_hyperverbinding">hyperverbinding</a>
</td>
<td>
</td>
<td>

</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Wegzone {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegzone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Wegzone</td>
</tr>
<tr>
<th>Definitie</th>
<td>Functionele ruimte die in gebruik is voor weginrichting.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_zone">FunctioneleZone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegzone_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een wegzone.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegzone_attribuutsoort_type">type</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_wegzone">TypeWegzone</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Spoorzone {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_spoorzone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Spoorzone</td>
</tr>
<tr>
<th>Definitie</th>
<td>Functionele ruimte die in gebruik is voor spoorwegen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_zone">FunctioneleZone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_spoorzone_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_spoorzone_attribuutsoort_type_spoorzone">typeSpoorzone</a>
</td>
<td>
Typering van een spoorzone.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_spoorzone">TypeSpoorzone</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Luchtvaartzone {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_luchtvaartzone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Luchtvaartzone</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_zone">FunctioneleZone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_luchtvaartzone_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een luchtvaartzone</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_luchtvaartzone_attribuutsoort_type_luchtvaartzone">typeLuchtvaartzone</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_luchtvaartzone">TypeLuchtvaartzone</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_luchtvaartzone_attribuutsoort_naam">naam</a>
</td>
<td>
Breed geaccepteerde benaming van een zone zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>



#### Spoorwegknoop {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_spoorwegknoop}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Spoorwegknoop</td>
</tr>
<tr>
<th>Herkomst</th>
<td>Gebaseerd op conceptueel model netwerken.</td>
</tr>
<tr>
<th>Definitie</th>
<td>Spoorverkeerruimte die een begin-, eind- of keuzepunt voor de spoorgebruiker is.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>

</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportknoop">Transportknoop</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_spoorwegknoop_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Spoorverbinding {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_spoorverbinding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Spoorverbinding</td>
</tr>
<tr>
<th>Herkomst</th>
<td>Gebaseerd op conceptueel model netwerken</td>
</tr>
<tr>
<th>Definitie</th>
<td>Spoorverkeerruimte die de verkeerskundige inrichting van een spoor tussen twee knopen betreft.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>

</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportverbinding">Transportverbinding</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_spoorverbinding_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een spoorverbinding.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_spoorverbinding_attribuutsoort_type">type</a>
</td>
<td>
Aanduiding van het soort spoor.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_spoorverbinding">TypeSpoorverbinding</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Wegverbinding {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegverbinding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Wegverbinding</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegverkeerruimteverbinding">Wegverkeerruimteverbinding</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegverbinding_attribuutsoort_type">type</a>
</td>
<td>
</td>
<td>

</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegverbinding_attribuutsoort_routenummer">routenummer</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegverbinding_attribuutsoort_indicatie_openbare_weg">indicatieOpenbareWeg</a>
</td>
<td>
Deze wegverbinding is al dan niet een openbare weg.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Boolean</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegverbinding_relatiesoort_heeft">heeft</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbare_ruimte">OpenbareRuimte</a>
</td>
<td>
0..*</td>
</tr>
</tbody>
</table>
</section>

#### Baanverbinding {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_baanverbinding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Baanverbinding</td>
</tr>
<tr>
<th>Definitie</th>
<td>Aaneengesloten deel van een weg dat bedoeld is voor bepaalde groepen verkeersgebruikers.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegverkeerruimteverbinding">Wegverkeerruimteverbinding</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_baanverbinding_attribuutsoort_type">type</a>
</td>
<td>
</td>
<td>

</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_baanverbinding_attribuutsoort_afritnummer">afritnummer</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Integer</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_baanverbinding_attribuutsoort_hectometerpunt">hectometerpunt</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Decimal</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_baanverbinding_relatiesoort_is_onderdeel_van">isOnderdeelVan</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegverbinding">Wegverbinding</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Strookverbinding {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_strookverbinding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Strookverbinding</td>
</tr>
<tr>
<th>Definitie</th>
<td>Door doorgetrokken of onderbroken strepen gemarkeerd gedeelte van de baan.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegverkeerruimteverbinding">Wegverkeerruimteverbinding</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_strookverbinding_attribuutsoort_type">type</a>
</td>
<td>
</td>
<td>

</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_strookverbinding_relatiesoort_is_onderdeel_van">isOnderdeelVan</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_baanverbinding">Baanverbinding</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Wegknoop {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegknoop}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Wegknoop</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>

</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportknoop">Transportknoop</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegknoop_attribuutsoort_type_keuzepunt">typeKeuzepunt</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_keuzepunt">TypeKeuzepunt</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegknoop_relatiesoort_heeft">heeft</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_openbare_ruimte">OpenbareRuimte</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>

#### Baanknoop {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_baanknoop}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Baanknoop</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportknoop">Transportknoop</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>



<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_baanknoop_relatiesoort_ligt_aan">ligtAan</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_baanverbinding">Baanverbinding</a>
</td>
<td>
1..2</td>
</tr>
</tbody>
</table>
</section>

#### Strookknoop {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_strookknoop}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Strookknoop</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportknoop">Transportknoop</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Wegverkeerruimteverbinding {#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegverkeerruimteverbinding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Wegverkeerruimteverbinding</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>

</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportverbinding">Transportverbinding</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_objecttype_wegverkeerruimteverbinding_attribuutsoort_rijrichting">rijrichting</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_wegen_enumeratie_rijrichting">Rijrichting</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>








### Enumeraties

#### Rijrichting {#informatiemodel_conceptueel_model_ibro_domein_wegen_enumeratie_rijrichting}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Rijrichting</td>
</tr>
<tbody>
</tbody>
</table>


<section class="notoc">
<h5>Overzicht waarden</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 75%"></colgroup>
<tbody>
<tr>
  <th>Waarde</th>
  <th>Definitie</th>
</tr>
<tr>
<td>
Beide</td>
<td>
Beide rijrichtingen zijn op de verbinding toegestaan.</td>
<tr>
<td>
Eenrichting</td>
<td>
Eén rijrichting is op verbinding toegestaan.</td>
</tbody>
</table>


</section>



### Codelijsten

#### TypeVerharding {#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_verharding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeVerharding</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeVerkeerskundigFunctioneleZone {#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_verkeerskundig_functionele_zone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeVerkeerskundigFunctioneleZone</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeWegzone {#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_wegzone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeWegzone</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeSpoorzone {#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_spoorzone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeSpoorzone</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeLuchtvaartzone {#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_luchtvaartzone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeLuchtvaartzone</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeSpoorverbinding {#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_spoorverbinding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeSpoorverbinding</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeKeuzepunt {#informatiemodel_conceptueel_model_ibro_domein_wegen_codelijst_type_keuzepunt}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeKeuzepunt</td>
</tr>
<tbody>
</tbody>
</table>



## Domein Gebouwen
### Objecttypen

#### Pand {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_pand}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Pand</td>
</tr>
<tr>
<th>Definitie</th>
<td>Overdekte en geheel of grotendeels met wanden omsloten constructief zelfstandige eenheid bedoeld voor het in een afgeschermde omgeving onderbrengen van mensen, dieren of voorwerpen of voor de productie van goederen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op definitie “pand” in artikel 1 Wet basisregistratie adressen en gebouwen en de INSPIRE richtlijn</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Er is gekozen voor de naam Pand in plaats van de naam Gebouw zoals in de SOR. De BAG afbakeningscriteria blijven behouden. Dit om de BAG bijhouding niet te verstoren.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_pand_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een gebouw.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Solid"> GM_Solid</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_pand_attribuutsoort_type">type</a>
</td>
<td>
Categorisering van een gebouw op basis van het constructief beoogde gebruik.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_type_pand">TypePand</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_pand_attribuutsoort_aard">aard</a>
</td>
<td>
Fysieke verschijningsvorm van een gebouw.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_aard_pand">AardPand</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_pand_attribuutsoort_oorspronkelijk_bouwjaar">oorspronkelijkBouwjaar</a>
</td>
<td>
Aanduiding van het jaar waarin een gebouw oorspronkelijk als bouwkundig gereed is of zal worden opgeleverd.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Year</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_pand_attribuutsoort_naam">naam</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>



#### Bouwlaag {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_bouwlaag}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Bouwlaag</td>
</tr>
<tr>
<th>Definitie</th>
<td>Verzameling van ruimten die zijn gelegen op hetzelfde niveau binnen een gebouw</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op de definitie van het begrip Bouwlaag (IfcBuildingStorey) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)</td>
</tr>
<tr>
<th>Toelichting</th>
<td>In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan bouwlaag moet worden gegeven.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_bouwlaag_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een bouwlaag.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_bouwlaag_attribuutsoort_bouwlaagnummer">bouwlaagnummer</a>
</td>
<td>
Niveau waarop een bouwlaag zich bevindt</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Integer</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_bouwlaag_relatiesoort_ligt_in">ligtIn</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_pand">Pand</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Ruimte {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Ruimte</td>
</tr>
<tr>
<th>Definitie</th>
<td>Voor mensen toegankelijk deel van een gebouw, dat ten minste aan de onderzijde en/of de bovenzijde wordt begrensd door een scheidingsconstructie en dat een netto-hoogte heeft van tenminste 1,5 m.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Ontleend aan NEN 2580 en aansluitend op het begrip Ruimte (IfcSpace) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)</td>
</tr>
<tr>
<th>Toelichting</th>
<td>In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan ruimte moet worden gegeven. Ook zal dan gedetailleerder worden vastgelegd welke ruimten in de registratie zouden kunnen worden opgenomen. Hierbij gaat de gedachte primair uit naar ruimten in multifunctionele complexe gebouwen met meerdere ruimten met verschillende functies. Het is niet de bedoeling om landelijk alle ruimten in woningen in de registratie op te gaan nemen.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_ruimte_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een ruimte.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_ruimte_attribuutsoort_bouwlaagnummer">bouwlaagnummer</a>
</td>
<td>
Bouwlaag waarop een ruimte zich bevindt</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Integer</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_ruimte_attribuutsoort_oppervlakte">oppervlakte</a>
</td>
<td>
Gebruiksoppervlakte van een ruimte.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Integer</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_ruimte_attribuutsoort_type">type</a>
</td>
<td>
Categorisering van een ruimte op basis van het constructief beoogde gebruik.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_type_ruimte">TypeRuimte</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Panddeel {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_panddeel}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Panddeel</td>
</tr>
<tr>
<th>Herkomst</th>
<td>Gemeentelijk Gebouwinformatiemodel</td>
</tr>
<tr>
<th>Definitie</th>
<td>Component aan de buitenzijde van een gebouw, die het aanzicht van het gebouw mede bepaalt.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>IMGeo 2.2</td>
</tr>
<tr>
<th>Toelichting</th>
<td>In een later stadium zullen inwinregels worden opgesteld die de minimale omvang van de vast te leggen objecten aangeeft. Ook zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan gebouwcomponenten moet worden gegeven.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_panddeel_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een gebouwcomponent.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_keuze_datatype__punt_lijn_of_vlak">PuntLijnOfVlak</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_panddeel_attribuutsoort_aard">aard</a>
</td>
<td>
Soort gebouwcomponent.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_aard_gebouwcomponent">AardGebouwcomponent</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_panddeel_relatiesoort_hoort_bij">hoortBij</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_keuze_relatiedoel__verblijfsobject_of_gebouw">VerblijfsobjectOfGebouw</a>
</td>
<td>
1..2</td>
</tr>
</tbody>
</table>
</section>

#### Toegangsdeur {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_toegangsdeur}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Toegangsdeur</td>
</tr>
<tr>
<th>Definitie</th>
<td>Deur of andere voorziening die vanaf de openbare weg, een erf of een gedeelde verkeersruimte toegang geeft tot een object.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Begrip sluit aan bij het begrip Deur (IfcDoor) uit de concepten rondom Bouwwerkinformatiemodellen (BIM)</td>
</tr>
<tr>
<th>Toelichting</th>
<td>In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan toegangsdeur moet worden gegeven.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_toegangsdeur_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een toegangsdeur.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_toegangsdeur_attribuutsoort_toegangssoort">toegangssoort</a>
</td>
<td>
Plaats waarvan een toegangsdeur toegang geeft.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_toegangssoort">Toegangssoort</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_toegangsdeur_attribuutsoort_gebruiksaard">gebruiksaard</a>
</td>
<td>
Aard van gebruik van een toegangsdeur.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_gebruiksaard_toegangsdeur">GebruiksaardToegangsdeur</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_toegangsdeur_relatiesoort_hoort_bij">hoortBij</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_keuze_relatiedoel__verblijfsobject_of_gebouw">VerblijfsobjectOfGebouw</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Erfconstructie {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_erfconstructie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Erfconstructie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>Gemeentelijk Gebouwinformatiemodel</td>
</tr>
<tr>
<th>Definitie</th>
<td>Afzonderlijk staande overdekking rustend op een constructie met kolommen met één of meerdere open gevels bedoeld voor het beschutten of stallen van mensen, dieren, objecten en/of voer- en vaartuigen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op definities “open loods” en “overkapping” uit de gegevenscatalogus BGT</td>
</tr>
<tr>
<th>Toelichting</th>
<td>In een later stadium zullen de inwinregels worden opgesteld die de minimale omvang van de vast te leggen objecten en de eventuele kolommen aangeeft. Ook zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan open bouwwerken moet worden gegeven.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_erfconstructie_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een open bouwwerk.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Solid"> GM_Solid</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_erfconstructie_attribuutsoort_type">type</a>
</td>
<td>
Soort open bouwwerk.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_type_erfconstructie">TypeErfconstructie</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_erfconstructie_attribuutsoort_naam">naam</a>
</td>
<td>
Breed geaccepteerde benaming van een open bouwwerk zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>



#### Verblijfsobject {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_verblijfsobject}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Verblijfsobject</td>
</tr>
<tr>
<th>Definitie</th>
<td>Kleinste binnen één of meer gebouwen gelegen eenheid van gebruik die ontsloten wordt via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, en die onderwerp kan zijn van goederenrechtelijke rechtshandelingen en in functioneel opzicht zelfstandig is.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op definitie “verblijfsobject” in artikel 1 Wet basisregistratie adressen en gebouwen.</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Verblijfsobject is een optelling van de Functiezones binnen het pand. In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan verblijfsobject moet worden gegeven.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_ruimte">FunctioneleRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_verblijfsobject_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een verblijfsobject.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_verblijfsobject_attribuutsoort_gebruiksdoel">gebruiksdoel</a>
</td>
<td>
Categorisering van de gebruiksdoelen van een verblijfsobject zoals in de vergunning is opgenomen of bij constatering is vastgesteld.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_gebruiksdoel">Gebruiksdoel</a>
</td>
<td>
1..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_verblijfsobject_attribuutsoort_gebruiksoppervlakte">gebruiksoppervlakte</a>
</td>
<td>
Gebruiksoppervlakte van een verblijfsobject.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Integer</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_verblijfsobject_relatiesoort_hoort_bij">hoortBij</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_pand">Pand</a>
</td>
<td>
1..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_verblijfsobject_relatiesoort_heeft">heeft</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_nummeraanduiding">Nummeraanduiding</a>
</td>
<td>
1..*</td>
</tr>
</tbody>
</table>
</section>

#### Functiezone {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_functiezone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Functiezone</td>
</tr>
<tr>
<th>Herkomst</th>
<td>Gemeentelijk Gebouwinformatiemodel</td>
</tr>
<tr>
<th>Definitie</th>
<td>Grootst mogelijke gedeelte van een pand dat in zijn geheel is gelegen op een bouwlaag en binnen de afbakening van een pand, waaraan eenduidig een bouwjaar kan worden toegekend, en dat qua constructie en gebruiksmogelijkheden voldoende uniform is.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Begrip gebaseerd op de functionele deelobjecten uit de WOZ en aansluitend bij het begrip Zonering (IfcZone) uit de concepten rondom Bouwwerkinformatiemodellen (BIM), waarbij ruimten worden gezoneerd tot bijvoorbeeld verblijfsobject of gebouwzone</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het gaat om het vergund gebruik: Verkeer, Verblijven, Opslag, of Techisch. In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan gebouwzone moet worden gegeven.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_ruimte">FunctioneleRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_functiezone_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een gebouwzone.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_functiezone_attribuutsoort_geometrie_oppervlakte">geometrieOppervlakte</a>
</td>
<td>
Geometrische representatie van de oppervlakte van een gebouwzone die betrokken wordt in de berekening van de gebruiksoppervlakte.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_functiezone_attribuutsoort_bouwlaagnummer">bouwlaagnummer</a>
</td>
<td>
Bouwlaag waarop een gebouwzone is gelegen.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Integer</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_functiezone_attribuutsoort_bouwjaar">bouwjaar</a>
</td>
<td>
Aanduiding van het jaar waarin een gebouwzone is ontstaan.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Year</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_functiezone_attribuutsoort_type">type</a>
</td>
<td>
Categorisering van het feitelijke gebruik dat van een gebouwzone wordt gemaakt.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_type_functiezone">TypeFunctiezone</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_functiezone_attribuutsoort_aard_fysieke_constructie">aardFysiekeConstructie</a>
</td>
<td>
Aanduiding van de fysieke constructie waarin een gebouwzone zich bevindt.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_aard_fysieke_constructie">AardFysiekeConstructie</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_functiezone_attribuutsoort_gebruiksoppervlakte">gebruiksoppervlakte</a>
</td>
<td>
Gebruiksoppervlakte van een gebouwzone.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Integer</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_functiezone_relatiesoort_hoort_bij">hoortBij</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_verblijfsobject">Verblijfsobject</a>
</td>
<td>
0..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_functiezone_relatiesoort_ligt_op">ligtOp</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_bouwlaag">Bouwlaag</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Gebruiksobject {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_gebruiksobject}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Gebruiksobject</td>
</tr>
<tr>
<th>Herkomst</th>
<td>Gemeentelijk Gebouwinformatiemodel</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een aggregatie van alle bouwwerken die bij een verblijfsobject horen</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_gebruiksobject_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
De geometrie van het gebruiksoppervlakte.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_gebruiksobject_attribuutsoort_type">type</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_type_gebruiksobject">TypeGebruiksobject</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_gebruiksobject_relatiesoort_bevat">bevat</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_erfconstructie">Erfconstructie</a>
</td>
<td>
0..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_gebruiksobject_relatiesoort_bevat">bevat</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_pand">Pand</a>
</td>
<td>
1..*</td>
</tr>
</tbody>
</table>
</section>








### Codelijsten

#### TypePand {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_type_pand}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypePand</td>
</tr>
<tbody>
</tbody>
</table>


#### AardPand {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_aard_pand}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>AardPand</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeRuimte {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_type_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeRuimte</td>
</tr>
<tbody>
</tbody>
</table>


#### AardGebouwcomponent {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_aard_gebouwcomponent}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>AardGebouwcomponent</td>
</tr>
<tbody>
</tbody>
</table>


#### Toegangssoort {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_toegangssoort}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Toegangssoort</td>
</tr>
<tbody>
</tbody>
</table>


#### GebruiksaardToegangsdeur {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_gebruiksaard_toegangsdeur}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>GebruiksaardToegangsdeur</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeErfconstructie {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_type_erfconstructie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeErfconstructie</td>
</tr>
<tbody>
</tbody>
</table>


#### Gebruiksdoel {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_gebruiksdoel}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Gebruiksdoel</td>
</tr>
<tbody>
</tbody>
</table>


#### FeitelijkGebruik {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_feitelijk_gebruik}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>FeitelijkGebruik</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeFunctiezone {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_type_functiezone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeFunctiezone</td>
</tr>
<tbody>
</tbody>
</table>


#### AardFysiekeConstructie {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_aard_fysieke_constructie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>AardFysiekeConstructie</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeGebruiksobject {#informatiemodel_conceptueel_model_ibro_domein_gebouwen_codelijst_type_gebruiksobject}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeGebruiksobject</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het gaat om het geconstateerd / feitelijk gebruik, zoals in de WOZ.</td>
</tr>
<tbody>
</tbody>
</table>



## Domein Kunstwerken
### Objecttypen

#### Overbrugging {#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_overbrugging}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Overbrugging</td>
</tr>
<tr>
<th>Definitie</th>
<td>Kunstwerk dat een beweegbare of vaste verbinding tussen twee punten betreft, die door water, een weg of anderszins gescheiden zijn, bestaande uit een brugdek/-bak met landhoofden en veelal gesteund door pijlers.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_overbrugging_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een overbrugging.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_overbrugging_attribuutsoort_type">type</a>
</td>
<td>
Aanduiding van het soort overbrugging.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_codelijst_type_overbrugging">TypeOverbrugging</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_overbrugging_attribuutsoort_naam">naam</a>
</td>
<td>
Breed geaccepteerde benaming van een overbrugging zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_overbrugging_attribuutsoort_indicatie_beweegbaar">indicatieBeweegbaar</a>
</td>
<td>
Deze overbrugging is al dan niet beweegbaar is (kan open en dicht).</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Boolean</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Ondertunneling {#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_ondertunneling}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Ondertunneling</td>
</tr>
<tr>
<th>Definitie</th>
<td>Ondergrondse of onder water gelegen verbinding tussen twee punten, aan beide einden voorzien van een open bakconstructie.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven welke typeringen verplicht in de registratie worden opgenomen.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_ondertunneling_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een ondertunneling.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_ondertunneling_attribuutsoort_type">type</a>
</td>
<td>
Aanduiding van het soort ondertunneling.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_codelijst_type_ondertunneling">TypeOndertunneling</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_ondertunneling_attribuutsoort_naam">naam</a>
</td>
<td>
Breed geaccepteerde benaming van een ondertunneling zoals deze door de eigenaar is toegekend of zoals deze in de volksmond bekend staat.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>



#### WaterstaatkundigKunstwerk {#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_waterstaatkundig_kunstwerk}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>WaterstaatkundigKunstwerk</td>
</tr>
<tr>
<th>Definitie</th>
<td>Kunstwerk voor de beheersing van het oppervlaktewater en alles wat daarin voorkomt.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>De kerende functie kan worden vastgelegd middels de functionele ruimte kering van het type water.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_waterstaatkundig_kunstwerk_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een waterstaatkundig kunstwerk.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_waterstaatkundig_kunstwerk_attribuutsoort_type">type</a>
</td>
<td>
Aanduiding van het soort waterstaatkundig kunstwerk.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_codelijst_type_waterstaatkundig_kunstwerk">TypeWaterstaatkundigKunstwerk</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_waterstaatkundig_kunstwerk_relatiesoort_heeft_functie">heeftFunctie</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_kering">Kering</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>

#### Kunstwerkdeel {#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_kunstwerkdeel}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Kunstwerkdeel</td>
</tr>
<tr>
<th>Definitie</th>
<td>Onderdeel van een civieltechnisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>BGT 1.2</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_kunstwerkdeel_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een kunstwerkdeel.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_kunstwerkdeel_attribuutsoort_type">type</a>
</td>
<td>
Aanduiding van het soort kunstwerkdeel</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_codelijst_type_kunstwerkdeel">TypeKunstwerkdeel</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_objecttype_kunstwerkdeel_relatiesoort_is_onderdeel_van">isOnderdeelVan</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_keuze_relatiedoel__overbrugging_of_waterstaatkundig_kunstwerk">OverbruggingOfWaterstaatkundigKunstwerk</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>








### Codelijsten

#### TypeOverbrugging {#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_codelijst_type_overbrugging}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeOverbrugging</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeOndertunneling {#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_codelijst_type_ondertunneling}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeOndertunneling</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeWaterstaatkundigKunstwerk {#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_codelijst_type_waterstaatkundig_kunstwerk}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeWaterstaatkundigKunstwerk</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeKunstwerkdeel {#informatiemodel_conceptueel_model_ibro_domein_kunstwerken_codelijst_type_kunstwerkdeel}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeKunstwerkdeel</td>
</tr>
<tbody>
</tbody>
</table>



## Domein Overige constructies
### Objecttypen

#### Kering {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_kering}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Kering</td>
</tr>
<tr>
<th>Definitie</th>
<td>Voorziening met een kerende functie.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Een waterkerende en/of scheidende, kunstmatige of natuurlijke hoogte of hooggelegen gronden inclusief de daarin aanwezige waterkerende elementen.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_ruimte">FunctioneleRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_kering_attribuutsoort_lijngeometrie">lijngeometrie</a>
</td>
<td>
Geometrische representatie van een kering.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_kering_attribuutsoort_vlakgeometrie">vlakgeometrie</a>
</td>
<td>
Geometrische representatie van een kering.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_kering_attribuutsoort_type">type</a>
</td>
<td>
Typering van een kering.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_codelijst_type_kering">TypeKering</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Reducering {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_reducering}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Reducering</td>
</tr>
<tr>
<th>Definitie</th>
<td>Voorziening om bepaalde effecten van omgevingsfactoren te verminderen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_ruimte">FunctioneleRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_reducering_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van de reducerende voorziening.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_reducering_attribuutsoort_type">type</a>
</td>
<td>
Categorisering van de verschillende type reducering.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_codelijst_type_reducering">TypeReducering</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Afscheiding {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_afscheiding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Afscheiding</td>
</tr>
<tr>
<th>Definitie</th>
<td>Functionele ruimte die een voorziening betreft om terrein af te scheiden.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_ruimte">FunctioneleRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_afscheiding_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Afvalcontainer {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_afvalcontainer}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Afvalcontainer</td>
</tr>
<tr>
<th>Definitie</th>
<td>Constructie met een permanent karakter voor het inzamelen van afval.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op IMGeo 2.2</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_afvalcontainer_attribuutsoort_puntgeometrie">puntgeometrie</a>
</td>
<td>
Geometrische representatie van een afvalcontainer.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Dok {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_dok}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Dok</td>
</tr>
<tr>
<th>Definitie</th>
<td>Constructie bedoeld om schepen uit het water te halen en vervolgens weer in het water te laten.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_dok_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een dok.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Geleideconstructie {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_geleideconstructie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Geleideconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Constructie bedoeld voor de fysieke (be-)geleiding van voer- of vaartuigen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het SOR-begrip geleideconstructie omvat meer dan het gelijknamige BGT/IMGeo objecttype weginrichtingselement; geleideconstructie.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_geleideconstructie_attribuutsoort_puntgeometrie">puntgeometrie</a>
</td>
<td>
Geometrische representatie van de ligging van de geleideconstructie.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_geleideconstructie_attribuutsoort_lijngeometrie">lijngeometrie</a>
</td>
<td>
Geometrische representatie van de ligging van de geleideconstructie.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_geleideconstructie_attribuutsoort_vlakgeometrie">vlakgeometrie</a>
</td>
<td>
Geometrische representatie van de ligging van de geleideconstructie.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Installatie {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_installatie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Installatie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Constructie die een technisch samenhangend systeem betreft dat een bepaald doel dient.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op installatie in IMGeo 2.2</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_installatie_attribuutsoort_puntgeometrie">puntgeometrie</a>
</td>
<td>
Geometrische representatie van de installatie.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_installatie_attribuutsoort_lijngeometrie">lijngeometrie</a>
</td>
<td>
Geometrische representatie van de installatie.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_installatie_attribuutsoort_vlakgeometrie">vlakgeometrie</a>
</td>
<td>
Geometrische representatie van de installatie.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_installatie_attribuutsoort_type">type</a>
</td>
<td>
Aanduiding van het soort installatie</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_codelijst_type_installatie">TypeInstallatie</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_installatie_relatiesoort_hoort_bij">hoortBij</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_gebouwen_objecttype_pand">Pand</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Mast {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_mast}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Mast</td>
</tr>
<tr>
<th>Definitie</th>
<td>Hoge draagconstructie voor een installatie of het transport van energie en elektromagnetische straling.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_mast_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van de mast.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_keuze_datatype__punt_multipunt_lijn_vlak_of_multivlak">PuntMultipuntLijnVlakOfMultivlak</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_mast_attribuutsoort_indicatie_open">indicatieOpen</a>
</td>
<td>
Geeft aan of een mast al dan niet open is.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Boolean</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Muur {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_muur}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Muur</td>
</tr>
<tr>
<th>Definitie</th>
<td>Constructie die een relatief smal, rechtopstaand bouwwerk betreft.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_muur_attribuutsoort_lijngeometrie">lijngeometrie</a>
</td>
<td>
Geometrische representatie van een muur.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_muur_attribuutsoort_vlakgeometrie">vlakgeometrie</a>
</td>
<td>
Geometrische representatie van een muur.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_muur_attribuutsoort_indicatie_valbescherming">indicatieValbescherming</a>
</td>
<td>
Muur die al dan niet bedoeld is om vallen te voorkomen.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Boolean</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_muur_relatiesoort_heeft_functie">heeftFunctie</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_keuze_relatiedoel__kering_of_afscheiding">KeringOfAfscheiding</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>

#### Omheining {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_omheining}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Omheining</td>
</tr>
<tr>
<th>Definitie</th>
<td>Kunstmatige verticale constructie die bedoeld is om de toegang tot een gebied te weren.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_omheining_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een omheining.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_omheining_attribuutsoort_indicatie_valbescherming">indicatieValbescherming</a>
</td>
<td>
Omheining die al dan niet bedoeld is om vallen te voorkomen.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Boolean</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_omheining_relatiesoort_heeft_functie">heeftFunctie</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_afscheiding">Afscheiding</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>

#### Opslagtank {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_opslagtank}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Opslagtank</td>
</tr>
<tr>
<th>Definitie</th>
<td>Constructie in de vorm van een bovengronds, afgesloten reservoir bestemd voor gassen, energie of vloeistoffen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>IMGeo 2.2</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_opslagtank_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een opslagtank</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Paal {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_paal}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Paal</td>
</tr>
<tr>
<th>Definitie</th>
<td>Lage draagconstructie voor onder meer installaties of borden.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_paal_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van de paal</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Putdeksel {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_putdeksel}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Putdeksel</td>
</tr>
<tr>
<th>Definitie</th>
<td>Afsluitende deel van een toegang tot een ingegraven constructie of netwerk.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Afgeleid van de definitie van een put in IMGeo 2.2</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_putdeksel_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een putdeksel.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Reservoir {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_reservoir}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Reservoir</td>
</tr>
<tr>
<th>Definitie</th>
<td>Constructie voor het (tijdelijk) bergen van water.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>gebaseerd op IMBOR 2020</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_reservoir_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een reservoir.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Scherm {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_scherm}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Scherm</td>
</tr>
<tr>
<th>Definitie</th>
<td>Lineaire constructie specifiek bedoeld om te reduceren.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_scherm_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een scherm.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_scherm_relatiesoort_heeft_functie">heeftFunctie</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_reducering">Reducering</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>

#### Straatmeubilair {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_straatmeubilair}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Straatmeubilair</td>
</tr>
<tr>
<th>Definitie</th>
<td>Constructie ter inrichting van de openbare ruimte niet verbonden met ondergrondse objecten.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op IMGeo 2.2</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_straatmeubilair_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van het straatmeubilair.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_straatmeubilair_attribuutsoort_type">type</a>
</td>
<td>
Typering van straatmeubilair.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_codelijst_type_straatmeubilair">TypeStraatmeubilair</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>



#### Zwembad {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_zwembad}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Zwembad</td>
</tr>
<tr>
<th>Definitie</th>
<td>Constructie in de vorm van een bassin bedoeld om in te zwemmen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>In een later stadium zullen registratieregels worden opgesteld waarin een nadere invulling wordt gegeven aan de interpretatie die aan zwembad moet worden gegeven. Daarbij zal ook nader worden bepaald in welke gevallen overdekte zwembaden in de registratie worden opgenomen.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_objecttype_zwembad_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een zwembad.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>










### Codelijsten

#### TypeKering {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_codelijst_type_kering}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeKering</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeReducering {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_codelijst_type_reducering}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeReducering</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeInstallatie {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_codelijst_type_installatie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeInstallatie</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeStraatmeubilair {#informatiemodel_conceptueel_model_ibro_domein_overige_constructies_codelijst_type_straatmeubilair}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeStraatmeubilair</td>
</tr>
<tbody>
</tbody>
</table>



## Domein Geografische ruimten
### Objecttypen

#### Bebouwingskern {#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_bebouwingskern}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Bebouwingskern</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geografische ruimte die gekenmerkt wordt door een concentratie van gebouwen en die vanuit besluitvorming, historie of in de volksmond bekend staat onder een bepaalde naam.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op definitie Plaats in BRT</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Met bebouwingskernen kan een algemeen toepasbaar onderscheid worden aangebracht tussen bebouwd gebied en het buitengebied. Tot het buitengebied kan dan worden gerekend al het gebied dat niet behoort tot een bebouwingskern, De bebouwingskern (zonder juridische status) moet niet worden verward met bebouwde kommen (die wel een juridische grondslag kennen in specifieke wetgeving). Hierbij kan worden gedacht aan de bebouwde kom in het kader van Wegenverkeerswet, Wegenwet, Wet natuurbescherming en Omgevingswet. De diversiteit in achterliggende doelstellingen van genoemde wetgeving maakt het op dit moment niet mogelijk te komen tot één uniform en breed bruikbaar begrip bebouwde kom. Deze bebouwde kommen maken dan ook geen onderdeel uit van de SOR. De regels voor de afbakening zullen worden vastgelegd in registratievoorschriften. Hierbij kan worden gedacht aan voorschriften dat alleen van een bebouwingskern sprake is bij aaneengesloten bebouwing waarbij de gebouwen maximaal 50 meter van elkaar liggen en deze minimaal 5 verschillende gebouwen met een verblijfsobject bevatten.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_geografische_ruimte">GeografischeRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_bebouwingskern_attribuutsoort_naam">naam</a>
</td>
<td>
Plaatselijke naam van een bebouwingskern zoals deze als woonplaats bekend is of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_bebouwingskern_attribuutsoort_alternatieve_naam">alternatieveNaam</a>
</td>
<td>
Alternatieve benaming van een bebouwingskern zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries).</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_bebouwingskern_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een bebouwingskern.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_keuze_datatype__vlak_of_multivlak">VlakOfMultivlak</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_bebouwingskern_attribuutsoort_type">type</a>
</td>
<td>
Hoofdkarakter van het gebied dat een bebouwingskern vormt.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_codelijst_type_bebouwingskern">TypeBebouwingskern</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_bebouwingskern_relatiesoort_ligt_in">ligtIn</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_registratieve_ruimten_objecttype_gemeentegebied">Gemeentegebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

#### Streek {#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_streek}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Streek</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_geografische_ruimte">GeografischeRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_streek_attribuutsoort_naam">naam</a>
</td>
<td>
Plaatselijke naam van een streek zoals deze formeel is vastgesteld of bij het ontbreken daarvan zoals deze in het plaatselijk gebruik bekend staat.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_streek_attribuutsoort_alternatieve_naam">alternatieveNaam</a>
</td>
<td>
Alternatieve benaming van een streek zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries).</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_streek_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een streek.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### LandschappelijkGebied {#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_landschappelijk_gebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>LandschappelijkGebied</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geografische ruimte die een fysisch-geografische samenhang vertoont.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het landschappelijk gebied is al dan niet begroeid, bebouwd of bedekt door water of wegen, waarbij de typering leidend is.</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_geografische_ruimte">GeografischeRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_landschappelijk_gebied_attribuutsoort_naam">naam</a>
</td>
<td>
Plaatselijke naam van een landschappelijk gebied zoals deze is vastgesteld of in het plaatselijk gebruik bekend staat.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_landschappelijk_gebied_attribuutsoort_alternatieve_naam">alternatieveNaam</a>
</td>
<td>
Alternatieve benaming van een landschappelijk gebied zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries).</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_landschappelijk_gebied_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een landschappelijk gebied.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_landschappelijk_gebied_attribuutsoort_type">type</a>
</td>
<td>
Aard van een landschappelijk gebied.</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_codelijst_type_landschappelijk_gebied">TypeLandschappelijkGebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>



#### Reliëfzone {#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_reliefzone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Reliëfzone</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geografische ruimte die een hoogteverschil in het landschap aanduidt.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Basisregistratie Topografie: Catalogus en Productspecificaties (versie 1.2.0.1)</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_geografische_ruimte">GeografischeRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_reliefzone_attribuutsoort_naam">naam</a>
</td>
<td>
Plaatselijke naam van een reliëfzone zoals deze is vastgesteld of in het plaatselijk gebruik bekend staat.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_reliefzone_attribuutsoort_alternatieve_naam">alternatieveNaam</a>
</td>
<td>
Alternatieve benaming van een reliëfzone zoals deze breed is geaccepteerd in de volksmond of zoals deze bekend staat in het Fries (bij een benaming in het Nederlands) of in het Nederlands (bij een benaming in het Fries)</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_reliefzone_attribuutsoort_puntgeometrie">puntgeometrie</a>
</td>
<td>
Geometrische representatie van het reliëfzone bekend is.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_reliefzone_attribuutsoort_lijngeometrie">lijngeometrie</a>
</td>
<td>
Geometrische representatie van het reliëfzone bekend is.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_LineString"> GM_LineString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_reliefzone_attribuutsoort_vlakgeometrie">vlakgeometrie</a>
</td>
<td>
Geometrische representatie van het reliëfzone bekend is.</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_objecttype_reliefzone_attribuutsoort_type">type</a>
</td>
<td>
Hoofdkarakter van het reliëfzone.</td>
<td>

</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>










### Codelijsten

#### TypeBebouwingskern {#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_codelijst_type_bebouwingskern}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeBebouwingskern</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeLandschappelijkGebied {#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_codelijst_type_landschappelijk_gebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeLandschappelijkGebied</td>
</tr>
<tbody>
</tbody>
</table>


#### TypeReliëfzone {#informatiemodel_conceptueel_model_ibro_domein_geografische_ruimten_codelijst_type_reliefzone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>TypeReliëfzone</td>
</tr>
<tbody>
</tbody>
</table>



## Domein Netwerk
### Objecttypen

#### Netwerkelement {#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerkelement}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Netwerkelement</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>




<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerkelement_relatiesoort_in_netwerk">in netwerk</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerk">Netwerk</a>
</td>
<td>
0..*</td>
</tr>
</tbody>
</table>
</section>

#### Netwerk {#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerk}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Netwerk</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>





#### Knoop {#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_knoop}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Knoop</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerkelement">Netwerkelement</a>
</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#extern_inspire_generic_network_model_objecttype_node">Node</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_knoop_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Point"> GM_Point</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_knoop_relatiesoort_inkomende_verbinding">inkomendeVerbinding</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_verbinding">Verbinding</a>
</td>
<td>
0..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_knoop_relatiesoort_uitgaande_verbinding">uitgaandeVerbinding</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_verbinding">Verbinding</a>
</td>
<td>
0..*</td>
</tr>
</tbody>
</table>
</section>

#### Verbinding {#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_verbinding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Verbinding</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerkelement">Netwerkelement</a>
</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#extern_inspire_generic_network_model_objecttype_link">Link</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_verbinding_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Curve"> GM_Curve</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>


<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_verbinding_relatiesoort_startknoop">startknoop</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_knoop">Knoop</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_verbinding_relatiesoort_eindknoop">eindknoop</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_knoop">Knoop</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>

#### Netwerkverwijzing {#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerkverwijzing}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Netwerkverwijzing</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>




<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerkverwijzing_relatiesoort_netwerkelement">netwerkelement</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerkelement">Netwerkelement</a>
</td>
<td>
1..1</td>
</tr>
</tbody>
</table>
</section>

#### Netwerkeigenschap {#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerkeigenschap}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Netwerkeigenschap</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>




<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerkeigenschap_relatiesoort_netwerkverwijzing">netwerkverwijzing</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_netwerkverwijzing">Netwerkverwijzing</a>
</td>
<td>
1..*</td>
</tr>
</tbody>
</table>
</section>









## Domein Transport
### Objecttypen

#### Transportverbinding {#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportverbinding}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Transportverbinding</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_verbinding">Verbinding</a>
</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportruimte">Transportruimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Transportknoop {#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportknoop}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Transportknoop</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportruimte">Transportruimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_netwerk_objecttype_knoop">Knoop</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Transportruimte {#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td></td>
</tr>
<tr>
<th>Naam</th>
<td>Transportruimte</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>

</td>
</tr>
<tbody>
</tbody>
</table>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_ruimte">FunctioneleRuimte</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>



<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 15%"></colgroup>
<colgroup style="width: 10%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportruimte_relatiesoort_ligt_op">ligtOp</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_reeel_object">ReeelObject</a>
</td>
<td>
1..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_transport_objecttype_transportruimte_relatiesoort_hyperverbinding">hyperverbinding</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_algemeen_objecttype_functionele_zone">FunctioneleZone</a>
</td>
<td>
0..*</td>
</tr>
</tbody>
</table>
</section>









## Domein Functionele zoneringen
### Objecttypen

#### Bungalowpark {#informatiemodel_conceptueel_model_ibro_domein_functionele_zoneringen_objecttype_bungalowpark}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Bungalowpark</td>
</tr>
<tr>
<th>Naam</th>
<td>Bungalowpark</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geheel van begroeiing, verharding en gebouwen, bedoeld voor niet-permanente bewoning.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_recreatiezone">Recreatiezone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Camping {#informatiemodel_conceptueel_model_ibro_domein_functionele_zoneringen_objecttype_camping}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Camping</td>
</tr>
<tr>
<th>Naam</th>
<td>Camping</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geheel van begroeiing, verharding en gebouwen, bedoeld voor tijdelijk verblijf in kampeermiddel.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_recreatiezone">Recreatiezone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Park {#informatiemodel_conceptueel_model_ibro_domein_functionele_zoneringen_objecttype_park}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Park</td>
</tr>
<tr>
<th>Naam</th>
<td>Park</td>
</tr>
<tr>
<th>Definitie</th>
<td>Landschappelijk ingericht terrein, met begroeiing, verharding, water en gebouwen, bedoeld als recreatieve voorziening.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_recreatiezone">Recreatiezone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Speeltuin {#informatiemodel_conceptueel_model_ibro_domein_functionele_zoneringen_objecttype_speeltuin}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Speeltuin</td>
</tr>
<tr>
<th>Naam</th>
<td>Speeltuin</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geheel van speelwerktuigen, begroeiing, verharding en gebouwen, bedoeld als speelplaats voor kinderen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_recreatiezone">Recreatiezone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Sportterrein {#informatiemodel_conceptueel_model_ibro_domein_functionele_zoneringen_objecttype_sportterrein}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Sportterrein</td>
</tr>
<tr>
<th>Naam</th>
<td>Sportterrein</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geheel van begroeiing, verharding en gebouwen bestemd voor sportbeoefening.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_recreatiezone">Recreatiezone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>




#### Volkstuin {#informatiemodel_conceptueel_model_ibro_domein_functionele_zoneringen_objecttype_volkstuin}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/ibro#Volkstuin</td>
</tr>
<tr>
<th>Naam</th>
<td>Volkstuin</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geheel van begroeiing, verharding en gebouwen in gebruik als particuliere tuinen die niet bij de woning liggen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_conceptueel_model_ibro_domein_groen_objecttype_recreatiezone">Recreatiezone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>














## Extern NEN 3610:2022 - Basismodel geo-informatie
## Extern INSPIRE - Generic Network Model
