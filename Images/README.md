# SOLO Images

## Source: [BitSavers](http://www.bitsavers.org).
[PDP11 Software Archive](http://www.bitsavers.org/bits/DEC/pdp11/Brinch_Hansen_SOLO/)

|Image            | Description   |
|-----------------|---------------|
|solo.dsk         |SOLO disk image|
|soloDiskImage.tap|SOLO tape image|

## Source: [Stuttgart University](http://computermuseum.informatik.uni-stuttgart.de).
**ftp.informatik.uni-stuttgart.de** (FTP server. It will require an external FTP client). Directory: /pub/cm/dec/pdp11/

|Image            | Description   |
|-----------------|---------------|
|solo.rk05        |SOLO disk image|

solo.rk05 and solo.dsk use different internal formats

## Source: soloDiskImage.tap

|Image                   |Description                                           |Software Tool[[1]](#1)|
|------------------------|------------------------------------------------------|-------------|
|soloDiskImage.tap.file.1|SOLO disk image extracted from soloDiskImage.tap image|TapExtract   | 

soloDiskImage.tap.file.1 and solo.dsk are identical 
            
## Source: solo.rk05

|Image        |Description                                |Software Tool[[1]](#1)|
|-------------|-------------------------------------------|-------------|
|solo.rk05.dsk|SOLO dsk image created from RK05 disk image|RK05toDsk    |

solo.rk05.dsk and solo.dsk use the same internal format

<a id="1">[1]</a>
SOLO Software Tools Repository: [GitHub](https://github.com/ngospina/SOLO-Tools)
