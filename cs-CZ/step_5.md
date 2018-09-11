## Přidání skóre

Pojďme udělat věci zajímavější tím, že budeme sledovat skóre!

\--- task \---

Vytvoř novou proměnnou nazvanou "skóre".

[[[generic-scratch-add-variable]]]

\--- /task \---

\--- task \---

Dokážeš sledovat skóre hráče? Hráči by měli získávat body chytáním duchů ato tak, že na ně budou klikat.

Pokaždé, když hráč klikne na ducha, jeho skóre by se mělo zvýšit.

![Zvýšení skóre](images/ghost-score-test.png)

\--- hints \--- \--- hint \--- `Po kliknutí na zelený praporek`{:class=”blockevents”}, proměnnou `score`{:class=”blockdata”} inicializujeme `nastavením na 0`{:class=”blockdata”}. Scéna je nejlepším místem pro přidání tohoto kódu. `Po kliknutí na mě`{:class=”blockevents”}, potřebujeme proměnnou `score`{:class=”blockdata”} `změnit o 1`{:class=”blockdata”}. \--- /hint \--- \--- hint \--- Zde jsou bloky, které budeš potřebovat: ![screenshot](images/ghost-score-blocks.png) \--- /hint \--- \--- hint \--- Zde je způsob, který zvyšuje skóre, když klikneš na ducha: ![screenshot](images/ghost-score-code.png) \--- /hint \--- \--- /hints \---

\--- /task \---