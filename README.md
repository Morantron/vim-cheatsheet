First things first
==================
:help help

Moving around
=============

:help cursor-motions

* hjkl
* 0 $ _
* gg G
* w e b
* f t F T
* :number numberG
* {} ( avoid holding jk )

PRO TIP: ; to jump to next ocurrence

Inserting text
==============

:help inserting

* I i a O o A

Deleting, fixing small fuckups
==============================

* x, xp ( AKA "the windows move", swaps to characters very quickly )
* r ( replace one chaacter )

Ever typed widht?
try fhxp from the beginning of the line

Line operations
===============

dd
J

Select
======

* v
* V
* <ctrl-v>

Text objects
============

:help text-objects

count + operator + motion

aw iw
ap ap
i([{t

Operators
=========

* c - change
* d - delete ( when you delete, you copy! )
* y - yank ( copy )

PROTIP: paste over selected text

Repeat
======

The power of .

Macros ( complex repeats )
==========================

* set @q ( fix macro )
* use :normal @q to apply macro line by line

Search
======

/
n N
?
.* ( poor man's fuzzy search )
* search word under cursor

CONFIG TIP: smartcase

Jump jump
=========

:help jumps

* <c-i>
* <c-o>
* <c-[>
* gf
* g;

Substitute power
================

:s/foo/bar
:s/foo/bar/g
:%s/foo/bar/g

:%s/somematch/&Lol
:%s/backreferences!/\1,\2

Use custom separators ( useful for URLs )

:%s!https?://www.google.com!http://www.duckduckgo.com!gc

CONFIG TIP: use smartcase
BOOK: Mastering regular expressions

Splits/windows
==============

* <C-w> s
* <C-w> v
* <C-w> c
* <C-w> o
* <C-w> hjkl

CONFIG TIP: remap <C-w> hjkl

Command mode PRO tips
=====================

* <c-r>" ( " / )
* <c-n> <c-p> navigate without cursors
* <c-f> open command-line window ( edit commands in normal mode OMG )
* <c-v> for keystrokes ( useful for macros, you'll see later )

Complete!
=========

* <c-x><c-n> ( complete by word )
* <c-x><c-f> ( complete file path, relative to current directory )
* <c-x><c-l> ( complete a line )
* Use <c-p> <c-n> to go up and down
