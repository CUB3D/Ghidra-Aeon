### Ghidra AEON1 plugin

This is a processor plugin for Ghidra that adds support for the AEON architecture, currently only `aeon:aeon1` is supported

There are three isa versions of AEON:
- aeon1
- aeon2
- aeonR2

aeon1 is little-endian 32-bit fixed width OpenRisc 1000 fork with some additional instructions (e.g. `b.subb` and a `b.` instruction prefix instead of `l.` (except for branches)

In aeon1 values are typically returned in `r3`, unless the param is 64 bit in which case register pair `r12:r11` is used (reversed from OpenRisc)

aeon2/aeonR2 are a 8-24 bit variable width encoding with even more instructions

Keywords:
AEON R2 ghidra 
