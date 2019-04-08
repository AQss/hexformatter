# hexformatter

Formats and displays information from raw telemetry files.  
Uses files with proprietary *.spc* extension, strongly hardcoded.

##Bit names
1.Time [h]
2.Time [m]
3.Time [s]
4.Time [ms]
5.Lenght, Type, ID type
  - Bit nr 0 -> ID type
  - Bit nr 1 -> Frame type
  - Bit nr 2,3 -> Empty
  - Bit from 4 to 7 - Frame length
6.ID
  - Bit from 0 to 4 -> Empty
  - Bit from 5 -> 7 -> 1st part of ID
7.2nd part of ID
8. Rest of bits its data
