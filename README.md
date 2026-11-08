# Board Thickness For 1.2MM
## Mapper007
* Board : AxROM
* PRG ROM : 512K
* CHR RAM : 8K
* REG $8000-$FFFF\
  xxxM PPPP\
  M : Mirror\
  P : PRG BANK at $8000-$FFFF
## Mapper066
* Board : GxROM
* PRG ROM : 512K
* CHR ROM : 128K
* REG $8000-$FFFF\
  PPPP CCCC\
  P : PRG BANK at $8000-$FFFF\
  C : CHR BANK at $0000-$1FFF
## Mapper024 & Mapper026
* Board : VRC6a & VRC6b
* PRG ROM : 256K
* CHR ROM : 256K
* REG $8000-$8003\
  xxxx PPPP\
  P : PRG BANK at $8000-BFFF
* REG $C000-$C003
  xxxP PPPP\
  P : PRG BANK at $C000-DFFF
