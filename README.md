# Windows cross-assembler for Data General Nova

<img src="asmdemo.png"

This is a Windows .exe file. Write your Nova assembly code in the Source panel, select Assemble in the Action menu (or ctrl-A), and save as absolute binary (File menu).

The assembler implements most of the functionality of the classical Nova assembler, as described in the document
"093-000017-03__Absolute_Assembler_Users_Manual__1973-Nov.001.pdf" at novasareforever.org.

The following pseudo-ops are NOT included: .DALC, .DIAC, .DIO, .DIOA, .DMR, .DMRA, .XPNG, .EOT

The following pseudo-ops ARE included: .DUSR, .LOC, .BLK, .RDX (only radix 8 and 10), .END (autostart parameter supported), .TXT, .TXTE, .TXTO, .TXTF, .TXTM
