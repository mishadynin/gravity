# Test your knowledge of physics and C

This C program measures acceleration due to gravity.&nbsp;
When run without any arguments, it prints the exact
[value of **g**](http://physics.nist.gov/cgi-bin/cuu/Value?gn)
in SI units (m/s^2^).

Instructions: [download the program text]
(https://raw.githubusercontent.com/mishadynin/gravity/master/g.c),
save it to a file, compile and run it.  It is *very important*
that you preserve the formatting: if you delete or add a single newline,
the program will not work!

```C
#define O +\
__LI\
NE__\
,46-\
__LI\
NE__
char
g[]
={
46
O       O









        O

        O







        O







        O






        O



};main(   ){puts(g);}
```

To understand the program, print out the source and look at it from
some distance.&nbsp;
The apparatus at the top is the particle dispenser; `O`'s
are falling particles, and at the bottom there's a photodector
connected to a very precise timer.&nbsp;  The program works by measuring
the time it takes for a particle to fall from the top of the program
to the bottom.

You can reproduce [Galileo's famous experiment]
(https://en.wikipedia.org/wiki/Galileo%27s_Leaning_Tower_of_Pisa_experiment)
by changing `O` to another letter and verifying that the value of
acceleration doesn't change.

FIXME: current version of the program works only on Earth;
support for other planets will be added in later revisions.&nbsp;
If you live on Mars and want to be a beta-tester, please
[contact me](http://mishadynin.com/#contact).

:wink:

---

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img
  alt="Creative Commons License" style="border-width:0"
  src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>  
This work is licensed under a <a rel="license"
  href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons
  Attribution-ShareAlike 4.0 International License</a>.
