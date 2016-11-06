# Physical constants font & package for latex

This will be a LaTeX package to use physical symbols, with a tweaked CMU font using Metafont.

## why
Because physical and mathematical constants use letters symbols, whose meanings can be confused with others. 

We propose to create new symbols allowing to visually distinguish the constants from simple variables.

For exemple, `\clight` whould represent the speed of light, `\melec` the electron mass, etc.

A dot added on those letters were the adopted solution.

## with
* Fontforge for the visual tests
* METAFONT to make the characters and insert them directly in the package


# list
## physics
c, G, h, \hbarre, m
## maths
\pi, e, \omega, ...

## links
* [Symbols, units, nomenclature and fundamental constants in physics](http://iupap.org/wp-content/uploads/2014/05/A4.pdf)
* [How do I create a LaTeX package? - TeX stack exchange](http://tex.stackexchange.com/a/34176)
* [Using metafont-letters in LaTeX](http://tex.stackexchange.com/questions/197607/using-metafont-letters-in-latex)
