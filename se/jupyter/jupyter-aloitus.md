---
title: test
lang: se
ref: jupyter-aloitus
category: jupyter
---

# Så här använder du en Notebook

Här hittar du korta instruktioner för hur du kommer igång med Jupyter Notebooks.

Du kan också ta en titt på vår [YouTube-kanal](https://www.youtube.com/channel/UC2HOmLMQsq4EORZzncCyMIg), 
som innehåller material som vi använt i tidigare fortbildningskurser.

Jupyter Notebooks består av texceller (Markdown) och kodceller (Code).
Cellerna kan ändras och "köras" (run). När man kör en textcell blir den till prydlig artikeltext, 
som formateras enligt HTML-tolken Markdown. När man kör en kodcell verkställs koden, och celler skriver ut
kodens output. På bilden nedan syns några trick som Markdown erbjuder, och fler hittas på adressen [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

<img src="https://raw.githubusercontent.com/opendata-education/opendata-education.github.io/master/assets/img/exempel-notebook.png" width="60%">
![](https://raw.githubusercontent.com/opendata-education/opendata-education.github.io/master/assets/img/exempel-notebook.png)

I kodcellerna kan man skriva kod i Notebookens valda programmeringsspråk. Alla våra övningar använder Python.

## Verktyg i Notebook

Man markerar en cell genom att klicka en gång, och öppnar den i redigeringsläge när man klickar igen.
Cellen kan köras med verktygsbalkens **"Run"**-knapp eller med snabbkommandot **Ctrl + Enter**.
Då cellen är markerad har den en blå kant, om den är öppen i redigeringsläge är kanten grön.

Fler snabkommandon hittas i **Help**-menyn (eller genom att trycka **"h"** när ingen cell är öppen).

Till vänster om cellen syns klamrar med ett ordningstal (Index, **In [ ]**), som berättar
i vilken ordning kodcellerna har körts. Om klamrarna är tomma har cellen inte körts, och om de
visar en asterisk (**In [\*]**) håller cellen på att köras.
Ibland tar det länge att köra en cell, om den ska skapa en animation eller ladda in stora mängder information,
men om det tar orimligt länge kan man behöva avbryta processen genom **kernel**-menyns **Interrupt**-kommando.

Ibland kan det hända att kärnan (kernel) har sparat någon felaktig variabel eller att något annat minnesfel uppkommer.
Då kan det löna sig att återställa kärnan med **Kernel**-menyns **Restart**-kommando. Detta tar inte bort något av din kod,
den återställer bara resultaten och variablerna som finns i minnet. Efter den processen bör alla celler köras igen, men det kan också göras med ett enda kommando från menyn.



Tilläggsinformation:

- [https://jupyter.org/](https://jupyter.org/)
- [https://jupyter-notebook.readthedocs.io/en/stable/](https://jupyter-notebook.readthedocs.io/en/stable/)
