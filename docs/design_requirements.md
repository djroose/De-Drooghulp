## Overzicht van Design Requirements
|| Status || ❌ niet voldaan || ⚠️ gedeeltelijk voldaan || ✅ voldaan ||

| ID | Design Requirement | Source | Status |
| --- | --- | --- | --- |
| **Interface Layout** | | | |
| **1.1** | Duidelijke voorkeuroptie als advies met doorklik optie voor meer info | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **1.2** | Een antwoord op de vraag van de gebruiker kunnen bieden in minder dan 3 kliks | [Document 2](../reports%20and%20protocols/Document%202%20Analyse%20testen%20%26%20design%20requirments%20.pdf) | ✅ |
| **1.3** | Absolute voorrang geven aan het vinden van info en functies: de droogtijd, het weer en de timer | [Document 2](../reports%20and%20protocols/Document%202%20Analyse%20testen%20%26%20design%20requirments%20.pdf) | ✅ |
| **1.4** | Informatie consistent weergeven via één centrale schermindeling (geen versnippering over meerdere schermen) | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **1.5** | Duidelijke en permanente navigatie zodat de gebruiker na doorklikken steeds het hoofdscherm kan terugvinden | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **1.6** | Onboarding-scherm bij eerste gebruik met persoonlijke configuratievragen (vaste wasdag, beschikbare droogopties, zonnepanelen, app-gebruik, gezinsgrootte, locatie apparaat) | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ⚠️ |
| **Visuele Rangschikking** | | | |
| **2.1** | De drie droogopties worden weergegeven met een drievoudige kleurcodering: Groen (Aanbevolen), Oranje (Mogelijk), Rood (Afgeraden) | [Rapport Wave 2](../reports%20and%20protocols/Officieel_Rapport_Test_Wave_2.pdf) | ✅ |
| **2.2** | De aanbevolen optie is prominent gemarkeerd als "Aanbevolen" zodat keuzestress wegvalt | [Rapport Wave 2](../reports%20and%20protocols/Officieel_Rapport_Test_Wave_2.pdf) | ✅ |
| **2.3** | Effect van 'Snelste optie' op overige data is duidelijk visueel gecommuniceerd zodat de gebruiker begrijpt wat er wijzigt | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **Data Hiërarchie** | | | |
| **3.1** | De verwachte droogduur in uren/minuten wordt als meest prominente waarde getoond per droogoptie | [Rapport Wave 1](../reports%20and%20protocols/Officieel_rapport_test_wave_1.pdf) | ✅ |
| **3.2** | Extra info (onderbouwing van het advies) wordt weergegeven na doorklikken, niet op het hoofdscherm | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **3.3** | Secundaire omgevingsdata (tijd, locatie, weericon, temperatuur) worden weergegeven in een hoekje voor geloofwaardigheid | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **3.4** | Extra info over de opties is vindbaar op vraag van de gebruiker maar standaard verborgen voor overzicht en eenvoud | [Document 2](../reports%20and%20protocols/Document%202%20Analyse%20testen%20%26%20design%20requirments%20.pdf) | ✅ |
| **3.5** | Kostenweergave is abstract (bv. "Goedkoopste keuze" of kleurindicatie) en niet als exact eurobedrag, zeker voor huishoudens met zonnepanelen | [Rapport Wave 2](../reports%20and%20protocols/Officieel_Rapport_Test_Wave_2.pdf) | ✅ |
| **3.6** | Luchtvochtigheid en ruwe sensordata worden verwerkt in het advies maar niet standaard prominent getoond | [Rapport Wave 2](../reports%20and%20protocols/Officieel_Rapport_Test_Wave_2.pdf) | ✅ |
| **Interface Stofkeuze** | | | |
| **4.1** | De gebruiker kan een wassoort selecteren op basis van droogsnelheid: lichte stoffen, gewoonlijke stoffen en zware stoffen | [Rapport Wave 2](../reports%20and%20protocols/Officieel_Rapport_Test_Wave_2.pdf) | ✅ |
| **4.2** | Stofkeuze past het droogadvies en de timer automatisch aan wanneer de geselecteerde optie wijzigt | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **Timer** | | | |
| **5.1** | De timer is instelbaar én uitzetbaar door de gebruiker | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **5.2** | De timer past zich automatisch aan wanneer de geselecteerde droogoptie of stofkeuze wijzigt | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **5.3** | Tijdsaanduidingen in de interface maken ondubbelzinnig duidelijk of het een aftelling of een starttijdstip betreft (bv. "nog 20 min" vs. "om 20u") | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **Dynamische Updates** | | | |
| **6.1** | De droogdata en adviezen wijzigen dynamisch mee met veranderingen in het weer | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ⚠️ |
| **6.2** | Het systeem stuurt een extra melding bij een significante weerwijziging (bv. regen of daluur) | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ⚠️ |
| **6.3** | Het weerbericht toont expliciet de "tijd tot regen" en zonneschijnvenster voor buitendrogen | [Rapport Wave 2](../reports%20and%20protocols/Officieel_Rapport_Test_Wave_2.pdf) | ⚠️ |
| **Meldingen & App** | | | |
| **7.1** | Het systeem stuurt proactieve notificaties naar de smartphone (bv. "Morgen is ideaal voor de was") | [Develop 3 CMF](../reports%20and%20protocols/Develop_3_-_CMF_onderzoek.pdf) | ⚠️ |
| **7.2** | De app stuurt een completion alert wanneer de droogtimer afloopt | [Develop 3 CMF](../reports%20and%20protocols/Develop_3_-_CMF_onderzoek.pdf) | ⚠️ |
| **7.3** | Meldingsteksten zijn kort, helder en niet betuttelend van toon | [Interview Analyse](../reports%20and%20protocols/Interview_analyse_docx.pdf) | ✅ |
| **Terminologie** | | | |
| **8.1** | Gebruik van eenduidige termen zoals "Binnen" of "Over" in plaats van het verwarrende "In" | [Rapport Wave 2](../reports%20and%20protocols/Officieel_Rapport_Test_Wave_2.pdf) | ✅ |
| **8.2** | Gebruik van "gemiddelde stof" in plaats van "gewoonlijk" voor de middelste stofcategorie | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **8.3** | Regenvenster wordt weergegeven als "deadline" (tot wanneer het droog blijft) in plaats van "duur van de bui" | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **8.4** | Ventilatie-/muffe-geurwaarschuwingen gebruiken begrijpelijke, niet-technische bewoordingen | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **Iconografie** | | | |
| **9.1** | Gebruik van het gevalideerde 'wasrek-icoon' voor binnendrogen in plaats van een huisje | [Rapport Wave 2](../reports%20and%20protocols/Officieel_Rapport_Test_Wave_2.pdf) | ✅ |
| **9.2** | Locatie-icoon met weerinfo en temperatuur reflecteert de werkelijke lokale omstandigheden (geloofwaardigheid) | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ✅ |
| **CMF & Fysiek Product** | | | |
| **10.1** | Behuizing in matwitte hoogwaardige kunststof (ABS) die visueel aansluit bij bestaand witgoed in de wasruimte | [Develop 3 CMF Analyse](../reports%20and%20protocols/Develop_3_-_CMF_analyse.pdf) | ✅ |
| **10.2** | Oppervlak heeft een gladde, matte finish (micro-fuzzy skin of vonkerosie) die stof en vingerafdrukken optisch wegwerkt | [Develop 3 CMF Analyse](../reports%20and%20protocols/Develop_3_-_CMF_analyse.pdf) | ✅ |
| **10.3** | Vormtaal is vloeiend en organisch (geen rigide hoeken) om technologische aanwezigheid te verzachten zonder authenticiteit te verliezen | [Develop 3 CMF Analyse](../reports%20and%20protocols/Develop_3_-_CMF_analyse.pdf) | ✅ |
| **10.4** | Wandmontage op een hoogte van ca. 150 cm, 10° naar boven gekanteld, voor optimale leesbaarheid rechtstaand | [Document 2](../reports%20and%20protocols/Document%202%20Analyse%20testen%20%26%20design%20requirments%20.pdf) | ✅ |
| **Toegankelijkheid & Toekomst** | | | |
| **11.1** | Statuscommunicatie steunt niet uitsluitend op kleur: redundante signalen (vorm, tekst, symbool) ondersteunen kleurenblinde gebruikers | [Kritische Reflectie](../reports%20and%20protocols/) | ❌ |
| **11.2** | Systeem voorziet een offline back-upfunctie voor omgevingen zonder stabiele internetverbinding (bv. kelder) | [Kritische Reflectie](../reports%20and%20protocols/) | ❌ |
| **11.3** | VUI (voice interface) wordt onderzocht als bijkomende interactiemogelijkheid voor handsfree gebruik | [Analyse Dev 1](../reports%20and%20protocols/Analyse%20develop%201.pdf) | ❌ |
```

