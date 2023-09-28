# dipi
Distro Independent Linux Package Installer

# How it works
It simply fetches a given package from Tiny Core Linux repositiory
with all the dependencies, mounts downloaded SQUASHFS images and
installs package and dependencies to **/usr/local**

# Usage
Once you've downloaded **dipi** and copied it to **/usr/bin**<br>
you can simply do: **~$ dipi nano** where 'nano' is a package name.
You can use **wget -O- http://tinycorelinux.net/14.x/x86_64/tcz | grep your-package**<br>
to search for a package.

# Caution
There's no way to automatically remove packages installed with **dipi**,
so keep that in mind.

# YouTube tutorial
[![IMAGE ALT TEXT HERE](https://raw.githubusercontent.com/maksimKorzh/msmd-linux/main/root/var/local/img/msmd-linux.png)](https://www.youtube.com/watch?v=EVTw4YqPdKA)

