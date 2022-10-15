# Domitien bash scripts projects

**Not an experimented developer, not a professional**, I am here to share some bash scripts I have made for friends, family, or myself, to ease some procedures and installations that can be fully automated.

My scripts are not perfect, feel free to show me a better way to write them, make them lighter, faster... Everyone will benefit.

**You need to be superuser to run some of the scripts bellow and make them executable. Follow the procedure :**

    sudo -s
    [enter password]
    chmod +x SCRIPTNAME
    ./SCRIPTNAME    

**- Domitien Hosts (tested with Ubuntu)**

(15/10/2022) .deb installer released !

Worried about privacy and consequences of p0rn spreading over the Internet, my first script uses various hosts files sources from [filterlists](https://filterlists.com/lists/pl-host-file) as well as from git.
**Quite and aggressive list with 4062100 entries (as of 24 sept. 22)**

This script works perfectly but the design might not be optimal.
What does it do ?

    1) Just for fun and design : downloads mpg123 and plays a chiptune music (copyright free)
    2) Downloads all the blocklists I use
    3) Merge, organize, creates a clean hosts file
    4) Copies the file to /etc/hosts
    5) Once completed, shreds and deletes all unecessary files
    6) Allows to add a website to the list
    7) Allows to remove a website from the list
    8) Allow to restore the VERY PREVIOUS back-up state
    
**- DUPS (Domitien Ubuntu Post-Script)**

RELEASED !
Bash script for newbies willing to get everything they need installed for an office use, firewall rules included.

Note that **this repository does not accept pull requests!** The code here is provided in hopes that others may find it useful, not to allow community contribution. Issue reports of all kinds (bug reports, feature requests, etc.) are VERY welcome.
