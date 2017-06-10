![Version 0.1.7.1](https://img.shields.io/badge/Version-1.0-green.svg)
![Python 2.7.x](https://img.shields.io/badge/Python-2.7.x-yellow.svg)
[![GPLv3 License](https://img.shields.io/badge/License-GPLv3-red.svg)](https://github.com/D35m0nd142/LFISuite/blob/master/COPYING.GPL)
[![Twitter](https://img.shields.io/badge/Twitter-%40d35m0nd142-blue.svg)](https://www.twitter.com/d35m0nd142)

# LFI Suite

![alt tag](https://github.com/D35m0nd142/LFISuite/blob/master/screenshot.png)

<h3> What is LFI Suite? </h3>

LFI Suite is a totally <b>automatic</b> tool able to scan and exploit Local File Inclusion vulnerabilities using many different methods of attack, listed in the section `Features`.

* * * 

<h3> Features </h3>

* Works with Windows, Linux and OS X
* Provides 8 different Local File Inclusion attack modalities:
  - /proc/self/environ
  - php://filter
  - php://input
  - /proc/self/fd
  - access log
  - phpinfo
  - data://
  - expect://

* Provides a ninth modality, called <b>Auto-Hack</b>, which scans and exploits the target automatically by trying all the attacks one after the other without you having to do anything (except for providing, at the beginning, a list of paths to scan, which if you don't have you can find in this project directory in two versions, small and huge). 
* Tor proxy support
* Reverse Shell for Windows, Linux and OS X

<h3> How to use it? </h3>

Usage is extremely simple and LFI Suite has an easy-to-use user interface; just run it and let it lead you.
##### Reverse Shell
When you got a LFI shell by using one of the available attacks, you can easily obtain a reverse shell by entering the command <b>"reverseshell"</b> (obviously you must put your system listening for the reverse connection, for instance using <b>"nc -lvp port"</b>).

<h3> Dependencies </h3>

* Python <b>2.7</b>.x
* Python modules to install: termcolor, requests
* socks.py 

> I recommend you to install <b>pip</b> on your operating system because if you have it installed, when you run the software all the missing modules will be automatically solved and the file socks.py downloaded.

<h3> Collaboration </h3>

LFI Suite already contains a lot of features but, as you probably know, there are plenty of other possible attacks still to implement.
If you are a Python programmer/Penetration tester and you want to join this project in order to improve it and extend it, please contact me at <<b>d35m0nd142@gmail.com</b>> or directly here.

<h3> Disclaimer </h3>

I am not responsible for any kind of illegal acts you cause. This is meant to be used for ethical purposes by penetration testers. If you plan to copy, redistribute please give credits to the original author.

Video: Be patient..it will be available in a few days <br>
Follow me: <b>https://twitter.com/d35m0nd142</b>
