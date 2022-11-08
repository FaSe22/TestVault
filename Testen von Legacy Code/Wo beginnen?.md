---
tags: legacy code, refactoring
author: Roy Osherove
---

Anhand von folgenden Kriterien kann man die Komponenten des Systems, das man testen will klassifizieren:

1. Logische Komplexität - Dies bezieht sich auf den Umfang der Logik innerhalb der Komponente, wie etwa verschachtelte if-Anweisungen, switch-Anweisungen oder Rekursionen.
2. Abhängigkeitsgrad - Dies bezieht sich auf die Anzahl der Abhängigkeiten innerhalb der Komponenten. Wie viele Abhängigkeiten müssen Sie aufbrechen, um diese Klasse testen zu können? Kommuniziert sie vielleicht mit einer externen E-Mail-Komponente oder ruft sie irgendwo eine statische Log-Methode auf?
3. Priorität - Dies ist die allgemeine Priorität der Komponente innerhalb des Projekts.