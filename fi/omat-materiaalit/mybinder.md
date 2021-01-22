---
title: Materiaalin jakaminen MyBinderissa
lang: fi
ref: mybinder
category: omat
---

# Materiaalin jakaminen MyBinderissa

Mikäli haluat, että GitHubiin tallentamiasi notebookeja pystyy käyttämään MyBinderissa, tulee GitHub-repoon lisätä "requirements.txt"-niminen tiedosto, johon on listattuna kaikki python-kirjastot, joita notebookeissasi käytetään tai joita haluat, että niissä pystyy käyttämään. Esimerkki tällaisesta tiedostosta on [tässä](https://github.com/opendata-education/Maantiede/blob/main/requirements.txt).

Opiskelijoille jaettavan MyBinder-linkin GitHub-sivullasi oleviin notebookeihin saat seuraavasti:

1. Kopioi GitHub-reposi osoite, tai suoraan haluamasi notebookin osoite, esimerkiksi [https://github.com/opendata-education/Maantiede/blob/main/materiaali/harjoitukset/lyhimman_reitin_analyysi.ipynb](https://github.com/opendata-education/Maantiede/blob/main/materiaali/harjoitukset/lyhimman_reitin_analyysi.ipynb)
1. Mene sivulle [https://mybinder.org](https://mybinder.org).
1. Kopioi koko GitHub-repon tapauksessa osoite kenttään "GitHub repository name or URL". Yksittäisen notebookin tapauksessa pilko osoite kenttiin seuraavasti: ![binder](/assets/img/binder-launch-notebook-arrow.png)
1. Kopioi linkki "Copy the URL below and share your Binder with others"-kentästä ja jaa se opiskelijoille.
1. Voit itse avata notebookin MyBinderissa painamalla "Launch"-nappia. MyBinder rakentaa GitHub-reposta virtuaalisen työtilan, jossa voit muokata ja käyttää notebookeja. Huom. virtuaalisesssa työtilassa tehdyt muokkaukset eivät muuta notebookeja GitHub-repossasi, vaan ainoastaan virtuaalisen työtilan sisällä.
