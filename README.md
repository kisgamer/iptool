# IPTool
This is a tool for beginners to get their local ip easier.\
Note: This only works on linux

# Guide
Make sure that you have git installed, if you don't, you can do so by running:\
`sudo apt install git -y`\
Download the script by running:\
`git clone https://github.com/kisgamer/iptool.git`\
Next go into the directory you just downloaded(iptool).\
`cd iptool`\
Make the file(s) executable for convenience, by running:\
`chmod +x wlan0ip.sh`\
and\
`chmod +x eth0ip.sh`\
and\
`chmod +x notsure.sh`\
If you have ethernet, then type: `./eth0ip.sh`\
If you have wifi, then type: `./wlan0ip.sh`.\
If you're not sure, then type: `./notsure.sh`
That's it!\
It should say `inet [YOUR_IP] brd [RANDOM_NUMBERS] blah blah`\
Of course [YOUR_IP] will be well, your ip.

