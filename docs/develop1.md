## Develop 1

Tijdens de Develop-fase van het ontwerpproces is de interactie met het product tot in detail uitgediept. Het doel was om diepgaand inzicht te verkrijgen in de resterende frictiepunten binnen het ontwerp, zodat deze systematisch konden worden geëlimineerd. Door een combinatie van kwantitatieve analyses, visuele mapping en technische verkenningen is het concept van De Drooghulp verfijnd tot een gebruiksvriendelijke en technisch haalbare oplossing. De onderstaande tools en methodieken vormden de kern van deze Develop-fase.   


### 1. Top task analysis

De functies van het product zijn op een Long Neck / Long Tail grafiek geplaatst om inzicht te krijgen in welke functies het belangrijkste zijn. Deze analyse helpt om de focus van het product te bepalen op de "kerntaken" (zoals de beste droogoptie en weersvoorspelling) die de meeste waarde leveren voor de gebruiker.

<p align="center">
  <img src="img/Top Task Analysis.png" width="100%">
</p>

### 2. User flows

In de User Flows zijn de specifieke doelen van de gebruiker en de benodigde stappen daarnaartoe gemapt. Dit proces was essentieel om frictiepunten in het ontwerp te ontdekken. Voor elk knelpunt zijn er gerichte oplossingen gezocht, waardoor de interface van De Drooghulp intuïtief blijft en de gebruiker gemakkelijk tot zijn doel komt.

<p align="center">
  <img src="img/User Flows.png" width="100%">
</p>

### 3. Story Board

In deze stap is het storyboard verder verfijnd om de logische opeenvolging van handelingen te visualiseren. Dit omvat de notificatie bij een voltooide wasbeurt, de interactie met de 'Drooghulp'-interface voor een optimaal droogadvies, en de feedbackloop met de timer die aangeeft wanneer de was buiten droog is.

<p align="center">
  <img src="img/Storyboard develop.png" width="100%">
</p>

### 4. Customer Journey

In het ontwerpproces is het "Was Ritueel" visueel in kaart gebracht middels een Customer Journey. Hiermee zijn de acties, emoties en motivaties van de gebruiker gedurende het gehele proces (van awareness tot het verzamelen van de droge was) inzichtelijk gemaakt.

Door deze reis stap voor stap te analyseren, zijn de kritieke pijnpunten blootgelegd, met name tijdens de wachtmomenten en de onzekerheid over droogtijden. Dit vormde de basis voor het definiëren van de functionele vereisten voor De Drooghulp, waarbij de focus ligt op het wegnemen van frustratie door proactieve meldingen en nauwkeurige voorspellingen.

<p align="center">
  <img src="img/Costumer Journey.png" width="100%">
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
  

### 8. Secondary research 

Naast het softwarematige onderzoek en de functionele analyses, hebben we een technische verkenning uitgevoerd naar de hardware voor het prototype van De Drooghulp. Hierbij zijn verschillende microcontrollers en computerplatforms onderzocht, waaronder de mogelijkheden van Arduino. Uiteindelijk is de keuze gevallen op een Raspberry Pi. De belangrijkste reden hiervoor is de behoefte aan een krachtig platform dat simultaan een groot aantal verschillende sensoren kan aansturen die essentieel zijn voor de nauwkeurigheid van het droogadvies. Voor het prototype willen we de volgende data integreren: 
- Temperatuur en Luchtvochtigheid: Voor het berekenen van de verdampingstijd. 
- Beweging: Om te detecteren of de was buiten hangt of binnengehaald wordt. 
- Geluid: Voor mogelijke feedback of statusmeldingen van wasmachines. 
- Display: De Raspberry Pi maakt het mogelijk om direct een scherm aan te sluiten, wat cruciaal is voor de UX.