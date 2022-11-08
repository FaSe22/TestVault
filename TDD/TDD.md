---
tags: TDD
---


## Was ist TDD

> Test-driven development is a way of managing fear during programming.
> - Kent Beck, Test-Driven Development, XI.



## Gesetze

1. Es darf kein Production Code geschrieben werden, ehe ein fehlschlagender Unit Test geschrieben wurde.
2. Schreibe den Test so, dass er die minimale Voraussetzung, um fehlzuschlagen erfüllt.
3. Es darf nicht mehr Production Code geschrieben werden, als notwendig ist, um den Unit Test zu bestehen.

>These three laws lock you into a cycle that is, perhaps, thirty seconds long. You begin by writing a small portion of a unit test. But wihtin a few seconds you must mention the name of some class or funtion you have not written yet, thereby causing the unit test to fail to compile. So you must write production code that makes the test compile. But you can't write any more than that, so you start writign mor unit test code. - R. Martin, Clean Coder, S. 81


>For the vast majority of us in between, following these two simple rules can lead us to work much more closely to our potential.
>- Write a failing automated test before you write any code
>- Remove duplication
>- Kent Beck, TDD