# Bill of Materials (BOM) - Project Vochtigheidsmeting

Dit document bevat de volledige lijst met componenten, specificaties en de geschatte kosten voor de Raspberry Pi opstelling.

## Projectonderdelen
* Vochtigheidssensor (DHT22)
* Raspberry Pi
* 3x RGB Leds
* Touchscreen scherm
* Plastieken behuizing
* Elektrische kabels & GPIO-jumperdraden
* Voorschakelweerstanden
* Voeding (adapter)
* DSI-lintkabel

## BOM Overzichtstabel

| Component | Omschrijving & Specificaties | Leverancier / Link | Prijs (Schatting) |
| :--- | :--- | :--- | :--- |
| **Raspberry Pi Kit** | Raspberry Pi 4 Model B met voeding | [SOS Solutions](https://www.sossolutions.nl/raspberry-pi-5-1gb-starter-kit-compleet) | € 70,00 - € 80,00 |
| **Touchscreen** | Officieel Raspberry Pi 7-inch Display (DSI) | [Raspberry Store](https://www.raspberrystore.nl/PrestaShop/nl/beeldschermen/620-pibow-frame-voor-de-raspberry-pi-touch-display-2-noirblack-0769894026380.html) | € 15,00 - € 20,00 |
| **Vochtigheidssensor**| DHT22 (AM2302) - Hoge nauwkeurigheid | Gotron | € 15,00 - € 20,00 |
| **Behuizing** | Plastieken behuizing (Productiemethode n.t.b.) | - | ~ € 5,00 |
| **RGB Leds** | 3x Diffuse RGB LED 5mm (Common Cathode) | Kiwi Electronics | € 0,50 - € 5,00 |
| **Voeding** | Inbegrepen in de Pi-kit | - | - |
| **DSI-lintkabel** | Inbegrepen bij het scherm | - | - |
| **Jumperdraden** | Set Male/Female & Female/Female | Gotron | € 4,00 - € 7,00 |
| **Weerstanden** | Set voorschakelweerstanden (o.b.v. LED specs) | OpenCircuit / HobbyElectronica | € 1,00 - € 5,00 |
| **TOTAAL** | | | **€ 111,50 - € 142,00** |


* **DHT22:** Vereist een 3.3V of 5V verbinding en één GPIO datapin (met eventueel een 10k ohm pull-up weerstand).
* **RGB Leds:** Worden aangesloten op PWM-geschikte GPIO pinnen voor kleurfiltering.