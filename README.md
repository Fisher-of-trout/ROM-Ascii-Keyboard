# ROM-Ascii-Keyboard
Old school eeprom based ascii keyboard
basically a decoder and multiplexer to scan and read the keyboard matrix. The same timing is used to scan the rom address with the correct ascii code
when the matix is closed it fires a one shot to load output register with the 7 bit code
