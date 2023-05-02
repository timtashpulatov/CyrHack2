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

### csli1388
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

### ttbl1388
```
00000000  00 80 00 80 00 80 00 80  00 80 00 80 00 80 00 80  |................|
00000010  00 80 00 40 00 40 00 40  00 40 00 40 00 80 00 80  |...@.@.@.@.@....|
00000020  00 80 00 80 00 80 00 80  00 08 00 08 00 08 00 08  |................|
00000030  00 08 01 04 00 80 00 80  00 80 00 80 00 80 00 80  |................|
00000040  00 04 00 08 00 08 00 08  00 08 00 08 00 08 00 08  |................|
00000050  00 08 00 08 00 08 00 08  00 08 00 08 00 08 00 08  |................|
00000060  00 21 00 21 00 21 00 21  00 21 00 21 00 21 00 21  |.!.!.!.!.!.!.!.!|
00000070  00 21 00 21 00 08 00 08  00 08 00 08 00 08 00 08  |.!.!............|
00000080  00 08 00 03 00 03 00 03  00 03 00 03 00 03 00 02  |................|
00000090  00 02 00 02 00 02 00 02  00 02 00 02 00 02 00 02  |................|
000000a0  00 02 00 02 00 02 00 02  00 02 00 02 00 02 00 02  |................|
000000b0  00 02 00 02 00 02 00 08  00 08 00 08 00 08 00 08  |................|
000000c0  00 08 00 11 00 11 00 11  00 11 00 11 00 11 00 10  |................|
000000d0  00 10 00 10 00 10 00 10  00 10 00 10 00 10 00 10  |................|
000000e0  00 10 00 10 00 10 00 10  00 10 00 10 00 10 00 10  |................|
000000f0  00 10 00 10 00 10 00 08  00 08 00 08 00 08 00 80  |................|
00000100  00 08 00 00 00 08 02 10  00 08 00 08 00 08 00 08  |................|
00000110  00 08 00 08 02 02 00 08  02 02 00 00 00 00 00 00  |................|
00000120  00 00 00 08 00 08 00 08  00 08 00 08 00 08 00 08  |................|
00000130  00 08 00 08 02 10 00 08  02 10 00 00 00 00 02 02  |................|
00000140  01 04 00 08 00 08 00 08  00 08 00 08 00 08 00 08  |................|
00000150  02 02 00 08 00 08 00 08  00 08 00 08 00 08 00 08  |................|
00000160  00 08 00 08 00 08 00 08  00 08 00 08 00 08 00 08  |................|
00000170  02 10 00 08 00 08 00 08  00 08 00 08 00 08 00 08  |................|
00000180  02 02 02 02 02 02 02 02  02 02 02 02 02 02 02 02  |................|
00000190  02 02 02 02 02 02 02 02  02 02 02 02 02 02 02 02  |................|
000001a0  02 02 02 02 02 02 02 02  02 02 02 02 02 02 02 02  |................|
000001b0  02 02 02 02 02 02 02 02  02 02 02 02 02 02 02 02  |................|
000001c0  02 10 02 10 02 10 02 10  02 10 02 10 02 10 02 10  |................|
000001d0  02 10 02 10 02 10 02 10  02 10 02 10 02 10 02 10  |................|
000001e0  02 10 02 10 02 10 02 10  02 10 02 10 02 10 02 10  |................|
000001f0  02 10 02 10 02 10 02 10  02 10 02 10 02 10 02 10  |................|
```

### ttbl1389
```
00000000  00 09 00 02 80 00 00 00  00 80 00 ff 00 00 00 01  |................|
00000010  00 08 00 00 00 08 00 00  00 9a 07 07 07 07 07 07  |................|
00000020  07 07 07 07 07 07 07 07  07 07 07 07 07 07 07 07  |................|
00000030  07 07 07 07 07 07 07 07  07 07 02 02 02 02 02 02  |................|
00000040  02 02 26 02 02 02 02 02  02 02 02 02 02 02 02 02  |..&.............|
00000050  02 02 26 02 02 02 02 02  02 02 26 26 26 26 26 26  |..&.......&&&&&&|
00000060  26 26 26 26 26 26 26 26  26 26 26 26 26 26 26 26  |&&&&&&&&&&&&&&&&|
00000070  26 26 26 26 26 26 26 26  26 26 26 26 26 26 26 26  |&&&&&&&&&&&&&&&&|
00000080  26 26 26 26 26 26 26 26  26 26 26 26 26 26 26 26  |&&&&&&&&&&&&&&&&|
00000090  26 26 26 26 26 26 26 26  26 26                    |&&&&&&&&&&|
```

### ttbl138a
```
00000000  00 09 00 02 80 00 00 00  00 00 00 07 00 00 00 ff  |................|
00000010  00 08 00 00 00 08 00 00  00 22 ff 00 01 03 ff ff  |........."......|
00000020  ff 02                                             |..|
```

