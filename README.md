# CyrHack2
All things CyrHack2

## Missing info
Format and purpose for **ttbl** and **ttli** resources from Palm OS 4.x

**ttli** resource is used within
- Latin Locale Module.prc
- System.prc

### ttli1388
```
00000000  00 11 74 74 62 6c 13 88  00 08 74 74 62 6c 13 89  |..ttbl....ttbl..|
00000010  00 40 74 74 62 6c 13 8a  00 44 74 74 62 6c 13 8b  |.@ttbl...Dttbl..|
00000020  00 6c 74 74 62 6c 13 8c  00 70 74 74 62 6c 13 8d  |.lttbl...pttbl..|
00000030  00 80 74 74 62 6c 13 8e  00 84 74 74 62 6c 13 8f  |..ttbl....ttbl..|
00000040  00 50 74 74 62 6c 13 90  00 54 74 74 62 6c 13 91  |.Pttbl...Tttbl..|
00000050  00 58 74 74 62 6c 13 92  00 28 74 74 62 6c 13 8f  |.Xttbl...(ttbl..|
00000060  00 2c 74 74 62 6c 13 93  00 78 74 74 62 6c 13 94  |.,ttbl...xttbl..|
00000070  00 34 74 74 62 6c 13 95  00 3c 74 53 54 4c 13 88  |.4ttbl...<tSTL..|
00000080  00 48 63 73 6c 69 13 88  00 4c                    |.Hcsli...L|
```

### csli388
Contains encoding names, like 'us-ascii', 'iso8859-1' etc.
```
00000000  00 1e 75 73 2d 61 73 63  69 69 00 01 41 53 43 49  |..us-ascii..ASCI|
00000010  49 00 01 49 53 4f 36 34  36 2d 55 53 00 01 75 73  |I..ISO646-US..us|
00000020  00 01 49 42 4d 33 36 37  00 01 63 70 33 36 37 00  |..IBM367..cp367.|
00000030  01 63 73 41 53 43 49 49  00 01 69 73 6f 2d 38 38  |.csASCII..iso-88|
00000040  35 39 2d 31 00 02 69 73  6f 38 38 35 39 2d 31 00  |59-1..iso8859-1.|
00000050  02 6c 61 74 69 6e 31 00  02 6c 31 00 02 49 42 4d  |.latin1..l1..IBM|
00000060  38 31 39 00 02 43 50 38  31 39 00 02 63 73 49 53  |819..CP819..csIS|
00000070  4f 4c 61 74 69 6e 31 00  02 63 70 31 32 35 32 00  |OLatin1..cp1252.|
00000080  07 77 69 6e 64 6f 77 73  2d 31 32 35 32 00 07 77  |.windows-1252..w|
00000090  69 6e 31 32 35 32 00 07  49 53 4f 2d 38 38 35 39  |in1252..ISO-8859|
000000a0  2d 31 2d 57 69 6e 64 6f  77 73 2d 33 2e 31 2d 4c  |-1-Windows-3.1-L|
000000b0  61 74 69 6e 2d 31 00 07  69 73 6f 2d 38 38 35 39  |atin-1..iso-8859|
000000c0  2d 35 00 27 69 73 6f 38  38 35 39 2d 35 00 27 63  |-5.'iso8859-5.'c|
000000d0  70 31 32 35 31 00 26 77  69 6e 64 6f 77 73 2d 31  |p1251.&windows-1|
000000e0  32 35 31 00 26 77 69 6e  31 32 35 31 00 26 4b 4f  |251.&win1251.&KO|
000000f0  49 2d 38 52 00 28 6b 6f  69 2d 38 72 00 28 6b 6f  |I-8R.(koi-8r.(ko|
00000100  69 38 72 00 28 75 6e 69  63 6f 64 65 2d 31 2d 31  |i8r.(unicode-1-1|
00000110  2d 75 63 73 32 00 09 49  53 4f 2d 31 30 36 34 36  |-ucs2..ISO-10646|
00000120  2d 55 43 53 2d 32 00 09  55 54 46 2d 38 00 06 75  |-UCS-2..UTF-8..u|
00000130  6e 69 63 6f 64 65 2d 31  2d 31 2d 75 74 66 38 00  |nicode-1-1-utf8.|
00000140  06                                                |.|
```

### tSTL1388
```
00000000  00 00 07 75 73 2d 61 73  63 69 69 00 49 53 4f 2d  |...us-ascii.ISO-|
00000010  38 38 35 39 2d 31 00 57  69 6e 64 6f 77 73 2d 31  |8859-1.Windows-1|
00000020  32 35 32 00 49 53 4f 2d  38 38 35 39 2d 35 00 57  |252.ISO-8859-5.W|
00000030  69 6e 64 6f 77 73 2d 31  32 35 31 00 4b 4f 49 2d  |indows-1251.KOI-|
00000040  38 52 00 57 69 6e 64 6f  77 73 2d 31 32 35 32 00  |8R.Windows-1252.|
```

## Links
- prc-tools remix https://github.com/jichu4n/prc-tools-remix
- par utility for creating and manipulating .prc and .pdb files http://djw.org/product/palm/par/index.html
- romeo https://romeo.sourceforge.net/
- CloudpilotEmu https://cloudpilot-emu.github.io/app-preview/#/tab/about
