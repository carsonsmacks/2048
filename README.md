2048-python
===========

[![Run on Repl.it](https://repl.it/badge/github/yangshun/2048-python)](https://repl.it/github/yangshun/2048-python)

Based on the popular game [2048](https://github.com/gabrielecirulli/2048) by Gabriele Cirulli. The game's objective is to slide numbered tiles on a grid to combine them to create a tile with the number 2048. Here is a Python version that uses TKinter! 

![screenshot](img/screenshot.png)

To start the game, run:
    
    $ python3 puzzle.py

How to configure 2048-Python
==
After running puzzle.py, a json file called config.json will be created, in this file you will be able to configure 2048-Python.

You can change the controls by changing "default" in line 1 of config.json to your prefered control scheme. 

Current control schemes: default (wasd), qwerty (wasd), azerty (zqsd), vim (khjl)

To add a new control scheme edit constants.py and go to lines 28-32. Format is "name":"controls".

Contributors:
==

- [Yanghun Tay](http://github.com/yangshun)
- [Emmanuel Goh](http://github.com/emman27)
