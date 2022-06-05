# IPTool
This is a tool for beginners to get their local ip easier.\
Note: This only works on linux

# Guide
Make sure that you have git installed, if you don't, you can do so by running:\
if on ubuntu, Pop!_OS, elementaryOS or derivatives: `sudo apt install git -y`\
if on arch, manjaro or derivatives: `sudo pacman -Sy git --noconfirm`\
Download the script by running:\
`git clone https://github.com/kisgamer/iptool.git`\
Next go into the directory you just downloaded(iptool).\
`cd iptool`\
Make the file(s) executable for convenience, by running:\
`sudo chmod +x ./*`\
If you have ethernet, then type: `./cable.sh`\
If you have wifi, then type: `./wifi.sh`.\
If you're not sure, then type: `./notsure.sh`
That's it!\
It should say `inet [YOUR_IP] brd [RANDOM_NUMBERS] blah blah`\
Of course [YOUR_IP] will be well, your ip.