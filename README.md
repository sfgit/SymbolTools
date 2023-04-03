# SymbolTools
Tools for creating schematic symbols in Fusion 360

Getting Started:

1) Copy the pin names from a datasheet (Alt/Opt + Select is a nice way to control the column width of a selection in PDF)
2) Paste into the first column in the spreadsheet (with Macros enabled the text will automatically get converted to upper case)
3) Modify direction, length, etc to suit
4) Select (including the column headings) the table contents to the extent you have pin names
5) Go into Fusion 360 symbol editor and Paste

Notes:

The names of the pins will automatically get "@1, @2, @3" added to them where there are naming collisions, thereby grouping pin names when you map them to pads.  There is a bit more of an "Im Feeling Lucky" mode where if you hold Ctrl / Command when you paste, the SW will try and process the clipboard buffer "as best as possible".  (Only reccomended for those brave souls willing to risk certain-satisfaction for convenience.)

(/SymbolTools/blob/master/Pin%20Paste.gif)

