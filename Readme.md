# Cloning

git clone --recursive git://github.com/mneuhaus/FLOW3-Distro-AdminBase.git


# FLOW3 1.1

Welcome to FLOW3!

There are a few things you need to know to get started with FLOW3.
All necessary steps are explained in the FLOW3 Getting Started tutorial
which you find on http://flow3.typo3.org/documentation/quickstart.html

In short here's what you need to do:

1 git clone --recursive git://github.com/mneuhaus/FLOW3-Distro-AdminBase.git

2 Set up a virtual host for your web server and let it point to the Web/ directory of FLOW3.
3 Adjust the file permissions. On Linux / Mac just run 
  sudo ./flow3 flow3:core:setfilepermissions johndoe wwwuser wwwgroup
  from FLOW3's main directory (replace the user names by some matching
  your system environment!).
4 Call the URL leading to your virtual host from a browser

Have fun!