### ttbl138b
```
00000000  00 09 00 01 e0 00 00 00  00 00 00 ff 00 00 ff ff  |................|
00000010  00 10 00 00 00 10 00 00  02 1a 00 00 00 01 00 02  |................|
00000020  00 03 00 04 00 05 00 06  00 07 00 08 00 09 00 0a  |................|
00000030  00 0b 00 0c 00 0d 00 0e  00 0f 00 10 00 11 00 12  |................|
00000040  00 13 00 14 00 15 00 16  00 17 00 18 00 19 00 1a  |................|
00000050  00 1b 00 1c 00 1d 00 1e  00 1f 00 20 00 21 00 22  |........... .!."|
00000060  00 23 00 24 00 25 00 26  00 27 00 28 00 29 00 2a  |.#.$.%.&.'.(.).*|
00000070  00 2b 00 2c 00 2d 00 2e  00 2f 00 30 00 31 00 32  |.+.,.-.../.0.1.2|
00000080  00 33 00 34 00 35 00 36  00 37 00 38 00 39 00 3a  |.3.4.5.6.7.8.9.:|
00000090  00 3b 00 3c 00 3d 00 3e  00 3f 00 40 00 41 00 42  |.;.<.=.>.?.@.A.B|
000000a0  00 43 00 44 00 45 00 46  00 47 00 48 00 49 00 4a  |.C.D.E.F.G.H.I.J|
000000b0  00 4b 00 4c 00 4d 00 4e  00 4f 00 50 00 51 00 52  |.K.L.M.N.O.P.Q.R|
000000c0  00 53 00 54 00 55 00 56  00 57 00 58 00 59 00 5a  |.S.T.U.V.W.X.Y.Z|
000000d0  00 5b 00 5c 00 5d 00 5e  00 5f 00 60 00 61 00 62  |.[.\.].^._.`.a.b|
000000e0  00 63 00 64 00 65 00 66  00 67 00 68 00 69 00 6a  |.c.d.e.f.g.h.i.j|
000000f0  00 6b 00 6c 00 6d 00 6e  00 6f 00 70 00 71 00 72  |.k.l.m.n.o.p.q.r|
00000100  00 73 00 74 00 75 00 76  00 77 00 78 00 79 00 7a  |.s.t.u.v.w.x.y.z|
00000110  00 7b 00 7c 00 7d 00 7e  00 7f 20 ac ff ff 20 1a  |.{.|.}.~.. ... .|
00000120  01 92 20 1e 20 26 20 20  20 21 02 c6 20 30 01 60  |.. . &   !.. 0.`|
00000130  20 39 01 52 ff ff 01 7d  ff ff ff ff 20 18 20 19  | 9.R...}.... . .|
00000140  20 1c 20 1d 20 22 20 13  20 14 02 dc 21 22 01 61  | . . " . ...!".a|
00000150  20 3a 01 53 ff ff 01 7e  01 78 00 a0 00 a1 00 a2  | :.S...~.x......|
00000160  00 a3 00 a4 00 a5 00 a6  00 a7 04 01 00 a9 00 aa  |................|
00000170  00 ab 00 ac 00 ad 00 ae  00 af 00 b0 00 b1 00 b2  |................|
00000180  00 b3 00 b4 00 b5 00 b6  00 b7 04 51 00 b9 00 ba  |...........Q....|
00000190  00 bb 00 bc 00 bd 00 be  00 bf 04 10 04 11 04 12  |................|
000001a0  04 13 04 14 04 15 04 16  04 17 04 18 04 19 04 1a  |................|
000001b0  04 1b 04 1c 04 1d 04 1e  04 1f 04 20 04 21 04 22  |........... .!."|
000001c0  04 23 04 24 04 25 04 26  04 27 04 28 04 29 04 2a  |.#.$.%.&.'.(.).*|
000001d0  04 2b 04 2c 04 2d 04 2e  04 2f 04 30 04 31 04 32  |.+.,.-.../.0.1.2|
000001e0  04 33 04 34 04 35 04 36  04 37 04 38 04 39 04 3a  |.3.4.5.6.7.8.9.:|
000001f0  04 3b 04 3c 04 3d 04 3e  04 3f 04 40 04 41 04 42  |.;.<.=.>.?.@.A.B|
00000200  04 43 04 44 04 45 04 46  04 47 04 48 04 49 04 4a  |.C.D.E.F.G.H.I.J|
00000210  04 4b 04 4c 04 4d 04 4e  04 4f                    |.K.L.M.N.O|
```

