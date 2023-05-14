# MX-CoreRed_8ToDo
This is a set of widgets plug-ins made for Conky for 2,4, or 8 CPU's.
There are 9 red Theme include.
There are 3 main types with each theme coming in 2CPU's 4CPU's and 8CPU's

# Special Features
This widget has several special features including: 
- A To Do List
- Weather for your ip address
- Debian Hints
- Displays up to 8 CPU Percentages

# Installation Instructions:
-Download and unzip the folder to ~/.conky/
-Open a terminal and type:
--chmod 0755 ~/.conky/MX-CoreRed/weather.sh

## Additional Shortcuts
-Create a Desktop Shortcut to ~/.conky/MX-CoreRed/todo.txt

-or type:
```bash
ln -s ~/.conky/MX-CoreRed_8ToDo/todo.txt ~/Desktop/
```
<img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc2coreRed.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc2coreRed_Plus.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc2coreRed_ToDo.png?raw=true" width="250" height="725">

<img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc4coreRed.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc4coreRed_Plus.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc4coreRed_ToDo.png?raw=true" width="250" height="725">

<img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc8coreRed.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc8coreRed_Plus.png?raw=true" width="250" height="725"><img src="https://github.com/AshersPrograms/MX-CoreRed/blob/main/conkyrc8coreRed_ToDo.png?raw=true" width="250" height="725">


## Pre-specify your zip code
-This is not necessary but if you want the program to run a little faster and more accurate. Pre-specify your zip code.

-Open a terminal and type:
```bash
sed -i '18s/.*/YOURZIPCODE=12345/' ~/.conky/MX-CoreRed/weather.sh
```
**replace 12345 with your zip code
