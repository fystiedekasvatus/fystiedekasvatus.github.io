---
title: test
lang: en
ref: jupyter-aloitus
category: jupyter
---

# How to Use a Notebook

This page provides quick instructions to get you started with Jupyter Notebooks.

You can also take a look at our [YouTube channel](https://www.youtube.com/channel/UC2HOmLMQsq4EORZzncCyMIg), which contains material used in previous training courses. (Currently only in Finnish)

Jupyter Notebooks consist of text--or Markdown--cells and code cells. The cells can be edited and run. When you run a text cell, it becomes neat article text, which is formatted according to the HTML interpreter Markdown. When you run a code cell, the code is executed, and the cell prints the code's output.

A markdown cell can only be edited in edit mode, which can be accessed by double-clicking the cell. You can write plain text there, and it looks neat. You can also easily add headings, links, images, tables, etc. Instructions for this can be found at [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

Code cells can be written with code in the language used in the Notebook (all our exercises use Python). See the picture below for an example.

![](/assets/img/jupyter-cell-example-en.png)

## Tools in Notebook

![](/assets/img/jupyter-tools-example-en.png)

You select a cell by clicking once and open it in edit mode by clicking again. The cell can be run with the toolbar's "Run" button or with the shortcut Ctrl + Enter . If a cell is selected, it is surrounded by a blue border that turns green in edit mode.

A list of keyboard shortcuts can be found in the “Help” menu on the toolbar (or by pressing “h” without cell selection).

The parentheses on the left side of the cells have a sequence number that indicates in which order the cells have been run. If they are empty, the cell has not been run yet, and if they show an asterisk ( * ), the cell is still running. Sometimes running a cell takes a long time, for example when making animations or loading large files. However, if it takes an unreasonably long time, you may need to interrupt the process using the kernel menu's Interrupt command. 

Sometimes it can also happen that a messy variable is left in the kernel that causes errors in later commands. In this case, it may be appropriate to run the defining cells again or clear all with the “ Restart” commands in the “Kernel” menu (which can also erase previous results or run the entire memo from scratch at once instead of clicking on individual cells). Restarting or interrupting the kernel does not affect the contents of the cells in the memo in any way, but only the results, variables, and similar objects in memory at any given time.

Sometimes it may be that the kernel has saved an incorrect variable or another memory error occurs. In this case, it may be appropriate to run the defining cells again or clear all with the “ Restart” commands in the “Kernel” menu. This does not delete any of your code, it just resets the results and variables that are in memory. After that process, all cells should be run again, but this can also be done with a single command from the menu.




More information:

- [https://jupyter.org/](https://jupyter.org/)
- [https://jupyter-notebook.readthedocs.io/en/stable/](https://jupyter-notebook.readthedocs.io/en/stable/)