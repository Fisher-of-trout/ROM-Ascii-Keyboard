# ROM-Ascii-Keyboard
Old school eeprom based ascii keyboard
basically a decoder and multiplexer to scan and read the keyboard matrix. The same timing is used to scan the rom address with the correct ascii code
when the matix is closed it fires a one shot to load output register with the 7 bit code

 couple of small errors , did not design stabilizer holes for the shift keys.  and the til311 displays are grounded the decimal point pins. cut the #4&10 pins on displays , on the pcbway zip this is not corrected.  there is led top left for the shift and caps lock, debounce chip for the shift keys. the trick was to have a scan of the the matrix with 74138 and multilplex the closure to rom with same timing as the scan. 
I used this online editor for the layout and a kicad footprints placer to do the layout. 
https://www.keyboard-layout-editor.com/
also used the kicad keyboard footprint placer , important that the keyboard switches are in correct numerical order for the automation to work.
