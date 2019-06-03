# 2019vectorizedCurvature
DEM curvature extraction methods, with vectorized computation

## Background information
This code is additional material for an article:
```
Pattern recognition of earthquake-induced paleo liquefaction 
spreads and Pulju moraines from an airborne laser scanning derived digital 
elevation model
```
sent to:
```
Computers and Geosciences
```
at Jun 2019. 

## Prerequisites
python 3.x and gnu octave 5.x 

## Testing the code
The folder z/ holds a DEM file (2 m grid size, UTM-TM35FIN, 6km x 6km) 
which is converted to two curvature files in c/16/ folder:
```
cd code; python main.py ../z/S5232G.asc 16
```
You can repeat the command with target grid sizes 8 4 and 2.
Compare the c/16orig/*.k1 and c/16/*.k1. These should be verbatim the same,
if everything went right. 


## Authors

* **Paavo Nevalainen** - *theory and implementation* 
* **Maarit Middleton** - *a sample map page of the topographic height DEM*