### ttbl138c
```
00000000  00 09 00 04 80 00 00 00  00 00 21 22 00 00 ff ff  |..........!"....|
00000010  00 08 00 00 00 08 00 00  01 ce 00 5e 01 44 01 58  |...........^.D.X|
00000020  00 00 01 86 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00000030  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00000040  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00000050  00 00 00 00 00 00 00 00  00 00 01 60 01 80 00 e6  |...........`....|
00000060  00 80 00 01 02 03 04 05  06 07 08 09 0a 0b 0c 0d  |................|
00000070  0e 0f 10 11 12 13 14 15  16 17 18 19 1a 1b 1c 1d  |................|
00000080  1e 1f 20 21 22 23 24 25  26 27 28 29 2a 2b 2c 2d  |.. !"#$%&'()*+,-|
00000090  2e 2f 30 31 32 33 34 35  36 37 38 39 3a 3b 3c 3d  |./0123456789:;<=|
000000a0  3e 3f 40 41 42 43 44 45  46 47 48 49 4a 4b 4c 4d  |>?@ABCDEFGHIJKLM|
000000b0  4e 4f 50 51 52 53 54 55  56 57 58 59 5a 5b 5c 5d  |NOPQRSTUVWXYZ[\]|
000000c0  5e 5f 60 61 62 63 64 65  66 67 68 69 6a 6b 6c 6d  |^_`abcdefghijklm|
000000d0  6e 6f 70 71 72 73 74 75  76 77 78 79 7a 7b 7c 7d  |nopqrstuvwxyz{|}|
000000e0  7e 7f a0 60 a0 a1 a2 a3  a4 a5 a6 a7 a8 a9 aa ab  |~..`............|
000000f0  ac ad ae af b0 b1 b2 b3  b4 b5 b6 b7 b8 b9 ba bb  |................|
00000100  bc bd be bf c0 c1 c2 c3  c4 c5 c6 c7 c8 c9 ca cb  |................|
00000110  cc cd ce cf d0 d1 d2 d3  d4 d5 d6 d7 d8 d9 da db  |................|
00000120  dc dd de df e0 e1 e2 e3  e4 e5 e6 e7 e8 e9 ea eb  |................|
00000130  ec ed ee ef f0 f1 f2 f3  f4 f5 f6 f7 f8 f9 fa fb  |................|
00000140  fc fd fe ff 00 14 52 02  8c 9c 0e 02 8a 9a 18 01  |......R.........|
00000150  9f 05 02 8e 9e 15 01 83  00 08 c6 01 88 16 01 98  |................|
00000160  00 20 13 02 96 97 05 0b  91 92 82 00 93 94 84 00  |. ..............|
00000170  86 87 95 0e 01 85 0a 01  89 09 02 8b 9b 73 01 80  |.............s..|
00000180  00 05 22 01 99 00 00 48  01 01 a8 0f 41 c0 c1 c2  |.."....H....A...|
00000190  c3 c4 c5 c6 c7 c8 c9 ca  cb cc cd ce cf d0 d1 d2  |................|
000001a0  d3 d4 d5 d6 d7 d8 d9 da  db dc dd de df e0 e1 e2  |................|
000001b0  e3 e4 e5 e6 e7 e8 e9 ea  eb ec ed ee ef f0 f1 f2  |................|
000001c0  f3 f4 f5 f6 f7 f8 f9 fa  fb fc fd fe ff b8        |..............|
```

### ttbl138d
Most likely contains table for uppercase conversion
```
00000000  00 09 00 01 e0 00 00 00  00 00 00 ff 00 00 00 00  |................|
00000010  00 08 00 00 00 08 00 00  01 1a 00 01 02 03 04 05  |................|
00000020  06 07 08 09 0a 0b 0c 0d  0e 0f 10 11 12 13 14 15  |................|
00000030  16 17 18 19 1a 1b 1c 1d  1e 1f 20 21 22 23 24 25  |.......... !"#$%|
00000040  26 27 28 29 2a 2b 2c 2d  2e 2f 30 31 32 33 34 35  |&'()*+,-./012345|
00000050  36 37 38 39 3a 3b 3c 3d  3e 3f 40 41 42 43 44 45  |6789:;<=>?@ABCDE|
00000060  46 47 48 49 4a 4b 4c 4d  4e 4f 50 51 52 53 54 55  |FGHIJKLMNOPQRSTU|
00000070  56 57 58 59 5a 5b 5c 5d  5e 5f 60 41 42 43 44 45  |VWXYZ[\]^_`ABCDE|
00000080  46 47 48 49 4a 4b 4c 4d  4e 4f 50 51 52 53 54 55  |FGHIJKLMNOPQRSTU|
00000090  56 57 58 59 5a 7b 7c 7d  7e 7f 80 81 82 83 84 85  |VWXYZ{|}~.......|
000000a0  86 87 88 89 8a 8b 8c 8d  8e 8f 90 91 92 93 94 95  |................|
000000b0  96 97 98 99 8a 9b 8c 9d  8e 9f a0 a1 a2 a3 a4 a5  |................|
000000c0  a6 a7 a8 a9 aa ab ac ad  ae af b0 b1 b2 b3 b4 b5  |................|
000000d0  b6 b7 a8 b9 ba bb bc bd  be bf c0 c1 c2 c3 c4 c5  |................|
000000e0  c6 c7 c8 c9 ca cb cc cd  ce cf d0 d1 d2 d3 d4 d5  |................|
000000f0  d6 d7 d8 d9 da db dc dd  de df c0 c1 c2 c3 c4 c5  |................|
00000100  c6 c7 c8 c9 ca cb cc cd  ce cf d0 d1 d2 d3 d4 d5  |................|
00000110  d6 d7 d8 d9 da db dc dd  de df                    |..........|
```

