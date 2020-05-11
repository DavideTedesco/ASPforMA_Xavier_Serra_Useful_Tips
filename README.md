# Audio Signal Processing for Music Applications by Xavier Serra

[link to the course on coursera.org](https://www.coursera.org/learn/audio-signal-processing/home/welcome)

##### Your Python version
To see which Python version you have on your system type `python` on your terminal, and it will appear the version of it.

##### Python extensions needed:

Paste this code on linux to install all the necessary Python stuff
```
sudo apt-get install ipython python-dev python-matplotlib python-numpy python-scipy python-pygame cython
```
##### The sms-stools used by Serra:
to download them via terminal paste this in your terminal window
```
git clone https://github.com/MTG/sms-tools.git
```
you can also download them via this link:[files of the course to download](https://github.com/MTG/sms-tools)

##### The tools needed:
[Sonic Visualizer](https://www.sonicvisualiser.org/)

[Audacity](https://www.audacityteam.org/)

*You can install this tools via terminal on Linux:*

- *Sonic Visualizer*
```
wget -c https://code.soundsoftware.ac.uk/attachments/download/2606/sonic-visualiser_4.0.1_amd64.deb
```
```
dpkg -i sonic-visualiser_4.0.1_amd64.deb
```
<ins>Note that this version of the code is for the installer of the version *4.0.1* for *64-bit Ubuntu* so you should change the link and paste the right one and most current one version for your system</ins>

You can check the actual version and copy the links via [this page](https://sonicvisualiser.org/download.html)

- *Audacity*
```
sudo apt-get update
sudo apt-get install audacity
```

##### Sonic Visualizer's plugins used by Serra (Aubio):
[Download Link](https://aubio.org/vamp-aubio-plugins/)
You can build the plugins also directly on your machine 
```
git clone https://github.com/aubio/vamp-aubio-plugins.git
```
on Mac
```
bash build_osx.sh
```
on Linux
```
bash build_linux.sh
```
move the files _.dll, .dylib, or .so_ in the folders specified [here](https://www.vamp-plugins.org/download.html#install) for your system
