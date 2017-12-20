# final
Final Assignment

1. Modify the polynomial object written in class to trigonometric polynomials in cos(x) and sin(x), for example the following is a trigonometric polynomial

f(x) = 3*cos(3 x) + 7.1 sin(2 x) + 0.3 sin(x) - 3

2. The following code assumes a class named myobj which represent strings. Building a myobj object such that the following code works

~~~

luke    = myobj("Luke")
hansolo = myobj("Han Solo")
leia    = myobj("Leia")
yoda    = myobj("Yoda")
padme   = myobj("Padme Amidala")
anakin  = myobj("Anakin Skywalker")
obi     = myobj("Obi-Wan")
darth   = myobj("Darth Vader")
_all    = myobj("All")


luke.add_dependency(hansolo, leia, yoda)
leia.add_dependency(padme, anakin)
obi.add_dependency(yoda)
darth.add_dependency(anakin)

_all.add_dependency(luke, hansolo, leia, yoda, padme, anakin, obi, darth)
_all.build()
# code should print: 
Han Solo 
Padme Amidala 
Anakin Skywalker 
Leia
Yoda 
Luke 
Obi-Wan 
Darth Vader
# (can print with newlines in between modules)

~~~
from https://www.ynonperek.com/2017/09/21/python-exercises/