### ttbl138e
Most likely contains table for lowercase conversion
```
00000000  00 09 00 01 e0 00 00 00  00 00 00 ff 00 00 00 00  |................|
00000010  00 08 00 00 00 08 00 00  01 1a 00 01 02 03 04 05  |................|
00000020  06 07 08 09 0a 0b 0c 0d  0e 0f 10 11 12 13 14 15  |................|
00000030  16 17 18 19 1a 1b 1c 1d  1e 1f 20 21 22 23 24 25  |.......... !"#$%|
00000040  26 27 28 29 2a 2b 2c 2d  2e 2f 30 31 32 33 34 35  |&'()*+,-./012345|
00000050  36 37 38 39 3a 3b 3c 3d  3e 3f 40 61 62 63 64 65  |6789:;<=>?@abcde|
00000060  66 67 68 69 6a 6b 6c 6d  6e 6f 70 71 72 73 74 75  |fghijklmnopqrstu|
00000070  76 77 78 79 7a 5b 5c 5d  5e 5f 60 61 62 63 64 65  |vwxyz[\]^_`abcde|
00000080  66 67 68 69 6a 6b 6c 6d  6e 6f 70 71 72 73 74 75  |fghijklmnopqrstu|
00000090  76 77 78 79 7a 7b 7c 7d  7e 7f 80 81 82 83 84 85  |vwxyz{|}~.......|
000000a0  86 87 88 89 9a 8b 9c 8d  9e 8f 90 91 92 93 94 95  |................|
000000b0  96 97 98 99 9a 9b 9c 9d  9e 9f a0 a1 a2 a3 a4 a5  |................|
000000c0  a6 a7 b8 a9 aa ab ac ad  ae af b0 b1 b2 b3 b4 b5  |................|
000000d0  b6 b7 b8 b9 ba bb bc bd  be bf e0 e1 e2 e3 e4 e5  |................|
000000e0  e6 e7 e8 e9 ea eb ec ed  ee ef f0 f1 f2 f3 f4 f5  |................|
000000f0  f6 f7 f8 f9 fa fb fc fd  fe ff e0 e1 e2 e3 e4 e5  |................|
00000100  e6 e7 e8 e9 ea eb ec ed  ee ef f0 f1 f2 f3 f4 f5  |................|
00000110  f6 f7 f8 f9 fa fb fc fd  fe ff                    |..........|
```

### ttbl138f
```
00000000  00 01 02 03 04 05 06 07  08 2a 2b 2c 2d 2e 09 0a  |.........*+,-...|
00000010  0b 0c 0d 0e 0f 10 11 12  13 14 15 16 17 18 19 1a  |................|
00000020  28 2f 30 31 32 33 34 23  35 36 37 5a 38 24 39 3a  |(/01234#567Z8$9:|
00000030  73 77 79 7b 7d 7e 7f 80  81 82 3b 3c 5b 5c 5d 3d  |swy{}~....;<[\]=|
00000040  3e 83 84 85 86 88 89 8a  8b 8c 8d 8e 8f 90 91 92  |>...............|
00000050  94 95 96 97 98 9a 9b 9c  9d 9e 9f 3f 40 41 42 44  |...........?@ABD|
00000060  45 83 84 85 86 88 89 8a  8b 8c 8d 8e 8f 90 91 92  |E...............|
00000070  94 95 96 97 98 9a 9b 9c  9d 9e 9f 46 47 48 49 1b  |...........FGHI.|
00000080  65 1c 54 89 57 71 6e 6f  43 72 97 58 93 1d 1e 1f  |e.T.WqnoCr.X....|
00000090  20 52 53 55 56 70 26 27  51 99 97 59 93 21 22 9e  | RSUVp&'Q..Y.!".|
000000a0  29 4a 61 62 63 64 4b 66  a6 67 83 5f 68 25 69 4d  |)JabcdKf.g._h%iM|
000000b0  6a 5e 7a 7c 4e 6b 6c 6d  a6 78 92 60 74 75 76 50  |j^z|Nklm.x.`tuvP|
000000c0  a0 a1 a2 a3 a4 a5 a7 a8  a9 aa ab ac ad ae af b0  |................|
000000d0  b1 b2 b3 b4 b5 b6 b7 b8  b9 ba bb bc bd be bf c0  |................|
000000e0  a0 a1 a2 a3 a4 a5 a7 a8  a9 aa ab ac ad ae af b0  |................|
000000f0  b1 b2 b3 b4 b5 b6 b7 b8  b9 ba bb bc bd be bf c0  |................|
```

