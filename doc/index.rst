|discord|_
|test|_
|stars|_

About
=====

A tetris clone based on https://github.com/nsauzede/vsdl2 in the `Mys
programming language`_.

Project: https://github.com/mys-lang/package-mystris

.. image:: images/screenshot.png

Controls
========

+-----+---------------------------------+
| Key | Description                     |
+=====+=================================+
| Z   | Rotate tetro counterclockwise.  |
+-----+---------------------------------+
| X   | Rotate tetro clockwise.         |
+-----+---------------------------------+
| ⬅   | Move tetro left.                |
+-----+---------------------------------+
| ➡   | Move tetro right.               |
+-----+---------------------------------+
| ⬇   | Move tetro down.                |
+-----+---------------------------------+
| ⬆   | Move tetro up (yeah, right...). |
+-----+---------------------------------+

Installation
============

#. Install SDL libraries.

   .. code-block:: text

      sudo apt install libsdl2-dev libsdl2-ttf-dev libsdl2-mixer-dev libsdl2-image-dev

#. Install and run Mystris.

   .. code-block:: myscon

      ❯ mys install mystris
      ...
       ✔ Building (1.1 seconds)
       ✔ Installing mystris in /home/erik/.local/bin (0 seconds)
      ❯ mystris
      Mystris -- tribute to venerable Twintris

.. |discord| image:: https://img.shields.io/discord/777073391320170507?label=Discord&logo=discord&logoColor=white
.. _discord: https://discord.gg/GFDN7JvWKS

.. |test| image:: https://github.com/mys-lang/package-mystris/actions/workflows/pythonpackage.yml/badge.svg
.. _test: https://github.com/mys-lang/package-mystris/actions/workflows/pythonpackage.yml

.. |stars| image:: https://img.shields.io/github/stars/mys-lang/package-mystris?style=social
.. _stars: https://github.com/mys-lang/package-mystris

.. _Mys programming language: https://mys-lang.org
