# **Montage**

*Ich möchte Machern ermöglichen, die Schritte zum Konstruieren eines fertigen Produkts aus Komponenten oder teilweise zusammengestellten Einheiten zu verstehen.*

## **Wie dokumentiere ich einen Montage- oder Demontageprozess?**

*Montageanleitungen können die Hersteller anleiten, den Prozess der Montage oder Demontage von Komponenten eines Produkts zu verfolgen.*

### **Montageanleitungen**
<Details>
  <summary>Klicken Sie hier, um die Richtlinie anzuzeigen!</summary>
 
 - **Definition:** *Montageanleitungen könnten visuell und mit Worten und Text veranschaulichen, wie die mechanischen und elektrischen Komponenten des Produkts montiert oder demontiert werden.*


 ```
Was beinhaltet der Inhalt einer Montageanleitung?

 1. Erforderliche Fähigkeiten für die Montage
    - Bohrmaschine bedienen
    - Bandsäge/Dremel bedienen
    - Etc.
 2. Liste der Werkzeuge für die Montage oder Demontage
    - Obligatorisch
       - Inbusschlüsselsatz
       - Zollschlüsselsatz
       - Etc.
    - Optional
       - Bohrmaschine
       - Etc.
 3. Montageablauf
    - Teileliste für mechanische Teile: ist eine vollständige Liste aller Teile, die zum Bau des vollständigen Produkts benötigt werden (siehe Stückliste im Abschnitt Herstellung)
       - Artikelnummern: basieren auf der Baugruppenstruktur, d. h. der Reihenfolge, in der Teile in der Baugruppe angezeigt werden.
       - Teilenummer oder Zeichnungsnummer: Dies ist ein Rückbezug auf die Detailzeichnung (siehe Stückliste).
       - Beschreibung: ist normalerweise ein Teilename oder eine vollständige Beschreibung von Teilen.
       - Menge ist die Anzahl dieses bestimmten Teils, das in dieser Baugruppe verwendet wird.
       - Bild von jedem Teil
    - Datenblatt von Komponenten für elektronische Teile
       - Beschreibung der Funktionen
          - Kern
          - Erinnerungen
          - Erweiterte Konnektivität
          - etc.
       - Gerätezusammenfassung
          - Bezug
          - Artikelnummer
       - Wie benutzt man die Teile?
    - Beschreibung der Bearbeitung/Fertigung, falls dies während der Montage erforderlich ist (siehe Fertigung und siehe Vorlage unten)
      - Maschine gebraucht
      - Prozessablauf
    - Die Schritte, die zum ordnungsgemäßen Zusammenbau der Teile erforderlich sind
       - Beschreibung der Montage bei jedem Schritt
       - Identifizieren der Verbindungstechnologie bei jedem Schritt
          - Schrauben
          - Verschraubung
          - Löten
          - Etc.
  
Wie visualisiert man den Montage- oder Demontageprozess?
 1. Bilder
 2. Videos
```
</details>

<Details>
  <summary>Klicken Sie hier, um das Beispiel zu sehen!</summary>
 
*Einige Beispiele für Open-Source-Projekte, die Montageanleitungen enthalten.*

#### *Beispiel 1:* [Poppy Robot](https://docs.poppy-project.org/en/assembly-guides/ergo-jr/mechanical-construction.html)

#### *Beispiel 2:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/mechanical/body_assembly)

#### *Beispiel 3:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Assembly) , [Montageanleitung](https://ohai.satnogs.org/project/satnogs-rotator -v3-mechanische-montage/hardware/)
  
#### *Beispiel 4:* [Open Source Powered Prosthetic Leg](https://www.hackster.io/open-source-bionics/open-source-powered-prosthetic-leg-56be8e#toc-electronics-assembly -4)
</details>

### Montagevorlage
 
 #### 1. Erforderliche Fähigkeiten für die Montage
 
 *Sie können diese Vorlage im App-Diagramm verwenden, um die erforderlichen Fähigkeiten für die Montage zu definieren.*
 
![Bild der erforderlichen Fähigkeiten](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Required%20Fähigkeiten.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FRequired%20skills.drawio">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FRequired%20skills.png">In diagrams.net bearbeiten</a>

 #### 2. Liste der Werkzeuge für die Montage oder Demontage
   * Unverbindlich
     * ...
   * Optional
     * ...
 #### 3. Montagesequenzen
   * Teileliste (siehe [Bill of Material (BOM)](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/tree/main/Documentation/4.%20Manufacturing#1-Bill-of-Material-Bom))
   * Datenblatt
  
   *Sie können diese Vorlage im App-Diagramm verwenden, um die Teileliste zu definieren.*
 
![Bild der Teileliste](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Part%20list.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FPart%20list%20or%20data%20sheet.drawio">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FPart%20list%20or%20data%20sheet.png">In diagrams.net bearbeiten</a>
 
   *Sie können diese Vorlage im App-Diagramm verwenden, um das Datenblatt zu definieren.*
 
![Bild des Datenblatts](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Data%20sheet.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FData%20sheet.drawio">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FData%20sheet.png">In diagrams.net bearbeiten</a>
 
  * Beschreiben der Bearbeitung/Herstellung von Teilen, falls erforderlich (siehe [Manufacturing](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/tree/main/Dokumentation/4.%20Fertigung/Hergestelltes%20Werkstück#2-Fertigungsanleitung-sollte-enthalten))
  
 *Sie können diese Vorlage im App-Diagramm verwenden, um die Komponenten und den Prozess der Bearbeitung/Fertigung zu demonstrieren.*
 
![Bild der Bearbeitung/Fabrikation](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Describing%20die%20Bearbeitung_%20Fertigung%201.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FDescribing%20the%20machining%2F%20fabrication.drawio">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FDescribing%20the%20machining%2Ffabrication.png">In diagrams.net bearbeiten</a>
   
   * Die Schritte, die erforderlich sind, um die Teile richtig zusammenzubauen
   
   *Siehe Beispiel 1 und 2.*
     
   *Sie können diese Vorlage im App-Diagramm verwenden, um die Schritte für den Zusammenbau der Teile zu erklären.*
 
![Bild der zusammenzubauenden Schritte](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Steps%20bis%20montieren%20die%20Teile%201.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FSteps%20to%20assemble%20the%20parts.drawio">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FSteps%20to%20assemble%20the%20parts.png">In diagrams.net bearbeiten</a>
