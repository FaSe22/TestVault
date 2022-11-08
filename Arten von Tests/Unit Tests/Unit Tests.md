---
tags: Unit Testing, PHPUnit
---

# Was sind Unit Tests?

>Ein Unit Test ist ein automatisiertes Stück Code, das eine zu testende Methode oder Klasse aufruft und dann einige Annahmen über das logische Verhalten dieser Methode oder Klasse prüft. Ein Unit Test wird fast immer mithilfe eines Unit Testing Frameworks erstellt. Er kann einfach geschrieben und schnell ausgeführt werden. Er ist vollständig automatisiert, vertrauenswürdig, lesbar und wartbar. - Roy Osherove, The Art of Unit Testing, S. 31.

Unit Tests werden gegen ein "System under Test" ( SUT) durchgeführt.

> SUT steht für "System Under Test", manche Leute verwenden auch den Begriff CUT ("Class Under Test" oder "Code Under Test"). Wenn wir etwas testen, bezeichnen wir das, was wir testen als das SUT

# Was sind keine Unit Tests?

Ein Test ist **kein** Unit-Test, ...

1. ... wenn er mit einer Datenbank kommuniziert;
2. ... wenn er über ein Netzwerk kommuniziert;
3. ... wenn er auf das Dateisystem zugreift;
4. ... wenn Sie Ihre Umgebung verändern müssen ( etwa indem sie Konfigurationsdateien bearbeiten), um ihn auszuführen.