## Develop 2

In deze fase verschuiven we de focus van de functionele architectuur ("hoe het werkt") naar de menselijke ervaring ("hoe het voelt"). Het doel is om een frictieloze usability te garanderen door middel van een onderbouwd ergonomisch ontwerp en een interactief, testbaar prototype. 


### 1. Antropometrie (The Body)

Om een inclusief ontwerp te garanderen voor zowel kleine als grote gebruikers, hanteren we de strategie "Design for the Range" (P5 vrouw tot P95 man).
Touchpoints:
•	Interactieve knoppen: Afmetingen zijn gebaseerd op de P95 breedte van de mannelijke duim om het "fat finger"-syndroom te voorkomen.
•	Behuizing & Montage: De vorm van de achterplaat suggereert intuïtief de wandmontage (Affordance).
•	Display: Geplaatst op een hoogte die rekening houdt met de ooghoogte van de P5 vrouw en P95 man.
Methode:
De fysieke plaatsing wordt geëvalueerd via een antropometrische analyse:
•	Centrale hoogte: Het scherm wordt op circa 150 cm geplaatst om bukken of extreem omhoog kijken te voorkomen.
•	Zichthoek: Het scherm wordt 10° naar boven gekanteld om een optimale kijkhoek van 15° tot 30° onder de horizontale ooglijn te faciliteren.
•	Reikwijdte: Alle interactieve elementen bevinden zich binnen de functional reach van een P5-vrouw.




### 2. Cognitieve & Sensoriële Ergonomie (The Senses)

We passen theoretische kaders toe om de mentale inspanning (cognitive load) te minimaliseren.
•	7 Stages of Action (Don Norman): We overbruggen de kloof van executie door sterke Signifiers (knoppen zien er klikbaar uit door schaduwen) en de kloof van evaluatie door directe Feedback binnen 100ms na interactie.
•	GESTALT-wetten: Toepassing van de wet van nabijheid (groeperen van sensordata) en de wet van gelijkenis (uniforme kleuren voor actieknoppen) voor snelle visuele scanning.
•	Informatieverwerking: Gebruik van Chunking (data verdelen in 'huidig', 'verwachting' en 'conclusie') en Recognition over Recall (het systeem rekent, de gebruiker kiest).



### 3. Onderzoek vorige interface

Om een beter beeld te krijgen van de werking van de vorige interface hebben we visueel de werking in kaart gebracht. Dit gaf ons het inzicht dat veel info te ver verstopt zat. 


<p align="center">
  <img src="img/interface wave 3 uitgezet.png" width="100%">
</p>

### 4. Prototyping

Om meerdere soorten interface indelingen te testen maakten we 2 nieuwe interactieve interfaces en gaven we de interface van develop 1 een upgrade. Deze interfaces zijn uit te testen met onderstaande links.

<p align="center">
  <img src="img/Schermafbeelding 2026-04-12 210827.png" width="100%">
</p>


### 5. Benchmark analyse

Er is een specifieke benchmark uitgevoerd naar bestaande droog-apps om te bepalen waar huidige oplossingen tekortschieten. Hieruit bleek dat apps zoals Washcast en Drying Buddy vooral focussen op buiten drogen. Dit bevestigde de noodzaak voor De Drooghulp om in te zetten op ontbrekende functies zoals indoor drying intelligence en smart home integratie.

Documentatie:
* Benchmarks (N=3)
  * [Protocol](../reports%20and%20protocols/Protocol%20Benchmark%20analyse%20voor%20Laundry%20Drying%20Apps.pdf)
  * [Rapport](../reports%20and%20protocols/Analyse%20Benchmark%20Analyse%20Laundry%20Drying%20Apps.pdf)

### 6. Prototype

Na het verzamelen van diepgaande inzichten in de gebruiker en de tekortkomingen van de huidige markt, is een fysiek prototype ontwikkeld. Dit prototype vormt de brug tussen de digitale intelligentie en de fysieke wasruimte. De focus ligt hierbij op het presenteren van een centrale interface die direct bij de wasmachine of droogkast geplaatst wordt, met een geoptimaliseerde informatiearchitectuur en lay-out voor maximaal gebruiksgemak.

Prototype:

    https://www.figma.com/make/3kj79Z1ZVnqXamjAskY5oq/Mobiel-startscherm-slimme-was-assistent?fullscreen=1&t=N7b5oIxtJ4CzQWrN-1 


<p align="center">
  <img src="img/Prototype wave 3.png" width="100%">
</p>

### 7. Interviews & Gebruikerstesten

Om de effectiviteit van de interface te valideren, zijn er kwalitatieve interviews en gebruikstesten uitgevoerd met het fysieke prototype. Testpersonen werden in een realistisch scenario geplaatst waarbij zij het volledige droogritueel doorliepen. Hierbij werd gebruikgemaakt van een 'Wizard of Oz'-opstelling (met externe speakers en sms-meldingen) om de interactieve ervaring van het gelaagde informatiemodel en de proactieve meldingen te simuleren. Dit gaf diepgaand inzicht in hoe gebruikers de informatie interpreteren en of het apparaat op de juiste momenten de gewenste ondersteuning biedt.

Rapports(N=4):
  * [Protocol](../reports%20and%20protocols/Protocol%20test%203.pdf)
  * [Analyse](../reports%20and%20protocols/Analyse%20develop%201.pdf)
  

### Kritische Reflectie

Naast het softwarematige onderzoek en de functionele analyses, hebben we een technische verkenning uitgevoerd naar de hardware voor het prototype van De Drooghulp. Hierbij zijn verschillende microcontrollers en computerplatforms onderzocht, waaronder de mogelijkheden van Arduino. Uiteindelijk is de keuze gevallen op een Raspberry Pi. De belangrijkste reden hiervoor is de behoefte aan een krachtig platform dat simultaan een groot aantal verschillende sensoren kan aansturen die essentieel zijn voor de nauwkeurigheid van het droogadvies. Voor het prototype willen we de volgende data integreren: 
- Temperatuur en Luchtvochtigheid: Voor het berekenen van de verdampingstijd. 
- Beweging: Om te detecteren of de was buiten hangt of binnengehaald wordt. 
- Geluid: Voor mogelijke feedback of statusmeldingen van wasmachines. 
- Display: De Raspberry Pi maakt het mogelijk om direct een scherm aan te sluiten, wat cruciaal is voor de UX.