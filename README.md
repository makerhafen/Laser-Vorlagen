<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

# Inhaltsverzeichnis  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Laser-Vorlagen](#laser-vorlagen)
- [Hilfreiche Software bzw. Online Resources](#hilfreiche-software-bzw-online-resources)
- [Schnittoptimierung](#schnittoptimierung)
- [Materialien](#materialien)
  - [NICHT geeignete Materialien (Gefährlich)](#nicht-geeignete-materialien-gef%C3%A4hrlich)
  - [Geeignete Materialien](#geeignete-materialien)
  - [Schlecht geeigenete Kunststoffe](#schlecht-geeigenete-kunststoffe)
- [Materialeinstellungen](#materialeinstellungen)
    - [Legende](#legende)
  - [Papier, Karton und Pappe](#papier-karton-und-pappe)
    - [Papier](#papier)
    - [Vollpappe](#vollpappe)
    - [Sonstiger Karton](#sonstiger-karton)
  - [Holz und Holzwerkstoffe](#holz-und-holzwerkstoffe)
    - [Sperrholz und Multiplex](#sperrholz-und-multiplex)
    - [Weitere Holzwerkstoffe](#weitere-holzwerkstoffe)
    - [Kunststoffe](#kunststoffe)
    - [Weiche Kunststoffe](#weiche-kunststoffe)
    - [Weitere Werkstoffe](#weitere-werkstoffe)
    - [Sonstige](#sonstige)
  - [Quellen für Vektor Grafiken](#quellen-f%C3%BCr-vektor-grafiken)
  - [Weitere Links](#weitere-links)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Laser-Vorlagen

Beispiele, Vorlagen und Krams den man mal lasern kann.
# Hilfreiche Software bzw. Online Resources

* [Slicer for Fusion 360](https://apps.autodesk.com/FUSION/en/Detail/Index?id=8699194120463301363&os=Win64&appLang=en)
* [Thingiverse](http://thingiverse.com/)
* [Instructables](http://www.instructables.com/)
* [DaFont](http://www.dafont.com/de/)
* Laser Cutter Designs zum Downloaden [Orbrary](https://obrary.com/collections/open-designs)
* Living Hinge (biegsames Holz) [Orbrary](https://obrary.com/products/living-hinge-patterns)

# Schnittoptimierung

* [SVGnest](http://svgnest.com/) - Online und kostenlos, funktioniert mit einfachen Polygonen sehr gut, bei komplexeren Formen und und Kurven, besonders mit konkaven Teilen dauert der Prozess sehr lange.
* [Deepnest](http://deepnest.io/) - Installation erforderlich - ist deutlich schneller als SVGnest, ein optimierter Export ist aber kostenpflichtig - man sieht aber in der Vorschau, wie die Teile positioniert wurden

# Materialien
**Die nachfolgende Liste wurde zum größten Teil von [Happylab](https://wiki.happylab.at/w/Main_Page) übernommen und muss noch erweitert bzw. angepasst werden.**

Keine unbekannten oder gefährlichen Materialien schneiden! Anleitung zum Identifizieren (z.B. Brandtest) von Kunststoffen: www.barthmann-recycling.de/files/erkennekunststoffe.pdf

Bitte die Leistung (Power) maximal auf 90% einstellen. 90% Power erzielt das selbe Ergebnis wie 100% Power, allerdings wird das Netzteil und die Röhre geschont und sind dadurch langlebiger.

## NICHT geeignete Materialien (Gefährlich)

| Material                                                     |  Abkürzung   |                 Handelsname                  | Anmerkung                                                    |
| ------------------------------------------------------------ | :----------: | :------------------------------------------: | ------------------------------------------------------------ |
| **Kunststoffe:**                                             |              |                                              |                                                              |
| Polyvinylchlorid                                             |     PVC      |                    Vinyl                     | erzeugt beim Schneiden/Gravieren Salzsäuredämpfe, chem. HCl  |
| Polyoxymethylen-Copolymer                                    |    POM-C     |                                              | Es gibt auch ein POM-H welches mit dem Laser Cutter geschnitten werden darf |
| Neopren (Chloropren-Kautschuk, auch Polychloropren oder Chlorbutadien-Kautschuk) |      CR      |                   Neopren                    | erzeugt beim Schneiden/Gravieren Salzsäuredämpfe, chem. HCl  |
| Polyvinylbutyrale                                            |     PVB      |                                              |                                                              |
| Aramide                                                      |  PPTA, PMPI  |              Kevlar, Nomex,...               | -> Cyanwasserstoff (Blausäure), chem. HCN                    |
| Polytetrafluoroethylene                                      |     PTFE     |                    Teflon                    | -> Es entsteht Flusssäure (HF), eine der potentesten Säuren überhaupt, COCl2? |
| Sämtliche Materialien die Epoxy-/Epoxid- oder Phenolharze enthalten |              |                   Bakelite                   | Gesundheitsschädliche Dämpfe und Rückstände (Benzene, Phenol, Formaldehyd)an den Schnittkanten [PDF](http://www.researchgate.net/publication/241122179_Feasibility_Study_on_Laser_Cutting_of_Phenolic_Resin_Boards) |
| Fluor-Kautschuk bzw. Fluorkarbon-Kautschuk                   | FPM bzw. FKM |    Viton®, Tecnoflon®, Fluorel®, Dai-el®     | enthält Fluor                                                |
| Kunstleder                                                   |              |                                              | Manche Kunstleder sind mit PVC, Nur Kunstleder mit PUR verwenden |
| **natürliche Materialien:**                                  |              |                                              |                                                              |
| Naturkautschuk                                               |              |                                              | Beschädigung der Optik durch Rußentwicklung                  |
| Latex                                                        |              |                                              | Beschädigung der Optik durch Rußentwicklung                  |
| Leder mit Chrom (IV)                                         |              |                                              | **Giftige Gase bzw. Partikel können entstehen** -> Es gibt z.B. natürlich gegerbtes Leder welches ohne Chrom gegerbt wird. |
| Metalle                                                      |              | Mangan, Chrom, Nickel, Kupfer, Cobalt, Blei, |                                                              |
| **sonstige Materialien:**                                    |              |                                              |                                                              |
| Berylliumoxide                                               |              |                                              | **hochgiftig**                                               |
| Sämtliche Materialien welche Halogene (Fluor, Chlor, Brom, Jod, Astatin) enthalten |              |                                              | Materialien mit dem Zusatz "Flammhemmend" haben oft Brom zugesetzt |
| Glasfaser bzw. Kohlenstofffaserverstärkte Platten            |              |       z.B. Leiterplatten, Carbonteile        | Diese bestehen meist aus Epoxidharzen, außerdem sehen die Schnittkanten furchtbar aus |
| Printplatten-Material (FR1/2/3/4/5)                          |              |                                              |                                                              |
| Kohlenstofffasern                                            |              |                    Carbon                    |                                                              |

## Geeignete Materialien

| Material                                 |     Abkürzung     |                         Handelsname                          | Anmerkung                                                    |
| ---------------------------------------- | :---------------: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| **Kunststoffe:**                         |                   |                                                              |                                                              |
| Polymethylmethacrylat                    |       PMMA        | Plexiglas, [Acryl](https://wiki.happylab.at/w/Acryl), Acrylglas, Schildermaterial aus dem Fabstore (=2-färbiges Acryl),... |                                                              |
| Polyethylene                             |        PE,        |                                                              | Schmilzt stark                                               |
| Polystyrol                               |        PS         |                                                              | Schnittkanten schmelzen stark bei dickeren sheets            |
| Extrudiertes Polystyrol                  |        XPS        |                       Depron, Styrodur                       |                                                              |
| Expandiertes Polystyrol                  |        EPS        |                           Styropor                           |                                                              |
| Polyimide                                |        PI         |                            Kapton                            |                                                              |
| Polyethylenterephthalate                 | PET, PETE, BO-PET | Mylar, Dacron, Rettungsdecke, Polyesterfasern und Polyesterstoffe |                                                              |
| Polyethylenterephthalate glycol-modified |       PET-G       |                                                              |                                                              |
| Polybutylenterephthalat                  |     PBT, PTMT     |                       Arnite, Crastin                        |                                                              |
| Polypropylen                             |        PP         |                                                              |                                                              |
| Polyphenylensulfide                      |        PPS        |                                                              |                                                              |
| Polyurethan                              |        PUR        |                                                              |                                                              |
| Ethylen-Propylen Kautschuk               |     EPR, EPM      |                                                              |                                                              |
| Ethylen-Propylen-Dien-Kautschuke         |       EPDM        |                                                              | Brennt sehr stark                                            |
| Polyamide                                |        PA         |                            Nylon                             | schmilzt stark                                               |
| Acrylnitril-Butadien-Styrol              |        ABS        |                                                              |                                                              |
| Polyoxymethylen-Homopolymer              |       POM-H       |                            Delrin                            | Vorsicht: es gibt auch POM-C -> dieser ist oben in der Liste der ungeeigneten Materialien angeführt |
| **Metalle:**                             |                   |                                                              |                                                              |
| Eloxiertes Aluminium                     |                   |                                                              | kann graviert werden                                         |
| lackierter Stahl                         |                   |                                                              | kann graviert werden                                         |
| Stahl                                    |                   |                                                              | Nur mit Lasertransfertape o.ä. gravierbar                    |
| **Sonstiges:**                           |                   |                                                              |                                                              |
| Leder                                    |                   |                                                              | Solange nicht Chrom IV haltig -> Es gibt chromfreigegerbtes Leder |
| synthetischer Gummi                      |                   |                                                              | Solange nicht Chlor-, Fluor-, Halogenhaltig -> siehe Tabelle oben<br />auch keinen Naturkautschuk oder Latex verwenden ->siehe Tabelle oben |
| [Holz](https://wiki.happylab.at/w/Holz)  |                   |                                                              | Massivholz funktioniert besser als Mehrschichtplatten, da kein Leim zwischen den Schichten. Weiches Holz funktioniert besser als Hartholz. Holz ist ist allerdings ein inhomogener Werkstoff... Schnittwerte können variieren... |
| Mitteldichte Faserplatte                 |        MDF        |                                                              |                                                              |
| Hochdichte Faserplatte                   |        HDF        |                                                              |                                                              |
| Papier, Karton                           |                   |                                                              |                                                              |
| Kraftplex                                |                   |                                                              | Besteht aus Holzfasern ohne Leim oder anderen Klebstoffen    |

## Schlecht geeigenete Kunststoffe

* Polycarbonat (PC, Makrolon, Lexan) -> leicht entzündlich, schmilzt und verfärbt sich stark, Dünne Sheets 1-2 mm lassen sich noch einigermaßen schneiden
* High density polyethylene (HDPE) –> leicht entzündlich, schmilzt stark
* geschäumtes Polypropylen (PP) -> leicht entzündlich
* Polystyrol Platten (Bastlerglas) -> sehr schlechte bis unbrauchbare Schnittergebnisse

# Materialeinstellungen
**ACHTUNG**: Die nachfolgenden Tabellen gelten überwiegend für eine 60W (bzw. 40W) Laserröhre, daher sind die Einstellungswerte tendenziell zu niedrig. Bitte bei den Einstellungen mehr Power oder weniger Speed verwenden und Testschnitte machen! Die Listen werden nach und nach auf 100W angepasst.

**Faustregel**:

* bei brennbaren Materialien (Holz, Karton, Papier, ...) niedrige PPI (150)
* bei Materialien die schmelzen (Acryl) hohe PPI; langsamer ergibt schöneren Schnitt, als mit mehr Power 
* beim Schneiden immer Zublasung (**Air**) einschalten

Die Einstellungen hängen vom Material, sowie der Sauberkeit der Linse und Spiegeln ab. Am besten vor dem Schneiden einen kleinen Testschnitt machen!

### Legende
- **Material** (Name des Werkstoffs )
- **Thickness** (Materialstärke)
- **Process**
  - **cut**: durchtrennen / schneiden des Werkstoffs
  - **engrave**: gravieren mit deutlichem Materialabtrag oder Verfärbung der Oberfläche
  - **mark**: wie "engrave" aber nur oberflächlich
  - **crease**: ähnlich cut, nur nicht komplett durchtrennt, z.B. um Papier oder Karton zu falzen oder Holz und Kunststoffe zu biegen.
- **Speed** (Geschwindigkeit)
- **Power** (Leistung, ausgehend von 60 Watt*)
- **PPI** (Auflösung)
- **Passes** (Anzahl der Durchläufe)
  - Eignet sich besonders für Materialien die sich stark verformen, schmelzen oder verkohlen (z.B. Polystyrol) die in mehreren Schritten mit geringerer Leistung geschnitten werden.
- **Focus** (Manuelle Korrektur des Fokus)
  - bei dickeren Materialien ab etwa 8 bis 10 mm ist ein Drittel bis Hälfte der Materialstärke i.d.R. ein guter Ausgangswert
- **Notes** (Zusätzliche Anmerkungen oder Tipps)

## Papier, Karton und Pappe

### Papier

| Material                                                     | Thickness | Process | Speed | Power | PPI  | Air  | Passes | Focus | Notes                                    |
| ------------------------------------------------------------ | :-------: | :-----: | :---: | :---: | :--: | :--: | :----: | :---: | :--------------------------------------- |
| **Holzarmes bzw. holzfreies Kopier- oder Schreibpapier (weiß)** |           |         |       |       |      |      |        |       |                                          |
|                                                              |  80 g/m²  | engrave |  100  |  25   | 400  |  ✖   |   1    |       |                                          |
|                                                              |  80 g/m²  |   cut   |  35   |  90   | 400  |  ✖   |   1    |       | Für 40 Watt                              |
|                                                              | 160 g/m²  | engrave |  100  |  30   | 400  |  ✖   |   1    |       | Für 40 Watt                              |
|                                                              | 160 g/m²  |   cut   |  15   |  90   | 400  |  ✔   |   1    |       | Für 40 Watt                              |
|                                                              | 200 g/m²  |   cut   |  100  |  90   | 1000 |  ✔   |   1    | auto  |                                          |
|                                                              | 300 g/m²  | engrave |  100  |  45   | 1000 |  ✖   |   1    |       | QR-Code auch lesbar ab Größe von 29x29mm |
|                                                              | 300 g/m²  |   cut   |  30   |  90   | 400  |  ✔   |   1    | auto  |                                          |

### Vollpappe

| Material      |     Thickness     | Process | Speed | Power | PPI  | Air  | Passes | Focus | Notes       |
| ------------- | :---------------: | :-----: | :---: | :---: | :--: | :--: | :----: | :---: | ----------- |
| Bristolkarton | 0,2 mm (300 g/m²) |   cut   |  25   |  90   | 400  |  ✖   |   1    | auto  |             |
|               |      0,5 mm       |   cut   |  4.6  |  60   | 600  |  ✔   |   1    |       | Für 40 Watt |
|               |       1 mm        |   cut   |   4   |  60   | 700  |  ✔   |   1    |       | Für 40 Watt |
|               |       2 mm        |   cut   |  3,4  |  60   | 1000 |  ✔   |   1    |       | Für 40 Watt |
|               |                   | engrave |  50   |  30   | 600  |  ✖   |   1    |       | Für 40 Watt |

### Sonstiger Karton

| Material                              | Thickness |      Process      | Watt | Speed | Power |    PPI    | Air  | Passes |  Focus  | Notes                                                        |
| :------------------------------------ | :-------: | :---------------: | :--: | :---: | :---: | :-------: | :--: | ------ | :-----: | :----------------------------------------------------------- |
| Plakatkarton schwarz (Pagro)          |           | cut / perforation |  40  |  15   |  50   |    150    |  ✔   |        |         |                                                              |
|                                       |           |        cut        |  40  |  15   |  50   | 300 - 400 |  ✔   |        |         |                                                              |
|                                       |           |      engrave      |  40  |  100  |  50   |    400    |  ✖   |        |         |                                                              |
| Plakatkarton schwarz (Archidelis)     |  0,5 mm   |        cut        |  40  |  7,6  |  60   |    500    |  ✔   |        |         |                                                              |
| Siebdruckkarton                       |  1,5 mm   |        cut        |  40  |  3,3  |  45   |   1000    |  ✔   |        |         |                                                              |
|                                       |           |      engrave      |  60  |  70   |  30   |   1000    |  ✖   |        |         |                                                              |
| Wellpappe                             |           |      engrave      |  40  |  50   |  90   |    150    |  ✖   |        |         |                                                              |
|                                       |   2 mm    |        cut        |  60  |   8   |  100  |    500    |  ✔   |        |  auto   |                                                              |
| Wellpappe (doppel)                    |   6 mm    |        cut        |  60  |  4,8  |  90   |    500    |  ✔   |        |         |                                                              |
| Sandwich Karton / Graphikboard        |  1,5 mm   |        cut        |  40  |   3   |  80   |   1000    |  ✔   |        |         |                                                              |
|                                       |   3 mm    |        cut        |  40  |   4   |  60   |   1000    |  ✔   |        |         |                                                              |
|                                       |   5 mm    |        cut        |  40  |  3.4  |  60   |   1000    |  ✔   |        |         |                                                              |
|                                       |   10 mm   |        cut        |  40  |   1   |  90   |   1000    |  ✔   |        |         |                                                              |
| Finnpapier (Boesner)                  |  1,5 mm   |        cut        |  40  |  4.4  |  65   |    400    |  ✔   |        |         | step - besser wäre evtl. 4.0 (4.4 schneidet nicht 100% sauber wenn der Fokuspunkt nicht stimmt) |
| Finnpappe  (Fabstore)                 |   2 mm    |        cut        |  60  |  7.0  |  90   |    400    |  ✔   |        |         | INTU = LMZ TU                                                |
|                                       |   3 mm    |        cut        |  40  |   3   |  90   |   1000    |  ✔   |        | -1,0 mm |                                                              |
|                                       |   1 mm    |        cut        |  60  |  13   |  90   |    400    |  ✔   |        |         |                                                              |
|                                       |   1 mm    |      engrave      |  60  |  35   |  90   |    400    |  ✖   |        |         | tief genug um den Karton zu knicken                          |
| Graupappe                             |   1 mm    |        cut        |  60  |   3   |  30   |    400    |  ✔   |        |         | Karton von der Rückseite eines Zeichenblocks, 1 mm Graupappe aus dem Happylab-Store. |
|                                       |   1 mm    |      engrave      |  40  |  100  |  50   |    400    |  ✖   |        |         | Karton von der Rückseite eines Zeichenblocks                 |
|                                       |   2 mm    |        cut        |  60  |   3   |  60   |   1000    |  ✔   |        |         |                                                              |
|                                       |   2 mm    |      engrave      |  60  |  10   |  30   |   1000    |  ✖   |        |         |                                                              |
|                                       |   3 mm    |        cut        |  60  |  3.5  |  90   |   1000    |  ✔   |        | -1,5 mm |                                                              |
|                                       |   3 mm    |        cut        |  60  |  1.4  |  96   |   1000    |  ✔   |        | -1,5 mm |                                                              |
| Verpackungskarton                     |   3 mm    |        cut        |  40  |  2,5  |  90   |    150    |  ✔   |        |         |                                                              |
|                                       |   3 mm    | cut / perforation |  40  |  10   |  90   |    30     |  ✔   |        |         |                                                              |
| KAPA Graph Schwarz Leichtschaumplatte |   5 mm    |        cut        |  40  |   4   |  90   |   1500    |  ✔   |        |         | Am Besten in zwei Durchgängen!                               |
| Abdeckband (Malerkrepp)               |           |        cut        |  60  |  100  |  70   |    800    |  ✔   |        |         | Verwendbar zum Maskieren direkt auf dem Werkstück. Die Bänder verwenden meistens einen druckempfindlichen Acrylklebstoff, dieser schäumt beim Schneiden leicht auf, nach dem Entgittern das Band wieder Festdrücken und ggf. klar vorlackieren, damit die Farbe nicht unter das Band kriechen kann. --Sigfried Arnold 10:05, 14 April 2017 (CEST) |

## Holz und Holzwerkstoffe 

### Sperrholz und Multiplex

| Material                 | Thickness | Process | Speed | Power | PPI  | Air  | Passes |  Focus  | Notes                                                        |
| ------------------------ | :-------: | :-----: | :---: | :---: | :--: | :--: | :----: | :-----: | :----------------------------------------------------------- |
| Birke                    |           |  mark   |  100  |  90   | 1000 |  ✔   |   1    |  auto   | feine Linie ohne Verfärbungen oder Schmauchspuren            |
|                          |   2 mm    |   cut   |   4   |  90   | 1050 |  ✔   |   1    |  -1 mm  | feine, wenig verkohlte Kanten                                |
|                          |   3 mm    |   cut   |  1,5  |  90   | 1000 |  ✔   |   1    |  auto   | ohne Defocus                                                 |
|                          |   4 mm    |   cut   |   1   |  90   | 1050 |  ✔   |   1    | -2,4 mm | stark verkohlte Kanten                                       |
|                          |   4 mm    | engrave |  60   |  60   | 1400 |  ✖   |   1    |  -1mm   | oberhalb der ersten Leimschicht (wenn darunter, dann schmilzt Leim) |
|                          |  6,5 mm   |   cut   |   1   |  90   | 1000 |  ✔   |   1    |  auto   | Einstellungen ziemlich knapp (ein paar einzelne Fasern wurden nicht druchtrennt), ev. vorher Testschnitt machen und die Geschwindigkeit ein bisschen reduzieren. |
| Buche                    |           |  mark   |  90   |  90   | 1000 |  ✔   |   1    |  auto   | feine Linie ohne Verfärbungen oder Schmauchspuren            |
|                          |   3 mm    |   cut   |  1,5  |  90   | 1000 |  ✔   |   1    | -1,5 mm |                                                              |
|                          |   4 mm    |   cut   |  2,4  |  90   | 500  |  ✔   |   1    | -2,0 mm |                                                              |
|                          |   4 mm    | engrave |  100  |  90   | 1000 |  ✔   |   1    | +2,0 mm |                                                              |
|                          |   6 mm    | engrave |  80   |  80   | 1000 |  ✖   |   1    |  auto   |                                                              |
|                          |   6 mm    |   cut   | 0,45  |  90   | 1500 |  ✔   |   2    |  auto   | stark verkohlt aber durch. Speedy 100                        |
|                          |   8 mm    |   cut   |  0,5  |  90   | 400  |  ✔   |   1    |  -6 mm  | Holz anfeuchten damit das Material an der Oberfläche nicht so stark verbrennt |
| **Sperrholz**            |           |         |       |       |      |      |        |         |                                                              |
| Plywood/Furniersperrholz |           | engrave |  37   |  30   | 150  |  ✖   |        |         |                                                              |
| Sperrholz                |           | engrave |  80   |  60   | 1400 |  ✖   |        |         |                                                              |
|                          |   1 mm    |   cut   |  2.6  |  30   | 1000 |  ✔   |        |  -1 mm  |                                                              |
|                          |   1 mm    | engrave |  10   |  50   | 1000 |  ✔   |        |  -1 mm  |                                                              |
| Lasersperrholz           |   2 mm    |   cut   |   3   |  90   | 400  |  ✔   |        |         | Bezugsquelle: http://www.kirchert.com/modellbau/             |
|                          |   3 mm    |   cut   |   5   |  90   | 400  |  ✔   |        |         |                                                              |
| Sperrholz von INTU       |   3 mm    |   cut   |  1.6  |  90   | 900  |  ✔   |        |         | INTU (LMZ TU) nicht sehr geeignet, stark verkohlte Kanten    |
| Laersperrholz (Kichert)  |           |         |       |       |      |      |        |         |                                                              |
|                          |   3 mm    |   cut   |  1,1  |  90   | 1500 |  ✔   |        | 1,5 mm  | Fokus 1,5 mm unter die Oberfläche                            |
|                          |   3 mm    | engrave |  50   |  35   | 1200 |  ✖   |        | 1,5 mm  | HELL - Fokus 1,5 mm unter die Oberfläche (langsam, aber schön) [Christoph] |
|                          |   3 mm    | engrave |  50   |  50   | 1200 |  ✖   |        | 1,5 mm  | MITTEL - Fokus 1,5 mm unter die Oberfläche (langsam, aber schön) |
| Flugzeugsperrholz        |   3 mm    |   cut   |  1,5  |  90   | 1000 |  ✔   |        |         | für 60 Watt; 6 Schichten verleimt                            |
| Lasersperrholz           |   3 mm    |   cut   |  1,3  |  90   | 400  |  ✔   |        | -1,5 mm | Bezugsquelle: http://www.kirchert.com/modellbau/             |
| Pappel                   |   3 mm    |   cut   |  8,0  |  90   | 1000 |  ✔   |        |         | schneller schöner Schnitt auch wenn Holz etwas gewölbt       |
| Pappel (Fabstore)        |   4 mm    |   cut   |  3,6  |  90   | 500  |  ✔   |        |         |                                                              |
|                          |   4 mm    | engrave |  100  |  60   | 800  |  ✔   |        |         |                                                              |
| Pappel (Bauhaus)         |   4 mm    |   cut   |  2,2  |  90   | 1000 |  ✔   |        |  -2 mm  | Trotec 400 (80W). Bei Speed 2.5 kommt er gerade noch durch, aber u.U. Probleme bei Unregelmäßigkeiten |
| Pappel (Bootcamp)        |   5 mm    |   cut   |  1,0  |  90   | 1000 |  ✔   |        | -2,5 mm | 60 Watt: 3/100/800                                           |
| Pappel (Obi / Bauhaus)   |   6 mm    |   cut   |  0.9  |  90   | 1000 |  ✔   |        |  2 mm   |                                                              |
| Pappel                   |   8 mm    |   cut   |  1,3  |  90   | 1000 |  ✔   |        |         |                                                              |



### Weitere Holzwerkstoffe

| Material                                            | Thickness |    Process    |         Speed         | Power | PPI  | Air  | Passes |  Focus   | Notes                                                        |
| :-------------------------------------------------- | :-------: | :-----------: | :-------------------: | :---: | :--: | :--: | ------ | :------: | :----------------------------------------------------------- |
| **Kraftplex (Fabstore)**                            |           |               |                       |       |      |      |        |          |                                                              |
|                                                     |   3 mm    |      cut      |          1,3          |  90   | 500  |  ✔   |        |          |                                                              |
|                                                     |  1,5 mm   |      cut      |           3           |  90   | 500  |  ✔   |        |          |                                                              |
|                                                     |  0,8 mm   |      cut      |           6           |  90   | 500  |  ✔   |        |          |                                                              |
|                                                     |  0,8 mm   |    engrave    |          30           |  80   | 500  |  ✔   |        |          | Schöne Gravurtiefe, gut sichtbar, besseres Resultat wenn man die zu gravierende stelle mit einem Tuch LEICHT Feucht macht |
| **Hartfaserplatte (≠HDF) Obi Zuschnitt**            |           |               |                       |       |      |      |        |          |                                                              |
|                                                     |   3 mm    |      cut      |          0,7          |  80   | 5000 |  ✔   |        | -1,5 mm  | 60 Watt - HINWEIS: Verkohlte Kanten, aber stabiles Material mit schönen Gravureigenschaften bei ca. 0,80€/DIN A3. Eventuell mal mit weniger PPI testen |
|                                                     |   3 mm    |    engrave    |          80           |  70   | 1000 |  ✖   |        | -1,5 mm  | 60 Watt - Für tiefe Gravuren (mit Schmauchspuren) 100/70/1000 |
|                                                     |   5 mm    |      cut      | 0.6 / 0.5 (80W / 60W) |  90   | 1000 |  ✔   |        | -2,5 mm  | 2 Durchgänge, verkohlte Kante aber sauberer Schnitt          |
| **HDF (≠ Hartfaserplatte)**                         |           |               |                       |       |      |      |        |          |                                                              |
|                                                     |   3 mm    |      cut      |          1,5          |  90   | 1000 |      |        | -1,5 mm  |                                                              |
|                                                     |   3 mm    |     mark      |          100          |  90   | 1000 |      |        | -1,5 mm  |                                                              |
|                                                     |  3,5 mm   |      cut      |           1           |  90   | 1000 |      |        |   auto   |                                                              |
| **MDF**                                             |           |               |                       |       |      |      |        |          |                                                              |
|                                                     |           |    engrave    |          80           |  90   | 1000 |  ✖   |        | -1,5 mm  | 60 Watt                                                      |
|                                                     |           |    engrave    |          65           |  90   | 1000 |  ✔   |        | -0,5 mm  | 60 Watt - erzeugt eine 0,5mm tiefe Gravur, sehr raue Oberfläche |
|                                                     |   1 mm    | cut / engrave |          40           |  90   | 1000 |  ✔   |        | -0,5 mm  | 60 Watt. Richtwert zum Testen, getestet mit 3mm MDF engrave/raster 0,5-1mm Breite |
|                                                     |  1,5 mm   | cut / engrave |          18           |  90   | 1000 |  ✔   |        | -0,75 mm | 60 Watt. Richtwert zum Testen, getestet mit 3mm MDF engrave/raster 0,5-1mm Breite |
| Peham Holz Eugendorf                                |   3 mm    |      cut      |          2,7          |  90   | 1100 |  ✔   |        | -1,5 mm  | 60 Watt                                                      |
|                                                     |   4 mm    |    engrave    |          60           |  45   | 1400 |  ✔   |        |          | 60 Watt                                                      |
|                                                     |   4 mm    |      cut      |          5,0          |  90   | 1100 |  ✔   |        | -1,5 mm  | 60 Watt                                                      |
|                                                     |   6 mm    |      cut      |          1,0          |  90   | 1100 |  ✔   |        |  -3 mm   | 60 Watt - Stark verkohlte Schnittkanten aber sauberer Schnitt |
| **Furnier**                                         |           |               |                       |       |      |      |        |          |                                                              |
| Olive & Buche                                       |  0,6 mm   |      cut      |           5           |  50   | 500  |  ✔   |        |          | Fokus auf die Oberfläche gesetzt, sehr schöne Schnittkanten  |
| Birke & Wenge                                       |  0,8 mm   |      cut      |           5           |  50   | 500  |  ✔   |        |          | Fokus auf die Oberfläche gesetzt, sehr schöne Schnittkanten  |
| Nuss                                                |   0,6mm   |    engrave    |          100          |  80   | 500  |  ✔   |        |          | Speedy 400, Material mit Malerkrepp niedergeklebt. Tendiert dazu sich im Klima des Cutters zu wölben |
| Balsaholz                                           |           |    engrave    |          60           |  50   | 150  |  ✖   |        |          |                                                              |
|                                                     |   1 mm    |      cut      |          50           |  90   | 530  |  ✔   |        |          |                                                              |
|                                                     |  1,5 mm   |      cut      |          30           |  90   | 530  |  ✔   |        |          |                                                              |
|                                                     |   2 mm    |      cut      |          10           |  60   | 600  |  ✔   |        | -0,5 mm  | Beim Kalibrieren des Lasercutters Z Focus auf -0.5 mm setzen |
| 2x 50g Glasfaser                                    |   3 mm    |      cut      |       3,2 - 3,6       |  90   | 1500 |  ✔   |        |  1,5 mm  | Fokus auf 1,5mm unter die Oberfläche                         |
|                                                     |   5 mm    |      cut      |           6           |  60   | 600  |  ✔   |        | -2,5 mm  | Beim Kalibrieren des Lasercutters Z Focus auf -2.5 mm setzen |
| **Massivholz**                                      |           |               |                       |       |      |      |        |          |                                                              |
| Linde                                               |   1 mm    |      cut      |           6           |  90   | 400  |  ✔   |        |          |                                                              |
| Linde                                               |   2 mm    |      cut      |          3,5          |  90   | 400  |  ✔   |        |          |                                                              |
| Linde                                               |           |     grave     |          50           |  35   | 1200 |  ✖   |        |          |                                                              |
| Linde (Haarlinienschrift)                           |           |      cut      |          50           |  40   | 300  |  ✖   |        |          | Im Corel Dicke der Linien auf "Haarlinie" einstellen         |
| Kiefer (Leimholzplatte)                             |   20 mm   |    engrave    |          75           |  50   | 1000 |  ✔   |        |          | Relief. Schönes Ergebnis mit Graustufen-Grafik. Für etwas mehr tiefe Power 100 oder 2 Durchgänge |
| Kiefer 3-Schicht-Holz                               |   29 mm   |    engrave    |          50           |  90   | 1500 |  ✔   |        |          |                                                              |
| Birke                                               |           |    engrave    |          15           |  15   | 500  |  ✔   |        |          |                                                              |
| Birke                                               |           |    engrave    |          75           |  90   | 500  |  ✔   |        |          | Dünne Schrift in die Schnittfläche graviert. Min. 2-4 Durchgänge machen, je nach gewünschter Tiefe |
| Leimholz Eiche (Ikea Arbeitsplatte mit 4mm Furnier) |           |    engrave    |          50           |  45   | 1500 |  ✔   |        |          | Thomas: Werte für 60W Laser. Gravur wird schön dunkel ohne zu verkohlen. Leichte Schmauchspuren an den Rändern. |
| Kirsche                                             |           |    engrave    |          15           |  15   | 500  |  ✔   |        |          |                                                              |
| Ebenholz                                            |           |    engrave    |          70           |  20   | 500  |  ✔   |        |          |                                                              |
| Pink Ivory                                          |           |    engrave    |          30           |  20   | 500  |  ✔   |        |          |                                                              |
| Olive                                               |           |    engrave    |          60           |  20   | 500  |  ✔   |        |          |                                                              |
| Holy wood                                           |           |    engrave    |          20           |  20   | 500  |  ✔   |        |          |                                                              |
| Amboina Wurzelholz                                  |           |    engrave    |          50           |  20   | 500  |  ✔   |        |          |                                                              |
| Kanadisches Ahorn Holz (Skateboard)                 |           |    engrave    |          60           |  87   | 840  |  ✔   |        |          |                                                              |
| Erle                                                |           |    engrave    |          55           |  81   | 916  |  ✔   |        |          |                                                              |
| Tanne trocken aus 1642                              |           |    engrave    |          65           |  55   | 1400 |  ✔   |        |          |                                                              |
| Bambus Starkfurnier                                 |    6mm    |      cut      |          1,4          |  90   | 1000 |  ✔   |        |          | Ränder sind augenscheinlich stark verkohlt, lassen sich aber sehr einfach und rückstandsfrei schleifen oder mit Drahtbürste entfernen - man verliert dabei etwa 0,15 mm Material je Kante; --Sigfried Arnold 22:41, 19 April 2017 (CEST) |
| Bambus Starkfurnier                                 |    6mm    |    engrave    |          60           |  90   | 600  |  ✔   |        |          | Die harten Fasern des Bambus bleiben stehen. Ev. mit mehr DPI versuchen... |
| Fichte                                              |   10mm    |      cut      |          0.2          |  90   | 1000 |  ✔   |        |          |                                                              |
### Kunststoffe

| Material                                                   | Thickness | Process |   Speed   | Power |     PPI      | Air  | Passes |  Focus  | Notes                                                        |
| :--------------------------------------------------------- | :-------: | :-----: | :-------: | :---: | :----------: | :--: | :----: | :-----: | :----------------------------------------------------------- |
| **Polystyrol (PS)**                                        |           |         |           |       |              |      |        |         |                                                              |
|                                                            |  0,5 mm   |   cut   |     7     |  65   |     600      |  ✔   |        |         |                                                              |
|                                                            |   1 mm    |   cut   |    4,8    |  65   |     600      |  ✔   |        |         |                                                              |
|                                                            |  1,5 mm   |   cut   |     3     |  90   |     1000     |  ✔   |        |         |                                                              |
|                                                            |   2 mm    |   cut   |     2     |  75   |     500      |  ✔   |        |         |                                                              |
|                                                            |   3 mm    |   cut   |    1,4    |  90   |     1200     |  ✔   |        |         |                                                              |
|                                                            |   4 mm    |   cut   |    0,9    |  90   |     1200     |  ✔   |        |         |                                                              |
|                                                            |   5 mm    |   cut   |    0,7    |  90   |     900      |  ✔   |        |         |                                                              |
| **Styropor (expandiertes Polystyrol PS)**                  |           |         |           |       |              |      |        |         |                                                              |
|                                                            |   10 mm   |   cut   |     3     |  12   |     500      |  ✔   |        |         | Fokus manuell auf Mitte gestellt, Schnittstärke ca. 1 mm     |
|                                                            |   50 mm   |   cut   |    2.7    |  90   |     500      |  ✔   |        | -10 mm  | Fokus manuell auf -10mm gestellt, Schnittstärke ca. 2 mm     |
| **Bastlerglas (Polystyrol)**                               |           |         |           |       |              |      |        |         |                                                              |
|                                                            |   2 mm    |   cut   |    1,0    |  65   |     300      |  ✔   |        |  -2 mm  | Bezugsquelle: Bauhaus ; sehr feiner schnitt Fokus:-2mm untere Kante |
|                                                            |   4 mm    |   cut   | 1,2 (0,7) |  90   | > 600 (1000) |  ✔   |        |         |                                                              |
| **XPS (Extrudiertes Polystyrol) Depron, Styrodur, Neopor** |           |         |           |       |              |      |        |         |                                                              |
|                                                            |   3 mm    |   cut   |     8     |  13   |     400      |  ✔   |   1    | -1,5 mm | alte Einstellungen für 40 W                                  |
|                                                            |   3 mm    | engrave |    60     |  90   |     300      |  ✔   |   1    | -1,5 mm | alte Einstellungen für 40 W (~1,5 mm tiefe Gravur)           |
|                                                            |   5 mm    |   cut   |    100    |  100  |     300      |  ✔   |   1    |         | ca. 1 mm Schnittbreite                                       |
|                                                            |   30 mm   |   cut   |     5     |  25   |     400      |  ✔   |   5    | -10 mm  | ca. 1 mm Schnittbreite, keine nennenswerten Verformungen     |
|                                                            |  > 30 mm  |   cut   |           |       |              |      |        |         | nicht mehr sinnvoll möglich                                  |

### Weiche Kunststoffe

### Weitere Werkstoffe

### Sonstige

## Quellen für Vektor Grafiken
- https://de.vecteezy.com/ 
- http://de.freepik.com/vektoren-beliebt
- http://www.freevectors.net
- https://www.troteclaser.com/de/know-how/musterauswahl/

## Weitere Links

* [Schneidetisch aus Aluminium zum Selberbauen - "Deluxe Version"](https://wiki.happylab.at/w/Schneidetisch_Aluminium)
* [Wabentisch aus Acrylglas zum Selberbauen](https://wiki.happylab.at/w/Acryl_Wabentisch)
* [Wabentisch aus Acrylglas zum Selberbauen (verbesserte Version)](https://wiki.happylab.at/w/Acryl_Wabentisch_Version2)
- Automatische Erstellung von Schachteln 
  - [boxes.py](https://www.festi.info/boxes.py/index.html ) (viele Presets und Möglichkeiten: auch irreguläre Formen, Scharniere usw.)
  - [makercase.com](http://www.makercase.com/)
  - [JBOX](https://wiki.happylab.at/w/JBOX)
- [Test Template für Laser Cutter](https://wiki.happylab.at/w/Laser_Cutter_test)

* [Puzzle Teile](http://clipart.nicubunu.ro/?gallery=jigsaw)
* [Puzzle Generator für Coreldraw](http://www.oberonplace.com/products/jigsaw/)
* Andere Projekte von **[Happylab](https://wiki.happylab.at/w/Main_Page)**: 
  * [Laser Parts](http://www.makercase.com/)
  * [Neuer Autofokus](https://wiki.happylab.at/w/Autofokus_neu)
