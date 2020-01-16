# Blockcipher_PIPO
## PIPO_reference_bitslice.c
Bitslice version implementation code of block cipher PIPO.

## PIPO_reference_TLU.c
Table lookup version implementation code of block cipher PIPO.

###test vector
####PIPO-64/128
Secret key: 0x6DC416DD_779428D2_7E1D20AD_2E152297
Plaintext: 0x098552F6_1E270026
Ciphertext: 0x5D10A7FA_33F90169
####PIPO-64/256
Secret key:0x34386A09_43116E68_25C471FF_72E5709C_6DC416DD_779428D2_7E1D20AD_2E152297
Plaintext: 0x098552F6_1E270026
Ciphertext:0x37CE460C_7F111C1A

## searching_trail.exe
Differential and Linear trail searching program for PIPO.
### Options
#### -o [RotationOffset]  : Each Rotation Offset
#### -c [D/L]             : Choose DC('D'), LC('L')
#### -r [Round]           : Target round
### Example
.\searching_trail.exe -o 04176235 -c D -r 8

