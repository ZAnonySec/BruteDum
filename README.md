# BruteDum
 BruteDum - Brute Force attacks SSH, FTP, Telnet, PostgreSQL, RDP, VNC with Hydra, Medusa and Ncrack
About BruteDum 1.0

BruteDum is a SSH, FTP, Telnet, PostgreSQL, RDP, VNC brute forcing tool with Hydra, Medusa and Ncrack. BruteDum can work with any Linux distros if they support Python 3.
Features of BruteDum

    SSH, FTP, Telnet, PostgreSQL, RDP, VNC with Hydra (recommended)
    SSH, FTP, Telnet, PostgreSQL, RDP, VNC with Medusa
    SSH, FTP, Telnet, PostgreSQL, RDP, VNC with Ncrack
    Scan victim's ports with Nmap

Install and run on Linux

You have to install Python 3 first:

    Install Python 3 on Arch Linux and its distros: sudo pacman -S python3
    Install Python 3 on Debian and its distros: sudo apt install python3

You have to install Hydra, Medusa, Nmap and Ncrack too:

    On Arch Linux and its distros: sudo pacman -S nmap hydra medusa ncrack

    On Debian and its distros: sudo apt install nmap hydra medusa ncrack

    git clone https://github.com/GitHackTools/BruteDum
    cd BruteDum
    python3 brutedum.py

