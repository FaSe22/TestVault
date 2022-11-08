
---
tags: Testbarkeit, Dependencies, Duplicate Code
author: Kent Beck, Michael Feathers
---

>Steve Freeman pointed out that the problem with the test and code as it sits is not duplication ... The problem is the dependency between the code and the test - yout can't change one without changing the other Our goal is to be able to write another test that makes sense to us, without having to change the code, something that is not popssible with the current implementation. **Dependency is the key problem in software development at all scales**.
>If you have details of one vendor's implementation of SQL scattered throughout the code and you decide to change to another vendor, then you will discover that your code is dependent on the database vendor. You can't change the database without changing the code.
>If dependency is the problem, duplication is the symptom. Duplication most often takes the form of duplicate logic - the same expression appearing in multiple places in the code. Objects are excellent for abstracting away the duplication of logic.
>**Unlinke most problems in life, where eliminating the symptons only makes the problem pop up elsewhere in worse form, eliminating duplication in programs eliminates dependency.** That's why the second rule appears in TDD. By eliminating duplication before we go on to the next test we maximize our chance of being able to get the next test running with one and only one change.

TDD, S. 8

> Dependencies sind oft das offensichtlichste Hindernis, das Tests blockiert.
> - Legacy Code, S. 43


> Dependency ist eines der gravierendsten Probleme bei der Software-Entwicklung. Ein großer Teil der Arbeit mit Legacy Code besteht darin, Dependencies so aufzuheben, dass der Code leichter geändert werden kann.
> - Legacy Code, S. 40