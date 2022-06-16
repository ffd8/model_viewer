# model_viewer
 
v0.1  
cc [teddavis.org](https://teddavis.org)

just a basic tool built with modelviewer.dev 
to refresh every X second to see changes as you glitch away!

more info to adjust below: https://modelviewer.dev/  
definitely works with GLB + glTF models (maybe more?!)

## usage:
- place this file in same folder as your model
- rename modelPath below with your file name
- adjust refreshRate as desired
- run folder with this page + model as a webserver:
	- `cd` + spacebar + drag/drop your folder into terminal (mac) / command prompt (win)
	- use one option below for quick server:
		- python 2: `python -m SimpleHTTPServer 8001`
		- python 3: `python -m http.server 8001`
		- php:      `php -S localhost:8001`
- haaaave fun!