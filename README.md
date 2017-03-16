# Fast_Scripts

These scripts works with Kali Linux!

These are created to make a sort of shortcuts: <br />
You can excecute these 'fast scripts' with the following command: <br />
"sudo bash [directory to script]" <br />
If you want to excecute the script by administrator A.K.A. root, <br />
then you need the "sudo" command (displayed above) <br />
If you're smart: create a folder on your desktop named: fastscripts <br />
Then you can create new scripts or copy them from this repository to your <br />
fastscripts folder. <br />
now open a terminal window and type the following commands: (without the $) <br />
`$ cd Desktop` <br />
`$ cd fastscripts` <br />
`$ ls` <br />
(now you can see al the files in the current directory with the "ls" command) <br />
Now choose a script you want to excecute: for example: testscript <br />
`$ sudo bash testscript` <br />
now your script will be excecuted. <br />
my sugestion is to use sudo because then you know you're good <br />
Btw. when you get an error: please first try to excecute the command without sudo, for example: <br />
`$ bash testscript` <br />


### Install

We will create a lot of fast scripts so you can clone them AND use them.<br />
To do this folow these steps:<br />
1. Open a new teriminal window and type the following command:<br />
`$ git clone https://github.com/Circulair/Fast_Scripts.git`<br />
Now linux will copy this git to your pc, you can find in the direcory immidiatly when you open "files"<br />
2. I recommend to replace this file and place it on your desktop.<br />
3. Now you can run these scripts by follow the steps shown above. <br />


### Types of adapters

There are many types of adapters, my adapters called `wlan0` and `eth0`.<br />
On every pc is there a difference adapter name possible, to identify the name of your adapter:<br />
1. Open a new terminal window and type the following command: `$ ifconfig`.<br />
(if you get an error: please be sure you have an internet connection and update your <br />
system by enter this command: `$ apt-get update`. <br />
Wait until you see your line that means you can put a new command in, now close the terminal.)<br />
2. Now you can see a few adapters like "wlan0" and "eth0". (your adapters are your hardware, for example:<br />
eth0 is your Ethernet port and wlan0 is your wifi hardware (wireless internet connection))<br />
The name's of the adapters are displayed and now you can change the default commands to **_your_** adapter names.<br />


### Python

Python is an other programming language, and it have more capability's.<br />
to run the python scripts, folow these steps:<br />
1. Go to your directory where the python file is located with the `$ cd` command. 
(if you don't know anymore, on the top of this README.md file is the guide)<br />
2. Now you type in: `$ python testscript.py`.<br />
= The command python means: run python. testscript.py means: the python script you want to run. 
(you need to care that your file is ending on `.py`.<br />
3. Now your script is running!<br />

My recommendation is: when you have a long file name or just want to type a bit faster: type the first characters of <br />
the filename and just enter "Tab". The filename appears on your screen. **BUT** when your first charcters are matching <br />
with other filenames it won't show up: you need to specifie the name a bit more. <br />
