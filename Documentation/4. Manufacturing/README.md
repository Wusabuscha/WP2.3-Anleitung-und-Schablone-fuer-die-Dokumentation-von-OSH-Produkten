# **Herstellung**

*Ich möchte Herstellern ermöglichen, den Prozess zu verstehen, durch den sich Rohstoffe in ein Endprodukt verwandeln.*

## **Wie dokumentiere ich einen Herstellungsprozess?**

*Herstellungsanweisungen können die Hersteller anleiten, einem Prozess zur Replikation eines Produkts zu folgen. Herstellungsanweisungen sind vollständige Beschreibungen und Anweisungen in Bezug auf Rohstoffe, Betriebsbedingungen und Verfahren, die für die Herstellung und Montage des Produkts verwendet werden sollen.
Die Stückliste (BOM) ist das Dokument, das alle Komponenten und ihre Referenzen beschreibt. Wenn die Komponente gekauft werden soll, sollte man alle Informationen finden, die zum Kauf des Teils erforderlich sind. Wenn das Teil hergestellt werden soll, sollten Sie alle Beschreibungen der Herstellungsanweisungen wie unten beschrieben finden.*

## **Wie dokumentiere ich ein Teil des Fertigungsprozesses?**

*Wenn das Teil hergestellt werden soll, sollten Sie alle Beschreibungen der Herstellungsanweisungen wie unten beschrieben finden.*

### *1. Stückliste (BOM)*
<Details>
  <summary>Klicken Sie hier, um die Richtlinie anzuzeigen</summary>
 
 - **Definition:** *Eine Stückliste (BOM) ist eine umfassende Liste von Teilen, Artikeln und anderen Materialien, die zur Herstellung eines Produkts erforderlich sind, sowie Anweisungen, die zum Sammeln und Verwenden der erforderlichen Materialien erforderlich sind.*

```
Was sollte die Stückliste enthalten (nicht beschränkt auf ...)?

   1. Teilenummer
   2. Artikelname
   3. Teilenummer des Herstellers
   4. Digi-Key-Teilenummer
   5. Beschreibung
   6. Hergestelltes Teil (Link zur Herstellungsanweisung)
   7. Kaufteil (Link zur Verkäuferseite)
   8. Menge
   9. Preis
   10. Standardlieferzeit für die Herstellung
   11. Verpackung
   12. Anmerkungen zur Stückliste
   13. ...
   ```
</details>
<Details>
  <summary>Klicken Sie hier, um das Beispiel zu sehen</summary>
 
 #### *Beispiel 1: [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/bill_of_materials)*
  
