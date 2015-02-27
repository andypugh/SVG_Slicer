# SVG_Slicer
Python Code to display a single slice of SVG file as a LinuxCNC HAL component

to start the slicer:
./test.py test.svg  

To actually display a layer (needs LinuxCNC HAL):
halcmd -kf
setp slice-viewer.Z 10
setp slice-viewer.scale 4


