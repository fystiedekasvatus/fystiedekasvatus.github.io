---
title: Så delar vi material med MyBinder
lang: en
ref: mybinder
category: omat
---

# Sharing materials with MyBinder

If you want your Notebooks on GitHub to open in MyBinder, you will need to add a file “requirements.txt” to the GitHub repository. The requirements file contains a list of all the python packages (numpy, matplotlib, folium, etc.) that your Notebooks need. You can see an example of such a file [here](https://github.com/opendata-education/Maantiede/blob/main/requirements.txt).

To then get a link that allows others to open your notebook in MyBinder, do the following:

1. Copy the address of your GitHub repo, or the address of the desired Notebook directly - example:[https://github.com/opendata-education/Languages/blob/main/content/exercises/shakespeare.ipynb](https://github.com/opendata-education/Languages/blob/main/content/exercises/shakespeare.ipynb)
2. Go to [https://mybinder.org](https://mybinder.org).
3. In the case of the entire GitHub repo, copy the address in the “GitHub repository name or URL” field. For a single notebook, split the address into fields as follows:
![binder](/assets/img/binder-launch-notebook-arrow-en.png)
4. Copy the link from the “Copy the URL below and share your Binder with others” field and share it with students.
5. You can open the notebook in MyBinder yourself by pressing the “Launch” button. MyBinder builds a virtual workspace from the GitHub repo where you can edit and use notebooks. Note: edits made in the virtual workspace do not change the notebooks in your GitHub repo, but only within the virtual workspace.