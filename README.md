# Ping Pong Game

<img src="/images/cover.png" width="1000" height="300" />


In this small project I used kivy one of the python package use to build multi platform (windows, linux, ios, android ...) application. It still a lot to improve in this game but it is a good start point anabling bigenner to experiment the process of game building end-to-end.
## Contents

1. Project Structure
2. Prosess
3. How to run
4. Generate apk file for android
5. Deployment (Real world Use)
6. To improve
7. About Me

## 1. Project Structure


#### images
* ├── contains images

##### app.py
##### helpers.kv

## 2. Process

* step1 : Install python and virtualenv
* step2 : set virtual environment
* step3 : install and import packages

## 3. How to run

### 3.1. CLONE PROJECT DIRECTORY

+ $ git clonehttps://github.com/Rekidiang2/kv_ping_pong.git
+ $ cd kv_ping_pong

### 3.2. CREATE & ACTIVATE VIRTUAL ENVIRONMENT

#### 3.2.1. WITH PIP and VENV

##### (Windows) 
+ $ python -m venv kv01_venv 
+ $ kv01_venv\Scripts\activate (<= Activate virtual Environment)
+ $ deactivate (<= Deactivate virtual Environment)
+ $ pip install -r requirements.txt
+ $ python app.py

##### (MasOS || LINUX)
+ $ python3 -m venv kv01_venv 
+ $ source kv01_venv/bin/activate (<= Activate virtual Environment)  
+ $ deactivate (<= Deactivate virtual Environment)
+ $ pip install -r requirements.txt
+ $ python app.py


#### 3.2.2. WITH CONDA

+ Verify if you have conda installed ($conda --version) if not go to [anconda](https://www.anaconda.com/products/individual) or [miniconda](https://docs.conda.io/en/latest/miniconda.html) to download and install it

+ $ conda create -n kv01_venv
+ $ conda activate kv01_venv (<= Activate virtual Environment)
+ $ conda deactivate  (<= Deactivate virtual Environment)
+ $ pip install -r requirements.txt
+ $ python app.py

## 4. Generate apk file for android
Note - If you are using Linux or Mac. Open up your terminal and directly jump to step number 4

1. Signup on Digital Ocean (https://m.do.co/c/c2cf5bc2a760 - Use this link to get 100$ free)
2. Create a Droplet
3. Open up terminal Access Console and login using you One-Time Password
4. Installing Python and Virtual Environment https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-ubuntu-16-04
5. Install buildozer - https://buildozer.readthedocs.io/en/latest/installation.html#targeting-android
6. Install Filezilla ( skip if Linux or Mac) - https://filezilla-project.org/download.php
7. Connect Filzilla to server ( skip if Linux or Mac)
8. Upload your kivy folder to enviroments folder ( in linux/mac just go to your kivy folder using terminal)
9. buildozer init (spec file will be add in the project folder)
10. buildozer -v android debug (the apk file can be find in the new created bin folder you can rename it as you want )
11. In case you get error in step 10 reinstall cpython ($ pip install cpython)
12. Using Filezilla download the apk in your bin directory
13. Copy this apk file to your phone
14. Run it. ( You need to enable install apk with unknown sources)

## 5. Deployment (Real world Use)

+ google play
+ ios app

## 6. To improve

+ add color
+ fix bugs

## 7. About Me
___

### I'm a data scientist, software Engineer. data and technology passionate person, Artificial Intelligence enthusiast 

> My Website [Click Here](https://rekidiangdata-s.github.io/kiesediangebeni/)

> Social Network

[![alt text][1.1]][1]
[![alt text][2.1]][2]
[![alt text][3.1]][3]
[![alt text][4.1]][4]

[1.1]: https://i.imgur.com/oFsAcMx.png (facebook icon with padding)
[2.1]: https://i.imgur.com/YCdR3o9.png (twitter icon with padding)
[3.1]: https://i.imgur.com/5BWvIrF.png (github icon with padding)
[4.1]: https://i.imgur.com/UA7Oh6z.png (medium icon with padding)

[1]: http://www.facebook.com/reagan.kiese.37
[2]: https://twitter.com/ReaganKiese
[3]: https://github.com/RekidiangData-S
[4]: https://medium.com/@rkddatas


My game make with kivy
