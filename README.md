# Domitien bash scripts projects

**Not an experimented developper, not a professionnal**, I am here to share some bash scripts I have made for friends, family, or myself, to ease some procedures and installations that can be fully automated.

My scripts are not perfect, feel free to show me a better way to write them, make them lighter, faster... Everyone will benefit.

- Domitien Hosts (tested with Ubuntu)

Worried about privacy and consequences of p0rn spreading over the Internet, my first script uses various hosts files sources from [filterlists](https://filterlists.com/lists/pl-host-file) as well as from git.
**Quite and aggressive list with 4070923 entries (as of 24 sept. 22)**

This script works perfectly but the design might not be optimal.
What does it do ?

    1) Just for fun and design : downloads mpg123 and plays a chiptune music (copyright free)
    2) Downloads all the blocklists I use
    3) Merge, organize, creates a clean hosts file
    4) Copies the file to /etc/hosts
    5) One completed, shred and delete all unecessary files
    6) Allows to add a website to the list
    7) Allows to remove a website from the list
    8) Allow to restore the VERY PREVIOUS back-up state

Note that **this repository does not accept pull requests!** The code here is provided in hopes that others may find it useful, not to allow community contribution. Issue reports of all kinds (bug reports, feature requests, etc.) are VERY welcome.
