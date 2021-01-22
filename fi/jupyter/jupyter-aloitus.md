---
title: test
lang: fi
ref: jupyter-aloitus
category: jupyter
---

# Näin käytät notebookeja

Tällä sivulla on lyhyet ohjeet, joilla pääset alkuun Jupyter notebookien kanssa.

Jupyter notebookit koostuvat teksti- eli Markdown-soluista ja koodisoluista.
Soluja voidaan muokata tai ajaa (run), jolloin tekstisolun tapauksessa Markdown-soluun kirjoitettu teksti muuttuu siistimpään muotoon tai koodisolun tapauksessa soluun kirjoitettu koodi suoritetaan. 

Markdown-solua voidaan muokata ainoastaan muokkaustilassa, johon päästään kaksoisklikkaamalla solua.
Soluun voidaan huoletta kirjoittaa tekstiä aivan tavallisesti.
Jos haluat lisäksi käyttää esimerkiksi otsikoita, linkkejä ja kuvia yms., katso apua osoitteesta [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

Koodisoluihin voidaan kirjoittaa koodia notebookissa käytössä olevalla kielellä (näissä harjoitteissa kielenä on Python).
Katso esimerkki alla olevasta kuvasta.

![](/assets/img/jupyter-cell-example.png)

## Työkalut notebookissa

![](/assets/img/jupyter-tools-example.png)

Soluja pääsee muokkaamaan kaksoisklikkaamalla solua ja solun sisällön ajaminen onnistuu joko työkalurivin **"Run"**-painikkeesta tai suoraan näppäimistöltä painamalla **Ctrl+Enter**. Jos solu on valittu, sen ympärillä on sininen reunus, joka muuttuu vihreäksi muokkaustilassa.

Työkalurivin **"Help"**-valikosta (tai painamalla **"h"** ilman soluvalintaa) löytyy lista pikanäppäimistä.

Solujen vasemmalla puolella näkyvissä sulkeissa on järjestysnumero, joka kertoo missä vaiheessa kyseinen solu on ajettu. Mikäli siinä näkyy tähti (**\***), solua ajetaan yhä. Joskus ajo kestää pitkään, esimerkiksi animaatioita tai isoja latauksia tehdessä. Joskus koodiin on voinut eksyä esimerkiksi loppumaton silmukka joka pitää keskeyttää **"Kernel"**-valikon kautta keskeyttämällä ajo **"Interrupt"**-käskyllä.

Välillä voi myös käydä niin, että ytimeen on jäänyt sotkuinen muuttuja joka aiheuttaa virheitä myöhemmissä komennoissa. Tällöin voi olla aiheellista ajaa määrittelevät solut uudelleen tai tyhjentää kaikki **"Kernel"**-valikon **"Restart"**-käskyillä (joilla voi myös pyyhkiä aiemmat tulokset tai ajaa alusta lähtien koko muistion kerralla yksittäisten solujen napsuttelun sijaan). Ytimen uudelleenkäynnistys tai keskeytys ei vaikuta millään tapaa muistion solujen sisältöön, vaan ainoastaan kullakin hetkellä muistissa oleviin tuloksiin, muuttujiin ja vastaaviin olioihin.

Lisäinformaatiota:

- [https://jupyter.org/](https://jupyter.org/)
- [https://jupyter-notebook.readthedocs.io/en/stable/](https://jupyter-notebook.readthedocs.io/en/stable/)
