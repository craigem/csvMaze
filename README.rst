CSV Maze
========

This code is based upon `Maze generation (Haskell)`_ by `Rosetta
Code`_ which in turn is based upon `Maze generation algorithm`_ on
`Wikipedia`_.

The goal of this application is to generate CSV files of random mazes so that
they may be used to create mazes in `Minecraft`_ as per **Building a Maze** in
**Adventure 6** of `Adventures in Minecraft`_.

.. _Maze generation (Haskell): http://rosettacode.org/wiki/Maze_generation#Haskell
.. _Rosetta Code: http://rosettacode.org/
.. _Maze generation algorithm: http://en.wikipedia.org/wiki/Maze_generation_algorithm
.. _Wikipedia: http://en.wikipedia.org/
.. _Minecraft: https://minecraft.net/en/
.. _Adventures in Minecraft: http://au.wiley.com/WileyCDA/WileyTitle/productCd-111894691X.html

Release Notes
-------------

**0.1.1**

* Cleaned up CSV output so clean mazes are generated.

**0.1.0**

* Produces output that be piped into a CSV file and used as input for a
  Minecraft maze.
* However does so without an entrance or an exit. Oh my!
