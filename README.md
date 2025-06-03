This is a fork from [faceteam/facescrub](https://github.com/faceteam/facescrub)
with an update to now be using python version 3

To get the [FaceScrub dataset](http://vintage.winklerbros.net/facescrub.html):


#### 1) Clone this repo
```bash
git clone https://github.com/nothingHereReally/facescrub_py3.git
facescrub_py3
```
#### 2) Create a python virtual envronment and activate it

MS Windows OS
```cmd
python -m venv .venv
.venv\Scripts\activate.bat
```
GNU/Linux and MacOS
```bash
python -m venv .venv
source .venv/bin/activate
```
#### 3) Install the modules needed
```bash
pip install -r requirement.txt
```
#### 4) Finally to download the [FaceScrub dataset](http://vintage.winklerbros.net/facescrub.html)
```bash
python download.py
```


facescrub
=========

Download dataset from http://vintage.winklerbros.net/facescrub.html

simply run `python download.py`, all images are downloaded under `download`.

### Notice

Since I want to vertify the image and extract face region from the images, opencv-python package needed. If you are on Windows, this [url](http://www.lfd.uci.edu/~gohlke/pythonlibs/) can be very helpful to install packages.
