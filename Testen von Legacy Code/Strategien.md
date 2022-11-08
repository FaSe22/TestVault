---
tags: legacy code, refactoring
author: Roy Osherove
---



## Einfaches Zuerst

### Wann?

Wenn das Team noch wenig Erfahrung mit Unit Testing hat

### Tip

Vermeide zunächst alle Komponenten mit mehr als vier Abhängigkeiten.

### Nachteil:

> Anfangs ist das Schreiben der Test einfach, aber mit der Zeit bleiben Sie auf den Komponenten sitzen, die zunehmen schwieriger zu testen sind, und die besonders harten Nüsse warten am Ende des Projektzyklus auf Sie, wenn sowieso jeder genervt ist und das Produkt nur noch fertigstellen möchte. 
> - Art of Unit Testing, S. 256




## Schwieriges Zuerst

### Wann?

Wenn das Team erfahren ist.

> Die Strategie Schwieriges zuerst ist nur möchlich, wenn Ihr team Erfahrung im Umgang mit dem Unit Testing hat, denn sie ist schwieriger umzusetzen. Wenn Ihr Team die Erfahrung hat, dann nutzen Sie den Prioritätsaspekt der Komponenten, um zu entscheiden, ob Sie mit den schwierigen oder den einfachen Komponenten starten wollen.

### Vorteil:

> Bei dieser Strategie können sie gut und gerne mehr als einen Tag damit verbinden, auch nur die einfachsten Tests für die komplexeren Komponenten ans Laufen zu bringen. Aber beachten Sie die schnelle Abnahme in der zum Schreiben der Tests benötigten Zeit. 

