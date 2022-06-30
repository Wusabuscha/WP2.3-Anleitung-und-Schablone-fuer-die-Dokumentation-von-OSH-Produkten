# **Verhaltensmodell**

*Ich möchte es den Herstellern ermöglichen, die Analyse des physikalischen Verhaltens eines Produkts zu verstehen, um die in den späteren Phasen des Designs getroffenen Entscheidungen zu unterstützen.*

## **Was ist ein Verhaltensmodell?**
<Details>
  <summary>Zum Erweitern klicken!</summary>
   
* Eine Möglichkeit, das Verhalten eines Produkts zu beschreiben, wenn es einen Stimulus erhält.
* Das Verhaltensmodell könnte die mathematische Beschreibung des physischen Produkts sein.
* Das Verhaltensmodell ist die physikalische Interaktion zwischen den Komponenten eines Designs sowie zwischen dem Design und seiner Umgebung. Ein Artefakt zeigt bestimmte Verhaltensweisen nicht nur durch die Änderung oder Beibehaltung seines physikalischen Zustands, sondern auch durch mehrere Interaktionen, die innerhalb des Artefakts sowie mit seiner Umgebung stattfinden.
</details>

## **Warum sollten Sie ein Verhaltensmodell definieren?**
<Details>
  <summary>Zum Erweitern klicken!</summary>
   
* Das Verhaltensmodell identifiziert die Eigenschaften zum Verständnis der Berechnung, Simulation und Umgebung des Produkts.
* Das Verhaltensmodell könnte die Simulation jedes gegebenen physikalischen Phänomens unter Verwendung numerischer Techniken bereitstellen.
* Das Verhaltensmodell beschreibt, wie das Artefakt seine Funktion implementiert und durch technische Prinzipien und physikalische Regeln verwaltet wird, die in einem Verhaltensmodell enthalten sind.
</details>
## **Wie dokumentiert man ein Verhaltensmodell?**

*Die Dokumentation eines Verhaltensmodells hängt vom Produkt ab und es gibt eine andere Art der Simulation zur Analyse des Verhaltens eines Produkts. Beispielsweise sind die Finite-Elemente-Analyse (FEA) und die Computational Fluid Dynamics (CFD) zwei Arten der mechanischen Simulation.*
*FEA verwendet mathematische Modelle, um die Auswirkungen realer Bedingungen auf ein Teil oder eine Baugruppe zu verstehen und zu quantifizieren. CFD ist ein Zweig der Strömungsmechanik, der numerische Analysen und Datenstrukturen verwendet, um die Strömung des Fluids im freien Strom und die Wechselwirkung des Fluids (Flüssigkeiten und Gase) mit durch Randbedingungen definierten Oberflächen zu analysieren.*
*Die Analyse des Verhaltens eines Produkts hängt von seinen Komponenten und seiner Umgebung ab, und es gibt verschiedene Arten von Simulationen, um das Verhalten des Produkts zu berücksichtigen. Daher können wir in diesem Abschnitt nicht alle Arten von Verhaltensmodellen identifizieren. Aber wir geben einen allgemeinen Überblick über die Simulationsmodelle und ihre Implementierung.*

 ### **1. Simulationsmodelle**
<Details>
  <summary>Klicken Sie hier, um die Richtlinie anzuzeigen!</summary>
   
- **Definition:** *Ein Simulationsmodell ermöglicht es den Designern, zu testen, ob die Designspezifikationen erfüllt werden, indem sie Computersimulationen anstelle von Experimenten am physischen Prototyp durchführen. Es verspricht eine umfassendere Untersuchung von Designalternativen und ein leistungsstärkeres endgültiges Design.*

 ```
1. Welche Mindestdokumentation sollte das Simulationsmodell bieten?

  - Identifizieren Sie die Art der Simulation
    - Mechanische Simulation
    - Physikalische Simulation
    - Thermomechanische Simulation
    - Elektronische Simulationen
    - Etc.
    
  - Modelldefinition besteht aus
    - Spezifikation des Geometriemodells (siehe editierbares Dateiformat im Statikmodell)
    - Materialeigenschaften (siehe Strukturmodell)
    - Anfangsbedingungen wie Anfangsspannungen, Temperaturen, Geschwindigkeiten etc.
    - Randbedingungen können einzelnen Lösungsvariablen wie Verschiebungen oder Drehungen auferlegt werden.
    - Kinematische Beschränkungen, die mehrere der grundlegenden Lösungsvariablen im Modell sind (Lineare Beschränkungsgleichungen) oder Mehrpunktbeschränkungen (Allgemeine Mehrpunktbeschränkungen) können definiert werden.
    - Interaktionen, die Kontakt sind, und andere Interaktionen zwischen Teilen können definiert werden
  - Modellierung und Ergebnisse von Simulationen
    
2. Wie wird das Simulationsmodell implementiert?

  - Verwenden Sie Open-Source-Software
    - Öffnen Sie Modelica
    -ADINA
    - Etc.
  ```
  </details>
  
  <Details>
  <summary>Klicken Sie hier, um die Beispiele zu sehen!</summary>
   
   
 **Beispiel 1: [FinEtools: Finite-Elemente-Tools](https://github.com/PetrKryslUCSD/FinEtools.jl)**
 
 **Beispiel 2:** *Bild unten zeigt die Simulation der Torsion des Festteils von unten und deren Bewertung der Realität.*
 
  ![Bild der Finite-Elemente-Analyse](https://github.com/OPEN-NEXT/WP2.3-Guideline-and-templatefor-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Finite %20Element%20Analyse%20Bild.gif)
 </details>
  
 ### Vorlage des Simulationsmodells
 
  1. Art der Simulation
     * ...
  2. Modelldefinition
     * Geometrisches Modell
     * Materialeigenschaften
     * Anfangsbedingungen
     * Randbedingungen
     * ...
     * ...
  3. Modellierung und Simulationsergebnisse
     * ...
  4. Name der Software
     * ...
