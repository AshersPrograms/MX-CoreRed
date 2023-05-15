# MX-CoreRed
This is a set of widgets plug-ins made for Conky for 2,4, or 8 CPU's.

There are 9 red Themes included.

There are 3 main types with each theme coming in 2CPU's 4CPU's and 8CPU's

# Special Features
This widget has several special features including: 
- A To Do List
- Weather for your ip address
- Debian Hints
- Displays up to 8 CPU Percentages

<img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc2coreRed.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc2coreRed_Plus.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc2coreRed_ToDo.png?raw=true" width="250" height="725">

<img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc4coreRed.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc4coreRed_Plus.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc4coreRed_ToDo.png?raw=true" width="250" height="725">

<img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc8coreRed.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc8coreRed_Plus.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc8coreRed_ToDo.png?raw=true" width="250" height="725">

# Installation Instructions:
-Download and unzip the folder

-Rename the directory to MX-CoreRed

-Copy or Move the directory to ~/.conky/

Open a terminal and type:
```BASH
chmod 0755 ~/.conky/MX-CoreRed/weather.sh
```

# MX Linux Users Install Proceedures
-Open MX Package Installer

-Click the tab Enabled Repos

-In the Search type: "fortunes"

-Click the box fortunes and fortune-debian-hint

-Next In the Search type: "curl"

-Click the box curl

-Next In the Search type: "jq"

-Click the box jq

-Remember to click "Also Install "Recommended" Packages"

-Click install

# Debian, Ubuntu, Mint Users Install Proceedures
You are going to install 4 programs fortunes, fortunes-debian-hints, curl, and jq **

-Open a terminal and type:
```BASH
sudo apt install fortunes fortunes-debian-hints curl jq
```

**You also need perl install but most distro this comes standard but just as a side note if there are any issues.

*curl, command line tool for transferring data with USL syntax

*jq, lightweight and flexible command-line JSON processor

## Additional Shortcuts
-Create a Desktop Shortcut to ~/.conky/MX-CoreRed/todo.txt
-or type:
```bash
ln -s ~/.conky/MX-CoreRed/todo.txt ~/Desktop/
```

## Pre-specify your zip code
-This is not necessary but, if you want the program to run a little faster and more accurate. Pre-specify your zip code. If you use this option then you do not have to install curl or jq.

-Open a terminal and type:
```bash
sed -i '18s/.*/YOURZIPCODE=12345/' ~/.conky/MX-CoreRed/weather.sh
```
**replace 12345 with your zip code

# Security
For complete security check with your system administration before installing this program. This program looks up your Ip address and retrieves information from several web sites here is a list of web sites this program contacts:
- https://api.ipify.org
- https://ipapi.co
- http://rss.accuweather.com

*You can find the BASH script here and how these website are being used to retrieve your IpAddress, your ZipCode, then the Weather. https://github.com/AshersPrograms/MX-CoreRed/blob/main/weather.sh
