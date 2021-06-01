# CEH Toolbelt

These are some tools I made from taking from [The Cyber Mentor's](https://github.com/TCM-Course-Resources) course on certified ethical hacking.

### General Links

Link to Website: https://www.thecybermentor.com/

Links to course:
* https://www.udemy.com/course/practical-ethical-hacking/ (udemy)
* https://academy.tcm-sec.com/p/practical-ethical-hacking-the-complete-course (tcm academy)

Link to discord server: https://discord.gg/EM6tqPZ

FAQ: https://github.com/hmaverickadams/Practical-Ethical-Hacking-FAQ

## What This Includes
* `port_scanner.py`: A script to scan a host's ports to see which are open.
* `ip_sweep.sh`: A script to see which hosts, by IP address, are connected to a network.
* `turn-key_socket.py`: A script to create a web socket.

# Getting Started

## Requirements
* Python3
* a CLI (if you're on Windows, this is the Command Prompt; for Linux and Mac, this is your terminal)

## Quick Start
You can go to [repl.it](https://github.com/crc8109/Practical-Ethical-Hacker.git) where I'm hosting the app in a personal repl. When you click the link, just hit the button up top that says `Run` with the forward arrow and the scripts will start up, to show you how they work.

## Starting from Scratch
Clone the repo (in your terminal, type `git clone https://github.com/crc8109/Certified-Ethical-Hacker.git`) and then open the CLI for the directory you just created. Here's the instructions for running the first two scripts, the ones that are used for reconnaissance:

*`python3 port_scanner.py > Open_ports.txt`; then enter a starting port # and an ending port # (e.g. `1 65000`) so the scan can start
*`./ip_sweep.sh <the first 3 octets of your network>` (e.g `192.168.0`); feel free to also redirect the output to a file too (e.g. `./ip_sweep.sh 192.168.0 > connected_hosts.txt`)

If this doesn't work, feel free to reach out.
