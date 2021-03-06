# Pascal's Triangle

Yet another [silly programming challenge][1] on c.l.f. 
I just translated some code someone posted in
another language to forth, but it turned out shortest 
so far.

Of course, if someone _really_ wants to compete
on size, [the J language][2] is the way to go!
In J, it's just: `([: ":@-.&0"1 !~/~)@i. 16` 

_Edit 2015-03-23_: I added a straight-forward prolog
version (the file has a `.pl` extension).

_Edit 2015-08-10_: I added a scala port of the forth
version. I did a tail recursive one, but then switched
to a more imperative style to match the forth better.

_Edit 2015-10-06_: I've added golang and haskell versions now.

_Edit 2015-10-12_: I've made a second haskell program, which generates
an infinite triangle, and then prints the first 15 rows.  More idiomatic,
I would guess. More readable than the formula used in the other versions,
in any case, but with the vice of needing the current row in memory
in order to compute the next one. 

```
1
1 1
1 2 1
1 3 3 1
1 4 6 4 1
1 5 10 10 5 1
1 6 15 20 15 6 1
1 7 21 35 35 21 7 1
1 8 28 56 70 56 28 8 1
1 9 36 84 126 126 84 36 9 1
1 10 45 120 210 252 210 120 45 10 1
1 11 55 165 330 462 462 330 165 55 11 1
1 12 66 220 495 792 924 792 495 220 66 12 1
1 13 78 286 715 1287 1716 1716 1287 715 286 78 13 1
1 14 91 364 1001 2002 3003 3432 3003 2002 1001 364 91 14 1
1 15 105 455 1365 3003 5005 6435 6435 5005 3003 1365 455 105 15 1
```

[1]: https://groups.google.com/d/topic/comp.lang.forth/3TTncBdnHjk/discussion
[2]: http://jsoftware.com/