### ttbl1390
```
00000000  00 01 02 03 04 05 06 07  08 29 2a 2b 2c 2d 09 0a  |.........)*+,-..|
00000010  0b 0c 0d 0e 0f 10 11 12  13 14 15 16 17 18 19 1a  |................|
00000020  27 2e 2f 30 31 32 33 22  34 35 36 57 37 23 38 39  |'./0123"456W7#89|
00000030  70 74 76 78 7a 7b 7c 7d  7e 7f 3a 3b 58 59 5a 3c  |ptvxz{|}~.:;XYZ<|
00000040  3d 80 82 83 84 85 86 88  89 8a 8b 8c 8d 8e 8f 90  |=...............|
00000050  93 94 95 96 98 9a 9b 9c  9d 9e a0 3e 3f 40 41 43  |...........>?@AC|
00000060  44 80 82 83 84 85 86 88  89 8a 8b 8c 8d 8e 8f 90  |D...............|
00000070  93 94 95 96 98 9a 9b 9c  9d 9e a0 45 46 47 48 1b  |...........EFGH.|
00000080  62 1c 51 87 54 6e 6b 6c  42 6f 97 55 92 1d 21 1e  |b.Q.TnklBo.U..!.|
00000090  1f 4f 50 52 53 6d 25 26  4e 99 97 56 92 20 21 9f  |.OPRSm%&N..V. !.|
000000a0  28 49 5e 5f 60 61 4a 63  a7 64 81 5c 65 24 66 4b  |(I^_`aJc.d.\e$fK|
000000b0  67 5b 77 79 4c 68 69 6a  a7 75 91 5d 71 72 73 4d  |g[wyLhij.u.]qrsM|
000000c0  a1 a2 a3 a4 a5 a6 a8 a9  aa ab ac ad ae af b0 b1  |................|
000000d0  b2 b3 b4 b5 b6 b7 b8 b9  ba bb bc bd be bf c0 c1  |................|
000000e0  a1 a2 a3 a4 a5 a6 a8 a9  aa ab ac ad ae af b0 b1  |................|
000000f0  b2 b3 b4 b5 b6 b7 b8 b9  ba bb bc bd be bf c0 c1  |................|
```

### ttbl1391
```
00000000  00 01 02 03 04 05 06 07  08 2a 2b 2c 2d 2e 09 0a  |.........*+,-...|
00000010  0b 0c 0d 0e 0f 10 11 12  13 14 15 16 17 18 19 1a  |................|
00000020  28 2f 30 31 32 33 34 23  35 36 37 58 38 24 39 3a  |(/01234#567X8$9:|
00000030  71 75 77 79 7b 7c 7d 7e  7f 80 3b 3c 59 5a 5b 3d  |quwy{|}~..;<YZ[=|
00000040  3e 82 85 87 89 8b 8d 90  92 94 96 98 9a 9c 9e a0  |>...............|
00000050  a5 a7 a9 ab af b2 b4 b6  b8 ba bd 3f 40 41 42 44  |...........?@ABD|
00000060  45 81 84 86 88 8a 8c 8f  91 93 95 97 99 9b 9d 9f  |E...............|
00000070  a4 a6 a8 aa ae b1 b3 b5  b7 b9 bc 46 47 48 49 1b  |...........FGHI.|
00000080  63 1c 52 8e 55 6f 6c 6d  43 70 ad 56 a3 1d 1e 1f  |c.R.UolmCp.V....|
00000090  20 50 51 53 54 6e 26 27  4f b0 ac 57 a2 21 22 bb  | PQSTn&'O..W.!".|
000000a0  29 4a 5f 60 61 62 4b 64  cb 65 83 5d 66 25 67 4c  |)J_`abKd.e.]f%gL|
000000b0  68 5c 78 7a 4d 69 6a 6b  ca 76 a1 5e 72 73 74 4e  |h\xzMijk.v.^rstN|
000000c0  bf c1 c3 c5 c7 c9 cd cf  d1 d3 d5 d7 d9 db dd df  |................|
000000d0  e1 e3 e5 e7 e9 eb ed ef  f1 f3 f5 f7 f9 fb fd ff  |................|
000000e0  be c0 c2 c4 c6 c8 cc ce  d0 d2 d4 d6 d8 da dc de  |................|
000000f0  e0 e2 e4 e6 e8 ea ec ee  f0 f2 f4 f6 f8 fa fc fe  |................|
```

### ttbl1392
```
00000000  00 09 00 01 e0 00 00 00  00 00 00 ff 00 00 00 00  |................|
00000010  00 08 00 00 00 08 00 00  01 1a 01 01 01 01 01 01  |................|
00000020  01 01 01 01 01 01 01 01  01 01 01 01 01 01 01 01  |................|
00000030  01 01 01 01 01 01 01 01  01 01 01 01 01 01 01 01  |................|
00000040  01 01 01 01 01 01 01 01  01 01 00 00 00 00 00 00  |................|
00000050  00 00 00 00 01 01 01 01  01 01 01 00 00 00 00 00  |................|
00000060  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00000070  00 00 00 00 00 01 01 01  01 01 01 00 00 00 00 00  |................|
00000080  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00000090  00 00 00 00 00 01 01 01  01 01 01 01 01 00 01 01  |................|
000000a0  01 01 01 01 00 01 00 01  01 01 01 01 01 01 01 01  |................|
000000b0  01 01 01 01 00 01 00 01  01 00 01 01 01 01 01 01  |................|
000000c0  01 01 00 01 01 01 01 01  01 01 01 01 01 01 01 01  |................|
000000d0  01 01 00 01 01 01 01 01  01 01 00 00 00 00 00 00  |................|
000000e0  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
000000f0  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00000100  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  |................|
00000110  00 00 00 00 00 00 00 00  00 00                    |..........|
```

### ttbl1393
```
00000000  00 09 00 08 40 00 00 00  00 00 00 ff 01 00 00 00  |....@...........|
00000010  00 10 00 00 00 10 00 00  01 4e 00 0c 00 04 00 03  |.........N......|
00000020  03 03 03 03 03 03 03 00  00 03 03 03 03 03 03 03  |................|
00000030  03 03 03 03 03 03 03 03  03 03 03 03 03 03 00 03  |................|
00000040  03 03 03 03 03 03 03 03  03 03 03 01 03 03 03 03  |................|
00000050  03 03 03 03 03 03 03 03  03 03 03 03 03 03 03 02  |................|
00000060  02 02 02 02 02 02 02 02  02 02 02 02 02 02 02 02  |................|
00000070  02 02 02 02 02 02 02 02  02 03 03 03 03 03 03 02  |................|
00000080  02 02 02 02 02 02 02 02  02 02 02 02 02 02 02 02  |................|
00000090  02 02 02 02 02 02 02 02  02 03 03 03 03 03 03 03  |................|
000000a0  03 02 03 03 03 03 03 03  02 03 02 03 03 03 03 03  |................|
000000b0  03 03 03 03 01 01 03 03  02 03 02 03 03 02 03 03  |................|
000000c0  03 03 03 03 03 03 02 03  03 03 03 03 03 03 03 03  |................|
000000d0  03 03 03 03 03 03 02 03  03 03 03 03 03 03 02 02  |................|
000000e0  02 02 02 02 02 02 02 02  02 02 02 02 02 02 02 02  |................|
000000f0  02 02 02 02 02 02 02 02  02 02 02 02 02 02 02 02  |................|
00000100  02 02 02 02 02 02 02 02  02 02 02 02 02 02 02 02  |................|
00000110  02 02 02 02 02 02 02 02  02 02 02 02 02 02 23 00  |..............#.|
00000120  00 00 02 02 00 00 02 01  00 00 02 02 00 00 23 00  |..............#.|
00000130  00 01 23 00 00 01 02 01  00 00 02 02 00 00 23 00  |..#...........#.|
00000140  00 01 02 02 00 00 02 01  00 00 02 02 00 00        |..............|
```

### ttbl1394
```
00000000  00 09 00 08 40 00 00 00  00 00 00 ff 01 00 00 00  |....@...........|
00000010  00 10 00 00 00 10 00 00  03 5a 00 8f 00 0d 00 01  |.........Z......|
00000020  01 01 01 01 01 01 01 01  01 01 01 01 01 01 01 01  |................|
00000030  01 01 01 01 01 01 01 01  01 01 01 01 01 01 0c 01  |................|
00000040  01 01 08 09 01 06 01 01  01 01 0a 07 0b 0a 04 04  |................|
00000050  04 04 04 04 04 04 04 04  0a 01 01 01 01 01 01 03  |................|
00000060  03 03 03 03 03 03 03 03  03 03 03 03 03 03 03 03  |................|
00000070  03 03 03 03 03 03 03 03  03 01 01 01 01 01 01 03  |................|
00000080  03 03 03 03 03 03 03 03  03 03 03 03 03 03 03 03  |................|
00000090  03 03 03 03 03 03 03 03  03 01 01 01 01 01 08 01  |................|
000000a0  01 03 01 01 01 01 01 09  03 01 03 01 03 01 01 01  |................|
000000b0  06 01 01 01 05 05 01 01  03 01 03 01 03 03 02 01  |................|
000000c0  09 08 08 08 01 01 03 01  01 01 01 05 01 01 09 01  |................|
000000d0  01 01 01 03 01 01 03 01  01 01 01 01 01 01 03 03  |................|
000000e0  03 03 03 03 03 03 03 03  03 03 03 03 03 03 03 03  |................|
000000f0  03 03 03 03 03 03 03 03  03 03 03 03 03 03 03 03  |................|
00000100  03 03 03 03 03 03 03 03  03 03 03 03 03 03 03 03  |................|
00000110  03 03 03 03 03 03 03 03  03 03 03 03 03 03 25 00  |..............%.|
00000120  00 00 02 01 00 00 02 00  00 00 02 02 00 00 02 03  |................|
00000130  00 00 02 04 00 00 02 06  00 00 02 04 00 00 02 09  |................|
00000140  00 00 02 05 00 00 02 05  00 00 02 06 00 00 02 0a  |................|
00000150  00 00 25 00 00 00 25 00  00 00 02 00 00 00 25 00  |..%...%.......%.|
00000160  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000170  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000180  00 00 25 00 00 00 25 00  00 00 25 00 00 00 02 00  |..%...%...%.....|
00000190  00 00 02 02 00 00 02 03  00 00 08 07 00 00 08 07  |................|
000001a0  00 00 08 07 00 00 25 00  00 00 25 00 00 00 25 00  |......%...%...%.|
000001b0  00 00 08 07 00 00 25 00  00 00 25 00 00 00 25 00  |......%...%...%.|
000001c0  00 00 02 00 00 00 02 02  00 00 02 03 00 00 25 00  |..............%.|
000001d0  00 00 08 08 00 00 02 01  00 00 02 09 00 00 25 00  |..............%.|
000001e0  00 00 08 08 00 00 02 05  00 00 25 00 00 00 25 00  |..........%...%.|
000001f0  00 00 25 00 00 00 02 00  00 00 02 02 00 00 25 00  |..%...........%.|
00000200  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000210  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000220  00 00 25 00 00 00 25 00  00 00 02 00 00 00 25 00  |..%...%.......%.|
00000230  00 00 02 03 00 00 25 00  00 00 25 00 00 00 25 00  |......%...%...%.|
00000240  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000250  00 00 25 00 00 00 25 00  00 00 25 00 00 00 02 00  |..%...%...%.....|
00000260  00 00 02 02 00 00 02 03  00 00 25 00 00 00 25 00  |..........%...%.|
00000270  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000280  00 00 25 00 00 00 25 00  00 00 25 00 00 00 2d 00  |..%...%...%...-.|
00000290  00 00 02 00 00 00 02 02  00 00 2d 00 00 00 2d 00  |..........-...-.|
000002a0  00 00 2d 00 00 00 25 00  00 00 2d 00 00 00 2d 00  |..-...%...-...-.|
000002b0  00 00 2d 00 00 00 2d 00  00 00 2d 00 00 00 25 00  |..-...-...-...%.|
000002c0  00 00 2d 00 00 00 02 00  00 00 2d 00 00 00 02 03  |..-.......-.....|
000002d0  00 00 2d 00 00 00 2d 00  00 00 25 00 00 00 2d 00  |..-...-...%...-.|
000002e0  00 00 2d 00 00 00 2d 00  00 00 2d 00 00 00 2d 00  |..-...-...-...-.|
000002f0  00 00 25 00 00 00 25 00  00 00 02 00 00 00 25 00  |..%...%.......%.|
00000300  00 00 25 00 00 00 25 00  00 00 25 00 00 00 02 01  |..%...%...%.....|
00000310  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000320  00 00 25 00 00 00 25 00  00 00 25 00 00 00 02 00  |..%...%...%.....|
00000330  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000340  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000350  00 00 25 00 00 00 02 0a  00 00                    |..%.......|
```

### ttbl1395
```
00000000  00 09 00 09 40 00 00 00  00 00 00 ff 01 00 00 00  |....@...........|
00000010  00 10 00 00 00 10 00 00  02 f2 00 75 00 0d 00 01  |...........u....|
00000020  01 01 01 01 01 01 01 01  01 01 01 01 01 01 01 01  |................|
00000030  01 01 01 01 01 01 01 01  01 01 01 01 01 01 0c 01  |................|
00000040  01 01 08 09 01 06 01 01  01 01 0a 07 0b 0a 04 04  |................|
00000050  04 04 04 04 04 04 04 04  0a 01 01 01 01 01 01 03  |................|
00000060  03 03 03 03 03 03 03 03  03 03 03 03 03 03 03 03  |................|
00000070  03 03 03 03 03 03 03 03  03 01 01 01 01 01 01 03  |................|
00000080  03 03 03 03 03 03 03 03  03 03 03 03 03 03 03 03  |................|
00000090  03 03 03 03 03 03 03 03  03 01 01 01 01 01 08 01  |................|
000000a0  01 03 01 01 01 01 01 09  03 01 03 01 03 01 01 01  |................|
000000b0  06 01 01 01 05 05 01 01  03 01 03 01 03 03 02 01  |................|
000000c0  09 08 08 08 01 01 03 01  01 01 01 05 01 01 09 01  |................|
000000d0  01 01 01 03 01 01 03 01  01 01 01 01 01 01 03 03  |................|
000000e0  03 03 03 03 03 03 03 03  03 03 03 03 03 03 03 03  |................|
000000f0  03 03 03 03 03 03 03 03  03 03 03 03 03 03 03 03  |................|
00000100  03 03 03 03 03 03 03 03  03 03 03 03 03 03 03 03  |................|
00000110  03 03 03 03 03 03 03 03  03 03 03 03 03 03 25 00  |..............%.|
00000120  00 00 02 01 00 00 02 00  00 00 02 02 00 00 02 03  |................|
00000130  00 00 02 01 00 00 02 01  00 00 02 05 00 00 02 04  |................|
00000140  00 00 02 01 00 00 02 01  00 00 02 04 00 00 02 08  |................|
00000150  00 00 25 00 00 00 25 00  00 00 02 00 00 00 25 00  |..%...%.......%.|
00000160  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000170  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000180  00 00 25 00 00 00 25 00  00 00 25 00 00 00 02 00  |..%...%...%.....|
00000190  00 00 02 02 00 00 02 03  00 00 08 06 00 00 08 06  |................|
000001a0  00 00 08 06 00 00 25 00  00 00 25 00 00 00 25 00  |......%...%...%.|
000001b0  00 00 08 06 00 00 25 00  00 00 25 00 00 00 25 00  |......%...%...%.|
000001c0  00 00 02 00 00 00 02 02  00 00 02 03 00 00 25 00  |..............%.|
000001d0  00 00 08 07 00 00 25 00  00 00 25 00 00 00 02 01  |......%...%.....|
000001e0  00 00 08 07 00 00 08 07  00 00 25 00 00 00 25 00  |..........%...%.|
000001f0  00 00 25 00 00 00 02 00  00 00 25 00 00 00 02 03  |..%.......%.....|
00000200  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000210  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
00000220  00 00 25 00 00 00 25 00  00 00 02 00 00 00 25 00  |..%...%.......%.|
00000230  00 00 02 03 00 00 25 00  00 00 25 00 00 00 25 00  |......%...%...%.|
00000240  00 00 02 04 00 00 25 00  00 00 25 00 00 00 25 00  |......%...%...%.|
00000250  00 00 25 00 00 00 25 00  00 00 2d 00 00 00 2d 00  |..%...%...-...-.|
00000260  00 00 02 02 00 00 2d 00  00 00 2d 00 00 00 2d 00  |......-...-...-.|
00000270  00 00 2d 00 00 00 2d 00  00 00 2d 00 00 00 2d 00  |..-...-...-...-.|
00000280  00 00 2d 00 00 00 2d 00  00 00 25 00 00 00 2d 00  |..-...-...%...-.|
00000290  00 00 2d 00 00 00 2d 00  00 00 02 03 00 00 2d 00  |..-...-.......-.|
000002a0  00 00 2d 00 00 00 2d 00  00 00 2d 00 00 00 2d 00  |..-...-...-...-.|
000002b0  00 00 2d 00 00 00 2d 00  00 00 2d 00 00 00 25 00  |..-...-...-...%.|
000002c0  00 00 25 00 00 00 02 00  00 00 25 00 00 00 25 00  |..%.......%...%.|
000002d0  00 00 25 00 00 00 25 00  00 00 25 00 00 00 25 00  |..%...%...%...%.|
000002e0  00 00 25 00 00 00 25 00  00 00 25 00 00 00 02 08  |..%...%...%.....|
000002f0  00 00                                             |..|
```


## Links
- prc-tools remix https://github.com/jichu4n/prc-tools-remix
- par utility for creating and manipulating .prc and .pdb files http://djw.org/product/palm/par/index.html
- romeo https://romeo.sourceforge.net/
- CloudpilotEmu https://cloudpilot-emu.github.io/app-preview/#/tab/about
