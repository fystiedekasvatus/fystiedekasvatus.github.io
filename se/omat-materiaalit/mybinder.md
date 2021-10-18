---
title: Så delar vi material med MyBinder
lang: se
ref: mybinder
category: omat
---

# Så delar vi material med MyBinder

Om du vill att dina Notebooks på GitHub ska gå att öppna i MyBinder, behöver du lägga till en fil "requirements.txt"
i GitHub-repositoriet. Requirements-filen innehåller en lista över alla python-paket 
(numpy, matplotlib, folium, etc.) som dina Notebooks behöver.
Du kan se ett exempel på en sådan fil [här](https://github.com/opendata-education/Maantiede/blob/main/requirements.txt).

För att sedan få tag på en länk som låter andra öppna din notebook i MyBinder gör du på följande sätt:

1. Kopiera adressen till din GitHub-repo, eller adressen direkt till den önskade Notebooken - exempel: [https://github.com/opendata-education/Maantiede/blob/main/materiaali/harjoitukset/lyhimman_reitin_analyysi.ipynb](https://github.com/opendata-education/Maantiede/blob/main/materiaali/harjoitukset/lyhimman_reitin_analyysi.ipynb)
1. Gå till sidan [https://mybinder.org](https://mybinder.org).
1. Kopiera in adressen i fältet: <img src="/assets/img/binder-launch-notebook-arrow.png" width="50%">
1. Kopiera länken "Copy the URL below and share your Binder with others" och dela den till din klass.
1. Du kan själv öppna Notebooken i MyBinder genom att trycka på "Launch". Mybinder bygger upp en virtuell miljö
baserad på GitHub-repon, där du kan redigera och använda notebooks. Obs! Ändringar som görs i denna virtuella miljö
påverkar inte filerna i din GitHub-repo, utan ändringarna görs bara inom den virtuella miljön.
