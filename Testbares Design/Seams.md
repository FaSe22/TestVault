
---
tags: Design, Testbarkeit
---

## Definition


> Ein Seam ist eine Stelle, an der Sie Verhalten in Ihrem Programm modifizieren können, ohne es an dieser Stelle zu ändern
> - M. Feathers, Legacy Code, 55.

> Seams sind Stellen in Ihrem Code, in die Sie eine andere Funktionalität einfügen können, wie etwa Stub-Klassen. Sie könnten auch einen Konstruktor-Parameter hinzufügen, eine Property mit öffentlichem set, Sie könnten eine Methode virtuell machen, damit sie überschrieben werden kann, oder einen Delegaten als Parameter oder Property von außen verfügbar machen, damit von außerhalb der Klasse auf ihn zugegriffen werden kann. Seams sind das, was Sie bekommen, wenn Sie das Open-Closed Prinzip implementieren, wo die Funktionalität einer Klasse offen ist für eine Verbesserung, aber der Quellcode abgeschlossen ist gegen eine direkte Modifikation. 
> - Art of Unit Testing, 82.