# Recovery Winch — Handleiding

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

Voor het pakket **1.0.0.2** uit [deze release](https://github.com/dafke1305/FS25_RecoveryWinch/releases/tag/v1.0.0.2). Deze instructies horen bij die ZIP, niet bij een andere build met hetzelfde versienummer.

## Installatie

1. Download **FS25_RecoveryWinch.zip** onder Assets van de release. Behoud de bestandsnaam en pak de ZIP niet uit. De automatische GitHub Source code-archieven zijn niet de mod.
2. Plaats de ZIP in de ingestelde FS25-modsmap (op Windows gewoonlijk `Documents\My Games\FarmingSimulator2025\mods`) en schakel de mod in vóór het laden van de savegame. Deze scriptmods zijn voor PC/Mac.
3. Server en alle multiplayerclients moeten **dezelfde ZIP** hebben, niet alleen hetzelfde versienummer. Sluit het spel/stop de server en maak vóór bijwerken een saveback-up.

## Geschikt bergingsmaterieel kopen

- Configureer een geschikte auto, pickup, vrachtwagen, laadvloer of bosbouwforwarder met een lier in de winkel/werkplaats. Beschikbaarheid hangt af van voertuigcategorie, bevestigingspunten en laadvloerdefinities.
- Koop voor een trekker de aparte **categorie 2-driepuntsbergingslier** onder **Gewichten**. Die weegt 220 kg, heeft geen aftakas nodig en past op een geschikte voor- of achterhef. De hef zelf is niet automatisch een kabelbevestigingspunt.
- Een lier kost 1.500 inclusief 20 meter kabel en één herbruikbaar los sleepoog voor de boerderij. Kabelkeuze: 20 tot 50 meter in stappen van 5 meter; extra kabel kost 250 per meter.
- Gemonteerde lieren bieden waar beschikbaar verstelling naar voren/achteren en omhoog/omlaag. De aparte driepuntslier heeft een vaste montagepositie.

## Een voertuig bergen

1. Zet een passend liervoertuig op stabiele grond en lijn het uit met de trekrichting. Gebruik indien nodig stilstaand de bergingsparkeerrem.
2. Pak te voet bij de lier de kabel op via de contextactie. Standaard: **Y**.
3. Loop naar een geschikte staande boom, een herkend bergingspunt van een voertuig of een ondersteunde vrije disselkoppeling. Gebruik de F1-bevestigingsactie voor het gemarkeerde doel.
4. Heeft een auto/pickup/vrachtwagen geen geschikt punt, monteer dan te voet met **Alt+E** het losse sleepoog. Het doelvoertuig hoeft geen eigen lier te hebben gekocht. Voertuigen van andere boerderijen kunnen ook worden geborgen.
5. Gebruik de native in-/uitlierbediening uit F1 of **Besturing**. Maak na de berging de verbinding los via de contextactie.

## Bediening

| Actie | Standaard/context |
| --- | --- |
| Kabel oppakken / loslaten | **Y**, te voet nabij de lier |
| Grondanker plaatsen / losmaken | **Ctrl+G**, tijdens besturen van een geschikt liervoertuig |
| Bergingsparkeerrem | **Ctrl+B**, geschikt voertuig; eerst stoppen |
| Los sleepoog plaatsen / verwijderen | **Alt+E**, te voet nabij geschikt doel |
| Hoogte / diepte van oog tijdens positioneren | **Alt+Omhoog/Omlaag** / **Alt+Links/Rechts** |
| Oogpositie bevestigen / annuleren | **Alt+C** / **Alt+Backspace** |
| Bevestigen, losmaken, in-/uitlieren | Native contextacties; volg F1 en je actuele toetsinstellingen |

Wordt het grondanker geweigerd, zoek dan vrije ruimte en een geschikte positie in plaats van herhaald in een obstakel te plaatsen.

## Laadvloeren, grenzen en opslaan

Laat geschikte oprijplaten zakken en lijn het doel ongeveer recht achter de platen uit. De naar achter gerichte laadlier kan een onbemand voertuig stuur-/remhulp geven, zichtbaar als een zittende helper. Die hulp **start geen motor en geeft geen gas**: de lier levert de trekkracht. Zet het geladen voertuig vast met de passende uitrusting van de transporter.

Grip, botsingen, bewegende vloeren, afmetingen en gewichtsverdeling blijven bepalend. Een lichte bergingsauto kan in deze release naar een zwaar doel schuiven of weinig druk op de vooras krijgen. Er is geen massaverhoudingspopup die zware lasten automatisch weigert. Gebruik materieel dat bij de werkelijke last past.

Gekochte uitrusting en winkelconfiguraties worden opgeslagen. Kabelverbindingen, grondankers en gemonteerde losse sleepogen zijn tijdelijk; verbind opnieuw na het laden van een save.

Ontbreekt een optie/actie, controleer dan of de lier gekocht is, het juiste werktuig geselecteerd is, je dichtbij staat en het doel wordt ondersteund. Eigen voertuigscripts en bewegende/kantelende vloeren kunnen extra compatibiliteitswerk vereisen. Beheerdersschakelaars voor compatibiliteit/debug staan onder **ESC > Spelinstellingen**, vereisen een in-game serverbeheerder en garanderen geen werking met ieder aangepast voertuig.

## Hulp vragen

Gebruik [het bug-/supportformulier van deze mod](https://github.com/dafke1305/FS25_RecoveryWinch/issues/new/choose). Vermeld release/ZIP, FS25- en mapversie, singleplayer/host/client/dedicated, stappen, tijdstip en het volledige clientbestand `log.txt`; bij een dedicated-serverprobleem ook `server.log` van dezelfde sessie. Voeg relevante screenshots/video toe. De pakketcontrolecode staat in [PUBLICATION.json](PUBLICATION.json). Verwijder wachtwoorden, tokens en privéverbindingsgegevens vóór openbaar plaatsen. Gebruik voor privébewijs alleen een goedgekeurd privékanaal.

Standaardtoetsen zijn aanpasbaar. De actuele F1-hulp en je instellingen onder Besturing zijn leidend.
