# **Funktionsmodell**

*Ich möchte den Herstellern ermöglichen zu verstehen, wofür das Produkt hergestellt wird.*

## **Was ist ein Funktionsmodell?**
<Details>
  <summary>Zum Erweitern klicken!</summary>

* Eine Beschreibung der Funktionen, die von einem Produkt ausgeführt werden.
* Eine Gelegenheit, ein Produkt in kleinere Teile zu zerlegen, die leichter verstanden werden können.
* Servicefunktionen sind auf der höchsten Ebene einer funktionalen Gliederung (Black-Box-Sicht) die (von den Stakeholdern gewollten) Wirkungen der Interaktion des Produkts mit seiner Umwelt. ([Spezifikation](https://github.com/OPEN-NEXT/wp2.3_template/tree/main/Documentation/2.%20Specification#specification))
* Auf der mittleren und untersten Ebene einer funktionalen Gliederung (White Box View) sind technische Funktionen Input-Output-Beziehungen, die Materie-, Energie- oder Informationsflüsse transformieren. Sie äußern sich auf nicht lösungsneutrale Weise und sind im Inneren des Produkts beobachtbar. Zur Realisierung einer Servicefunktion ist eine Reihe von technischen Funktionen notwendig.
 </details>
 

## **Warum sollten Sie Funktionsmodelle definieren?**
<Details>
  <summary>Zum Erweitern klicken!</summary>

* Ein Funktionsmodell hilft dabei, ein kompliziertes Problem in einfache Teilprobleme zu zerlegen.
* Ein funktionales Modell hilft, Fehler vorherzusehen, die auftreten, wenn eine beabsichtigte Wirkung des Produkts auf seine Umgebung nicht mehr erzeugt wird.
* Eine Funktion ist der Haupteingang, um die funktionalen Anforderungen abzuleiten, die erforderlich sind, um die Nutzungsbedingungen des Produkts zu definieren, und um objektive Nachweise durch die Validierungs- und Verifizierungsaktivitäten zu liefern.
 </details>
  
## **Wie dokumentiert man ein Funktionsmodell?**

*Die Dokumentation technischer Funktionen, die eine interne (white box) Sicht auf das Produkt erfordert, besteht darin, die Servicefunktion in Teilfunktionen zu zerlegen. Der Dekompositionsprozess ist nicht mehr lösungsneutral, da er eine Entscheidung auf jeder Indenture-Ebene erfordert. Die funktionale Zerlegung erfordert zwei Modellierungsansätze: Funktionsbaum und Funktionsgraph.*

 ### **1. Funktionsbaum**
<Details>
  <summary>Klicken Sie hier, um die Richtlinie anzuzeigen!</summary>
 
- **Definition:** *Der Funktionsbaum ist eine Top-Down-Zerlegung der Funktion in Unterfunktionen, die hilft, das zu lösende Problem zu vereinfachen.*

- **Kommentare:**

 - *Ein Top-Down- und Bottom-Up-Lesen des Funktionsbaums gibt Aufschluss über das „Wie“ bzw. „Warum“.*
  - *Der Dekompositionsprozess sollte gestoppt werden, wenn die technische Funktion ausreichend detailliert ist, um eine Designlösung wiederzuverwenden, herzustellen oder zu kaufen.*


 ```
1. Welche Mindestdokumentation sollte der Funktionsbaum bereitstellen?
  - Ein Modell, das die Arten von technischen Funktionen und deren Unterfunktionen im Format eines Baums spezifiziert (siehe Funktionsbaum von XYZ Cargo-ADD ONS)

2. Wie wird der Funktionsbaum implementiert?
  - Verwenden Sie funktionale Modellierungssprache für die Darstellung, wie z
    - UML (Use-Case-Diagramm)
    - SysML (Blockdefinition, Aktivität oder internes Blockdiagramm)
    - SADT/IDEF0
    - Funktionsfluss-Blockdiagramm
  - Verwenden Sie Open-Source-Software zum Modellieren der Baumdarstellung, wie z
    - Papyrus
    - Modellio
    - Kapella
  ```
</details>

<Details>
  <summary>Klicken Sie hier, um das Beispiel zu sehen!</summary>
 
*Wir zeigen einige Arten von Funktionsbäumen von Open-Source-Projekten.*

#### *Beispiel 1: [Projekt von XYZ CARGO ADD-ONS](https://projects.opennext.eu/@xyz-cargo-add-ons/xyz-cargo-add-ons)*

#### *Funktionsbaum der XYZ Cargo-ADD ONS*

*Die Zerlegung technischer Funktionen erstellt einen Funktionsbaum und die technischen Funktionen werden basierend auf den funktionalen Anforderungen definiert. Beispielhafter Funktionsbaum für den Kühlschrank auf den ADD-ONS für Lebensmittelhersteller, die in der folgenden Abbildung dargestellt sind.*

  ![Bild des Funktionsbaums von XYZ Cargo-ADD ONS](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Quellen/Bilder/Functional%20tree-%20XYZ%20cargo%20ADD-ONS.jpg)

<a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FFunctional%20tree.drawio" target="_blank">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FFunctional%20tree%20of%20XYZ%20cargo%20ADD-ONS.png">In diagrams.net bearbeiten</a>
</details>

### Vorlage des Funktionsbaums
 
  1. Ein Modell, das die Arten technischer Funktionen spezifiziert
 
  ![Bild des Funktionsbaums der Vorlage](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Funktionaler%20Baum%20für%20Vorlage.jpg)

*Sie können diese Vorlage im App-Diagramm verwenden, um den Funktionsbaum Ihres Projekts/Produkts zu definieren.*
 
 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FFunctional%20tree%20for%20template.drawio" target="_blank">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FFunctional%20tree.png">In diagrams.net bearbeiten</a>
  
 2. Name der Modellierungssprache
     * ...
     * ...
  3. Name der Software
     * Online-App-Diagramm
     * ...

 
### **2. Funktionsdiagramm**
<Details>
  <summary>Klicken Sie hier, um die Richtlinie anzuzeigen!</summary>
 
- **Definition:** *Der Funktionsgraph ist eine mehrstufige logische Gliederung technischer Funktionen.*

- **Kommentare:**

  - *Beziehungen zwischen Funktionen sind ein-/ausgehende Ströme von Materie, Energie oder Information.*
  - *Logische UND/ODER-Gatter können verwendet werden, um gleichzeitige oder sequentielle Funktionen zu definieren.*
  - *Die Artikulation der technischen Funktion kann als Input-Output-Beziehungen beschrieben werden, die Flüsse transformieren, indem die funktionale Modellierungssprache im Format des Diagramms verwendet wird*
  
   ```
  1. Welche Mindestdokumentation sollte der Funktionsgraph bieten?
    - Ein Modell, das eine mehrstufige Logik von Beziehungen zwischen technischen Funktionen spezifiziert (siehe Funktionsdiagramm von XYZ Cargo-ADD ONS)
  
  2. Wie wird der Funktionsbaum implementiert?
    - Verwenden Sie funktionale Modellierungssprache für die Darstellung, wie z
      - UML (Use-Case-Diagramm)
      - SysML (Blockdefinition, Aktivität oder internes Blockdiagramm)
      - SADT/IDEF0
      - Funktionsfluss-Blockdiagramm
    - Verwenden Sie Open-Source-Software zum Modellieren der Baumdarstellung, wie z
      - Papyrus
      - Modellio
      - Kapella
  ```
</details>
 
<Details>
  <summary>Klicken Sie hier, um das Beispiel zu sehen!</summary>
  
#### *Beispiel 1: Funktionsgraph von XYZ Cargo-ADD ONS*:
  
*Das Bild unten zeigt das Funktionsdiagramm der Beziehung zwischen technischen Funktionen zur Aufrechterhaltung der Lebensmittelqualität durch ADD-ONS von XYZ-Fracht*

  ![Bild des Funktionsdiagramms von XYZ Cargo-ADD ONS](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/ Quellen/Bilder/Functional%20graph%20of%20XYZ%20cargo-ADD%20ONS.jpg)

<a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FFunctional%20graph.drawio" target="_blank">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FFunctional%20graph%20of%20XYZ%20cargo%20ADD-ONS.png">In diagrams.net bearbeiten</a>


#### *Beispiel 2*:
  
*Der folgende Link zeigt ein Beispiel für Funktionsblockdiagramme eines Open-Source-Projekts*

[Funktionsdiagramm des Renesas-Beatmungsgeräts](https://www.rs-online.com/designspark/ventilator-design-solution-from-renesas-electronics)
</details>

### Vorlage eines Funktionsgraphen

  1. Ein Modell, das die Beziehungen zwischen technischen Funktionen spezifiziert
 
 ![Bild der Vorlage des Funktionsgraphen](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Funktions%20graph%20for%20template.jpg)
 
 *Sie können den unten stehenden Link verwenden, um das Funktionsdiagramm Ihres Projekts/Produkts zu definieren.*
 
 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FFunctional%20graph%20for%20template.drawio">Als neu bearbeiten</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FFunctional%20graph%20for%20template.png">In diagrams.net bearbeiten</a>
  
 2. Name der Modellierungssprache
     * ...
     * ...
  3. Name der Software
     * Online-App-Diagramm
     * ...
 




