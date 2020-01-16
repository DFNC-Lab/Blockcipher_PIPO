# Blockcipher_PIPO
## PIPO_reference_bitslice.c
Bitslice version implementation code of block cipher PIPO.

## PIPO_reference_TLU.c
Table lookup version implementation code of block cipher PIPO.

## searching_trail.exe
Differential and Linear trail searching program for PIPO.
### Options
#### -o [RotationOffset]  : Each Rotation Offset
#### -c [D/L]             : Choose DC('D'), LC('L')
#### -r [Round]           : Target round
### Example
.\searching_trail.exe -o 04176235 -c D -r 8

