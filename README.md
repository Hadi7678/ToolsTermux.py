# ToolsTermux.py
Web ToolsTermux.py

#!/bin/bash

#version 1.0

# Variables

b=’\033[1m’

u=’\033[4m’

bl=’\E[30m’

r=’\E[31m’

g=’\E[32m’

bu=’\E[34m’

m=’\E[35m’

c=’\E[36m’

w=’\E[37m’

endc=’\E[0m’

enda=’\033[0m’

blue=’\e[1;34m’

cyan=’\e[1;36m’

red=’\e[1;31m’
figlet Tools | lolcat
echo -e “Tools :Mr_hadi88 $white

” |lolcat
echo -e “By :Mr_hadi88 $white ” |lolcat
echo -e “Blog :https://mrhadichtalk.wordpress.com
$white ” |lolcat

###################################################

# CTRL + C

###################################################

trap ctrl_c INT

ctrl_c() {

clear

echo -e $red”[#]> (Ctrl + C ) Detected, Trying

To Exit … “

echo -e $cyan”[#]> Thanks”

sleep 1

echo “”

echo -e $white”[#]> see you :)…”

sleep 1

exit

}

lagi=1

while [ $lagi -lt 6 ];

do

echo “”

echo -e $b “1. Nmap${enda}”;

echo -e “============================” | lolcat

echo -e $r “2. Admin-finder${endc}”;

echo -e “============================” | lolcat

echo -e $g “3. RED_HAWK${endc}”;

echo -e “============================” | lolcat

echo -e $c “4 Lazymux${endc}”;

echo -e “============================” | lolcat

echo -e $r”5. Tools-X${endc}”;

echo -e “============================” | lolcat

echo -e $r “6. Exit${endc}”;

echo “”

echo -e “╭>MC” |lolcat

read -p “╰─#” pil;

# Nmap

case $pil in

