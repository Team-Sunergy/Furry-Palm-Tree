# Progress Log for smart-route

### Fri. 1/19/2018
Made program slightly easier to debug:
- the variable `FILENAME` lets you specify the source of test data
- Created `ASC 2016(2).kml` with only 17 data entry's to simplify testing
- Program downloads 25,991 Blocks of PolyLine data each block is 67.6kB in size
	- need to find if there is a way to download less data for each PolyLine
	  Possibly change 5 in `polyline.encode(block, 5)` to a lower value
	- try to get away with generateing and downloading fewer polylines 
- Installed pandas via apt-get
- Installed polyline via pip3
- Left lots of commented out testing code in place
- Added Comments containing best guess about what some code does
---

### Sat. 1/20/2018
- added more comments to code, comments with space after # are original.
- updated README
---

### Sun. 1/21/2018
- Latest Version of Dan's Code uploaded
- made easier to change between short and long test file
---
### Sun. 3/11/2018
- Fixed extra empty windows appearing when running RouteSimulator
- All three windows now open at once