![Bild](https://user-images.githubusercontent.com/59058909/126754681-8afeaaa9-619e-49c5-94ca-962bd0d225c3.png)

*BOM von JPL Open-Source-Rover*
  
 #### *Beispiel 2: [SatNOGS Rotator v3](https://gitlab.com/librespacefoundation/satnogs/satnogs-rotator/blob/master/rotator-bom.ods)*
  
 #### *Beispiel 3: [Krab v1.0](https://projects.fablabs.io/@avishek/krab-v10)*

</details>

### Stücklistenvorlage

 #### Stückliste
 
 *Sie können diese Vorlage im App-Diagramm verwenden, um die Stückliste Ihres Projekts/Produkts zu definieren.*

![Bild der Stückliste](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/BOM%20template-2.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FBOM%20template.drawio" target="_blank">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FBOM%20template%20of%20manufactured%20workpiece.png">In diagrams.net bearbeiten</a>
 
  ### *2. Die Herstellungsanweisungen sollten enthalten:*
 
 #### *2.1. Fertigungswerkzeuge*
  <Details>
  <summary>Klicken Sie hier, um die Richtlinie anzuzeigen!</summary>
 
  - **Definition:** *Damit sind alle Maschinen, Geräte und Prozesse gemeint, die zur Herstellung von Produkten verwendet werden. Leitfaden zur Herstellungstechnologie, um die Art der erforderlichen Technologie zur Herstellung des Teils zu finden. In diesem Fall sollte es je nach Kontext die am besten geeignete Technologie beschreiben.*

 ```
 Was sollte die Dokumentation von Fertigungswerkzeugen beinhalten?
 
 Art der verwendeten Maschinen

   1. CNC-Werkzeugmaschinen zur Bearbeitung von Metall oder anderen starren Materialien
     - Mahlen
     - Drehbank
     - Schneiden
     - Bohren
     - Etc.
     
   2. Andere gängige Fertigungswerkzeuge
     - 3D-Druck (FDM, SLS...)
     - Thermoformen
     - Brennende Bearbeitungstechnik (Laserschneiden, Plasmaschneiden, ...)
     - Verbindungstechnologien (Löten, Kaltschweißen, Lichtbogenschweißen, Kleben ...)
  
   3. Endbearbeitung: Um die richtigen Eigenschaften wie Oberflächenqualität, Formgenauigkeit und mechanische Eigenschaften zu erreichen, ist die Endbearbeitung unerlässlich.
     - Schleifen nach dem 3D-Druck
     - Eine Lücke stopfen
     - Sprengen
     - Polieren
     - Grundierung und Lackierung
     - Etc.
  
 Wie visualisiert man die Fertigungswerkzeuge?
  1. Bilder
  2. Videos
 ```
 </details>
 
  <Details>
  <summary>Klicken Sie hier, um die Beispiele zu sehen!</summary>
 
   #### *Beispiel 1:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/mechanical/body_assembly#3-machiningfabrication)
   
   #### *Beispiel 2:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Build_Sequence)
  </details>
 
   #### Vorlage für Fertigungswerkzeuge
   
*Sie können diese Vorlage im App-Diagramm verwenden, um Fertigungswerkzeuge zu definieren.*
 
![Bild der Fertigungswerkzeuge](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Manufacturing%20Werkzeuge.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FManufacturing%20technology.drawio">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FManufacturing%20technology.png">In diagrams.net bearbeiten</a>

 #### *2.2. Fertigungsabläufe und Anweisungen*
 <Details>
  <summary>Klicken Sie hier, um die Richtlinie anzuzeigen!</summary>
 
  - **Definition:** *Fertigungsabläufe bezeichnen schrittweise Bearbeitungs- und Fertigungsprozesse in zielgerichteter Anordnung, um eine Fertigung zu ermöglichen.*
  
  - **Kommentare:**
  
      * Die Bearbeitungsreihenfolge sollte für die Herstellung jedes Teils festgelegt werden.
      * Prozessparameter sind all jene Parameter, die jedem Bearbeitungsvorgang inhärent sind und einen geeigneten endlichen Wert haben sollten, um einen reibungslosen und effizienten Materialabtrag zu ermöglichen.
      * Herstellungsstandard-Dateiformate unterstützen einige der Herstellungsprozesse und die Oberflächengeometrie eines Designs ohne die Möglichkeit der Änderung.

```
Was beinhaltet die Dokumentation von Fertigungsabläufen und Anweisungen?
 
  1. Name der zugehörigen Maschine für jeden Schritt
  2. Beschreibung der schrittweisen Abfolge des Bearbeitungsprozesses
    - Maschine
    - Art der Operation
    - Werkzeugbeschreibung
    - Prozessparameter jedes Bearbeitungsvorgangs (siehe Vorlage für Fertigungsabläufe unten)
       - Prozessparameter des 3D-Drucks
       - Prozessparameter des Laserschneidens
       - Prozessparameter von CNC-Maschinen wie Drehmaschine, Fräsmaschine etc.
       - Prozessparameter des Lichtbogenschweißens
    - Rohstoffe
    - Fertigungsdateien (STL, SVG oder G-Code, ...)
       - CAD-Dateien in einem für den 3D-Druck geeigneten Austauschformat wie STL
       - Nenngeometrie und ihre zulässige Variation durch Verwendung von Symbolsprache in 2D-Zeichnungen wie SVG-, JPEG- und PDF-Format, das zum Laserschneiden geeignet ist
       - Fertigungsexportformate wie G-Code, STEP-NC sind für die CNC-Bearbeitung geeignet
       - Leiterplatten-Designformate wie Gerber RS-274X, Excellon, das für Vektorfotoplotter und mechanische 2D-NC-Maschinen geeignet ist
  ```
</details>

<Details>
  <summary>Klicken Sie hier, um die Beispiele zu sehen!</summary>
 
   #### *Beispiel 1:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/mechanical/body_assembly#3-machiningfabrication)
  
   #### *Beispiel 2:* [DIY Dremel CNC-Design und -Teile](https://www.thingiverse.com/thing:3004773) und [seine CAM-Datei für die Bearbeitung](https://www.estlcam.de /)
  
   #### *Beispiel 3:* Diese Tabelle zeigt beispielhaft die Fertigungsabläufe.
  
  ![Bild der Bearbeitungssequenzen](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Example% 20%20Bearbeitung%20Sequenzen.jpg)
  
  #### *Beispiel 4:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Specifications), [2D-Zeichnungsdatei](https://wiki.satnogs.org/File:C1001. png)
  
  #### *Beispiel 5:* Arten von CAD-Formaten von [transmagic](https://transmagic.com/cad-formats/)
   </details>
  
  #### Vorlage für Fertigungsabläufe
  
   *Sie können diese Parameter für jeden Bearbeitungsvorgang verwenden, um die Fertigungssequenzen im App-Diagramm zu vervollständigen.*
  
  #### 1. 3D-Druckerparameter

   * Extrudereinstellung
      * Extrusionsmultiplikator
      * Rückzugsabstand
      * Rückzugsgeschwindigkeit
      * Ausrollen
   * Layer-Einstellung
      * Höhe der ersten Schicht
      * Geschwindigkeit der ersten Schicht
   * Beckenhöhe
   * Druckbetttemperatur
   * Füllungseinstellung
      * Internes/Ewiges Füllmuster
   * Temperatureinstellung
   * Kühleinstellung
     
  #### 2. CNC-Maschinenparameter wie Drehmaschine, Fräsen usw.
  
   * Schnittparameter
      * Schneidgeschwindigkeit
      * Vorschubgeschwindigkeit
      * Schnitttiefe
      * Schnittbreite
      * Schneidkraft
      * Spulengeschwindigkeit
      * Schnitttemperatur
   * Schneidewerkzeug
      * Werkzeuggeometrie
      * Werkzeugeinstellung
   * Kühlmittel
      
 #### 3. Brennende Bearbeitungsparameter wie Laserschneiden
  
   * Strahlparameter
      * Wellenlänge
      * Kraft und Intensität
      * Polarisierung
   * Prozessparameter
      * Fokussierung von Laserstrahlen (die Brennweite der Linse)
      * Schwerpunktlage
      * Einfallswinkel
      * Schneidgeschwindigkeit
      * Gasdruck
      * Abstandsabstand
      * Erwartete Dauer

  #### 4. Parameter der Verbindungstechnologien wie Lichtbogenschweißen
    
   * Schweißstrom
   * Schweißspannung
   * Bogenfahrgeschwindigkeit
   * Brennerwinkel
      * Längs
      * Quer
   * Elektrodenkraft
   * Elektrodendurchmesser
   * Bogenlänge
   
![Bild der Fertigungssequenz](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Manufacturing%20sequenzen%201.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FMachining%20parameters.drawio">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2Fmachnining%20paramters.png">In diagrams.net bearbeiten</a>
