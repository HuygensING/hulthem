# Installatie Repertorium van Hulthem
## Installation docs (in Dutch) for the "Repertorium van Hulthem" Virtualbox and CD images

* Download en installeer Virtualbox via https://www.virtualbox.org volgens de instructies die VirtualBox zelf voor jouw besturingssysteem aangeeft.

* Download de virtuele machine waarop het Repertorium is voorgeïnstalleerd via
    http://huygens.knaw.nl/Hulthem/Win7%2032-bit%20-%20Hulthem.ova

* Download het `iso` image van de CDROM van het Repertorium via
    http://huygens.knaw.nl/Hulthem/hulthem.iso
    
* Bewaar dit `iso` image ergens op een plek op je computer die je nog kunt terugvinden en onthoud deze locatie

* Open de virtuele machine (dubbelklik op icoon, of rechtermuis en openen kiezen)

VirtualBox zal nu dit virtuele image gaan importeren om het klaar voor gebruik te maken. Hierbij kan het volgende schermpje getoond worden.

![Import settings](https://user-images.githubusercontent.com/2081891/28613496-cbf6b1ac-71f2-11e7-9baa-bd72d4297652.png)

* Klik op `Import` om het importeren te starten. Tijdens het importeren wordt de voortgang getoond:

![Importeren van het image](https://user-images.githubusercontent.com/2081891/28613495-cbf6278c-71f2-11e7-9010-5fe145250dd2.png)

Na de import is de virtuele machine beschikbaar. Links in de lijst staat deze benoemd (`Win7 32-bit - Hulthem`), rechts staan instellingen voor deze virtuele machine.

![Overzicht beschikbare virtuele machines](https://user-images.githubusercontent.com/2081891/28613498-cbf854bc-71f2-11e7-8ac7-7c29c8f2367a.png)

De software van het Repertorium vereist dat de CDROM "in de lade" ligt. We gaan dit vertalen naar de wereld van een virtuele machine, waar immers geen fysieke CDROM speler is.

In de `Storage` settings aan de rechterkant, is te zien dat de CDROM lade leeg is (`[Optical Drive] Empty`)

![CDROM lade is leeg](https://user-images.githubusercontent.com/2081891/28613494-cbf5cabc-71f2-11e7-8cee-1f8c71598fdc.png)

* Klik op `[Optical Drive] Empty` en selecteer de locatie van de CDROM `iso` die je eerder hebt opgeslagen en onthouden. De `Storage` settings laten nu zien dat de CDROM lade is "gevuld" met het `iso` bestand dat de inhoud van de CD bevat.

![CDROM lade is gevuld](https://user-images.githubusercontent.com/2081891/28613499-cbfa8db8-71f2-11e7-9a91-29256c2259c7.png)

De virtuele machine kan nu gestart worden.

* Dubbelklik op de virtuele machine aan de linkerkant `Win7 32-bit - Hulthem`, of selecteer deze virtuele machine en gebruik de groene `Start` knop boven in beeld.

Er verschijnt een nieuw scherm waarin eerst de virtuele machine wordt opgestart, die Windows zal draaien en daarin het `Repertorium van Hulthem` zal opstarten.

![Repertorium wordt gestart](https://user-images.githubusercontent.com/2081891/28614827-62f0acf8-71f7-11e7-91be-72568a0a0710.png)

## Afsluiten van de virtuele machine
Na afloop van een sessie werken met het Repertorium kan de gehele virtuele machine worden afgesloten. Sluit hiertoe het venster waarin de virtuele machine draait af met het betreffende 'kruisje'. M.a.w. sluit niet de applicatie af binnen het venster van de virtuele machine, maar sluit het venster van de virtuele machine zelf. Zodra je dit doet, komt er een venster met de vraag hoe rigoreus je de virtuele machine wilt afsluiten.

![Virtuele machine afsluiten](https://user-images.githubusercontent.com/2081891/28613500-cc0dad26-71f2-11e7-89d5-e789f38dee09.png)

*  Kies de optie `Power off`. Dat is het virtuele machine equivalent van de stekker uit het stopcontact trekken.

## Opstarten Repertorium in volgende sessies
Bij vervolgsessies kan het zijn dat de Windows installatie "klaagt" over onjuist afsluiten, of over verlopen houdbaarheid, of dat er updates gedraaid moeten worden. Al deze meldingen kunnen worden weggeklikt. Omdat de virtuele machine telkens weer vanuit dezelfde toestand wordt opgestart hoeft er niets te worden bijgewerkt en er gaat ook niets "stuk" met de `Power Off` optie.
