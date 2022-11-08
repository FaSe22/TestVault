### <span style="color:red"> Red </span>

Schreiben Sie einen Test, der fehlschlägt, um zu zeigen, dass im Endprodukt ein Stück Code oder eine Funktionalität fehlt.

> Der Test wird so geschrieben, als ob der Produktionscode bereits funktionieren würde, damit das Fehlschlagen des Tests wirklich bedeutet, dass ein Bug corliegt. Wenn ich beispielsweise ein neues Feature in eine Taschenrechner-Klasse einbauen und den Wert LastSum speichern wollte, so würde ich einen Test schrieben, der überprüft,,dass LastStum tatsächlich eine Zahl enthält. Der Test würde fehlschlagen, weil wir diese Funktionalität noch nicht eingebaut haben.
> - R. Osherove, The Art of Unit Testing , S. 38

### <span style="color:green"> Green </span> 

Lassen Sie den Test erfolgreich ablaufen, indem Sie Produktionscode schreiben, der die Anforderungen des Tests erfüllt


### <span style="color:yellow">Refactor</span>

Überarbeiten Sie ihren Code


Dazu Kent Beck:

> The general TDD cycle goes as follows:

1. Write a test. Think about how you would like the operation in your mind to appear in your code. You  are writing a story. Invent the interface you wish you had. Include all of the elements in the story that you imagine will be necessary to calculate the right answers.
2. Make it run. Quickly getting that bar to go to green dominates ecerything else. If a clean, simple solution is obvious, then type it in. If the clean, simple solution is obvious will take you a minute, then make a note of it and get back to the main problem, which is getting the bar green in seconds. This shift in aesthetics is hard for some experienced software engineers. They only know how to follow the rules of toog engineering. Quick green excuses all sins. But only for a moment.
3. Make it right. Now that the system is behaving, put the sinful ways of the recent past behind you. Step back onto the straight and narrow path of software righteousness. Remove the duplication that you have introduced, and get to green quickly.


Dazu Michael Feathers:

> Test-Driven Development arbeitet mit folgendem kleinen Algorithmus:

1. Schreiben Sie einen Failing Test Case.
2. Sorgen Sie fafür, dass er kompiliert wird. 
3. Sorgen Sie dafür, dass er bestanden wird.
4. Entfernen Sie duplizierten Code.
5. Fangen Sie von vorne an.