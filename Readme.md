This is a Python script for making "build sheets" from Eagle .brd files.

Build sheets are outputted as PDFs. Each page highlights
a set of components with the same prefix and same value and shows the position
of each component on the board.

Build sheets are useful for efficiently placing components by hand, particularly
with dense layouts where silkscreens are difficult to read.

Usage:

    python3 buildsheet.py board.brd [layer] out.pdf

Where [layer] is either an Eagle layer number or 'top' or 'bottom'.
