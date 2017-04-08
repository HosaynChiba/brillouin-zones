# brillouin-zones
in python 3.5

![preview for simple lattice](https://github.com/sajadabasi/brillouin-zones/raw/master/video/brillouin-cs.mp4)
![preview for hexagonal lattice](https://github.com/sajadabasi/brillouin-zones/raw/master/video/brillouin-hex.mp4)

### installtion guid
for installing fist need python 3.5 which is pre installed in ubutnu.

needed libraries:
- matplotlib
- numpy
- tkinter

could be installed with pip :

installing pip:
```bash
	# for ubuntu
	sudo apt-get install python3-pip
	# centOS
	sudo yum install python34-setuptools
	sudo easy_install pip
```
installing libraries with pip:
```bash
	sudo pip3 install matplotlib
	sudo pip3 install numpy
	# or
	python3.5 -m pip install matplotlib
```

and then running the code 
```bash
	python3.5 ./brillouin-zones.py
```
and enjoy the code




# breif description of the code:
- usage:
	the usage of code is so easy just edit the followin line of code:
```python
	BrillouinZone(a1, a2, size);
```
which a1 and a2 are basic vectors of lattice and size is the size of lattice
	example:
```python
BrillouinZone([1, 0], [0, 1], 5);
```

- how code works:
	- first all distanecs of all points to centeal point will calculated and will sotred in array and sorted.
	- calculates the nodes with the specisfic distance from top array
	- plot the Perpendicular of that node and centeral node. by calculating the tilt of the line 	


# TODO 
- colorize the zones
- 
