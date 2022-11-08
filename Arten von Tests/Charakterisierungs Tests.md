Die Tests, die wir brauchen, wenn wir verhalten bewahren wollen, bezeichne ich als Charakterisierungs-Tests. Solche Tests charakterisieren (beschreiben, definieren) das jetzige Verhalten eines Code-Fragments. Annahmen über und Wünsche an sein verhalten sind tabu. die Tests dokumentieren das tatsächliche gegenwärtige Verhalten des Systems.

> Charakterisiungs-Tests halten das tatsächliche Verhalten eines Code-Fragments fest. Wenn wir beim Schreiben der Tests etwas Unerwartetes finden, lohnt es sich, Klarheit zu schaffen. Es könnte ein Bug sein. Dies bedeutet, dass wir den Test nicht in unsere Test-Suite aufnehmen; stattdessen sollten wir ihn als verdächtig markieren und feststellen, welche Auswirkungen eine Korrektur hätte.


## Algorithmus zum schreiben von Charakterisierungstests

1. Verwenden Sie ein Code-Fragment in einem Test-Harnisch.
2. Schreiben Sie eine Zusicherung, von der Sie wissen, dass sie scheitern wird.
3. Lesen Sie am Scheitern das zugehörige Verhalten ab. 
4. Ändern Sie den Test so, dass er das Verhalten erwartet, das der Code zeigt.
5. Wiederholen Sie

## Heuristik für das Schreiben von Charakterisierungs Tests

1. Schreiben Sie Tests für den Bereich des Codes, in dem Sie Änderungen vornehmen wollen. Schreiben Sie so viele Testfälle, wie Sie brauchen, um das Verhalten des Codes zu verstehen.
2. Analysieren Sie danach besonder sdie Dinge, die Sie ändern werden, und versuchen Sie, dafür tests zu schreiben.
3. Wenn Sie versuchen Funktionalität zu extrahieren oder zu verschieben, schreiben Sie für jeden Testfall Tests, die die Existenz und Verknüpfung dieser Verhaltensweisen bestätigen. Verifizieren Sie, ob der zu verschiebende Code geprüft und korrekt verknüpft ist. 
