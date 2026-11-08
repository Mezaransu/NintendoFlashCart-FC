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
* REG $C000-$C003\
  xxxP PPPP\
  P : PRG BANK at $C000-DFFF
* REG $B003\
  WxPN MMDD\
  W : PRG RAM enable\
  P : CHR A10 mode\
  N : Nametable mode\
  M : Mirror\
  D : PPU BANK mode
* REG $D000-D003\
  CCCC CCCC\
  C : CHR BANK at $0000-$0FFF
* REG $E000-E003\
  CCCC CCCC\
  C : CHR BANK at $1000-$1FFF
* REG $F000\
  DDDD DDDD\
  D : IRQ latch
* REG $F001 or $F002\
  xxxx xxDD\
  D : IRQ control
* REG $F000 or $F001\
  AAAA AAAA\
  A : IRQ acknowledge\
