# How To

## Metafont


To compile the font and show the result:
    mf file && gftodvi file.2602gf && evince file.dvi

To compile for tex, use:
    mf "\mode=localfont; input file.mf"
Then
    gftopk myfont.???gf myfont.pk
which gives a .tfm and a .pk filse, usable by latex.


