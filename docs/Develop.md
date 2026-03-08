## Develop
In deze fase van het ontwerp proces. Werd het gebruik van het product verder uitgediept om nog extra inzicht te krijgen in de fricties van het ontwerp van het product zodat deze zo goed mogelijk kunnen weg gewerkt worden. De tools hieronder werden gebruikt.


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

### 6. Interviews

Er werd nieuwe prototype gemaakt aan de hand van een scherm. Het prototype focust op een betere info architectuur, lay out en gebruiksgemak. 
Dit prototype werd getest aan de hand van interviews bij gebruikers.

  * [Protocol](../reports%20and%20protocols/Protocol%20test%203.pdf)

### 7. secondary research 

Naast het softwarematige onderzoek en de functionele analyses, hebben we een technische verkenning uitgevoerd naar de hardware voor het prototype van De Drooghulp. Hierbij zijn verschillende microcontrollers en computerplatforms onderzocht, waaronder de mogelijkheden van Arduino. Uiteindelijk is de keuze gevallen op een Raspberry Pi. De belangrijkste reden hiervoor is de behoefte aan een krachtig platform dat simultaan een groot aantal verschillende sensoren kan aansturen die essentieel zijn voor de nauwkeurigheid van het droogadvies. Voor het prototype willen we de volgende data integreren: Temperatuur en Luchtvochtigheid: Voor het berekenen van de verdampingstijd. Beweging: Om te detecteren of de was buiten hangt of binnengehaald wordt. Geluid: Voor mogelijke feedback of statusmeldingen van wasmachines. Display: De Raspberry Pi maakt het mogelijk om direct een scherm aan te sluiten, wat cruciaal is voor de ultra eenvoudige UX en het direct beantwoorden van de hoofdvraag van de gebruiker.