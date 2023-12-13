Laddningstid och användbarhet
=======================

Analys av tre webbplatser och dess laddningstider. Rapporten ska undersöka hur en hemsidas uppbyggnad kan komma att påverka prestanda samt upplevelse för användaren.

Urval
-----------------------

Urvalet för denna analys gjordes genom att tre olika kommuners/städers webbplatser valdes fram. Syftet med urvalets tre olika webbsidor är att en stor stad, en mindre stad samt en liten kommun ska analyseras.

Se mer om [Göteborgs Stad](https://goteborg.se/ "Göteborgs Stad")                                    
Se mer om [Karlstads Kommun](https://karlstad.se/ "Karlstads Kommun")                                  
Se mer om [Bengtsfors Kommun](https://www.bengtsfors.se/ "Bengtsfors Kommun")

Metod
-----------------------

De tre utvalda webbsidorna undersöktes med två olika verktyg, både i desktop samt mobiletop läge. All insamlad data sparades ned i ett kalkylark. 
Skärmbild, mätningar samt resultat och diskussion gjordes för varje webbsida.
Chrome DevTools, den inbyggda funktionen i Google Chrome användes för att undersöka webbsidans hastighet.
Google PageSpeed Insights användes också för att hämta ut mätvärden i samma syfte som networks-fliken i DevTools. 
Google Kalkylark användes för att spara ner mätningarna från undersökningen.

Resultat
-----------------------


<h3>Göteborgs Stad</h3>

![Göteborgs Stad](%base_url%/image/goteborgs_stad.png){.goteborg}

Göteborgs Stads webbplats hade högst prestanda både i mobiletop och desktop. 

<h4>förbättring mobil:</h4>
- skicka bilder i mordernare bildformat 1,35s
- reducera JavaScript som inte används 1,20s
- ta bort resurser som blockerar renderingen 0,87s
- koda bilder effektivt 0,75s
- reducera CSS som inte används 0,30s

<h4>förbättring dator:</h4>
- ta bort resurser som blockerar renderingen 0,26s
- använd bilder med rätt storlek 0,25s
- skicka bilder i mordernare bildformat 0,25s
- reducera JavaScript som inte används 0,21s          


<h3>Karlstads Kommun</h3>

![Karlstads Kommun](%base_url%/image/karlstads_kommun.png){.karlstad}

<h4>förbättring mobil:</h4>
- använd bilder med rätt storlek 2,13s besparing
- skicka bilder i mordernare bildformat 1,08s besparing
- ta bort resurser som blockerar renderingen 0,77s besparing
- reducera CSS som inte används 0,71s besparing
- reducera JavaScript som inte används 0,18s besparing

<h4>förbättring dator:</h4>
- ta bort resurser som blockerar renderingen 0,25 s besparing
- använd bilder med rätt storlek 0,20s besparing


<h3>Bengtsfors Kommun</h3>

![Bengtsfors Kommun](%base_url%/image/bengtsfors_kommun.png){.bengtsfors}

<h4>förbättring mobil:</h4>
- skjut upp inläsningen av bilder som inte visas på skärmen 2,28s besparing
- skicka bilder i mordernare bildformat 2,11s besparing
- ta bort resurser som blockerar renderingen 1,38s besparing
- reducera Javascript som inte används 0,33s
- reducera CSS som inte används 0,16s

<h4>förbättring dator:</h4>
- skicka bilder i mordernare bildformat 1,32s
- koda bilder effektivt 0,76s
- ta bort resurser som blockerar renderingen 0,44s


<h3>Google Kalkylark</h3>

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQksyhqHR85tw7DMMcgX24vmA2lHweSszCn2I_QsituVxQPxu_jW9VLrC_8EA-li1FMTIFHQefzSPba/pubhtml?widget=true&amp;headers=false" class="loadtable" title="myFrame"> frame body </iframe>


Analys
-----------------------

Den vanligaste förbättringsåtgärden för de utvalda webbplatserna verkar vara att ta bort resurser som blockerar renderingen, den möjligheten finns för alla tre webbsidorbåde i mobiletop och desktop. Besparingen varierar mellan 0,25s till 1,38s för webbsidorna. Att skicka bilder i modernare bildformat verkar också vara en förbättringsmöjlighet för sidorna, besparingen blir även större. 
I kalkylen kan man se att Karlstads Kommun ligger sämre till jämfört med de andra två webbsidorna, och mycket av problematiken ligger i att använda bilder med rätt storlek och då i detta fall spara 2,13s vilket skulle gjort en ganska stor skillnad. Mycket handlar om bildernas anpassning och med detta resultat kan man dra en slutsats om att bilder och medier tar upp mycket utrymme och därmed tar länge tid att ladda upp.

Tanken med urvalet var att se om det fanns skillnader i webbplatsens utveckling och kvaliteér beroende på hur stor kommunen var. Att Sveriges näst största stad skulle ha mer resurser för fler/bättre webbutvecklare än vad en kommun på ca 10 000 invånare har.

<h3>Rangordning i analysen:</h3>

1. Göteborgs Stad
2. Bengtsfors Kommun
3. Karlstads Kommun                                  

Göteborgs Stad vinner i den bedömning som gjorts. Webbplatsen hade bäst prestanda både i desktop-läge samt mobiletop-läge, med 98 i prestanda, 100 i tillgänglighet, 100 i bästa metoder samt 100 i SEO (PageSpeed Insights). 

Det kan ta mycket längre tid på flera webbsidor att ladda alla resurser, därför är det "Contentful Paint" som är det viktiga, alltå hur lång tid det tagit för det nödvändigaste att laddats klart. Alla sidor i analysen var under 2 sek i laddningstiden, även om Karlstads Kommun var lite efter de andra två är det inget stort fel.

Referenser
-----------------------

PageSpeed Insights


Övrigt
-----------------------

Denna rapport skrevs av Saga Eriksson.