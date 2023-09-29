# dipi
Distro Independent Linux Package Installer

# How it works
It simply fetches a given package from Tiny Core Linux repositiory
with all the dependencies, mounts downloaded SQUASHFS images and
installs package and dependencies to **/usr/local**

# Usage
Once you've downloaded **dipi** and copied it to **/usr/bin**<br>
you can simply do: **~$ dipi nano** where 'nano' is a package name.<br>
You can use **wget -O- http://tinycorelinux.net/14.x/x86_64/tcz | grep your-package**<br>
to search for a package.

# Caution
There's no way to automatically remove packages installed with **dipi**,
so keep that in mind.

# YouTube tutorial
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/V_vYksQExgo/0.jpg)](https://www.youtube.com/watch?v=V_vYksQExgo&list=PLLfIBXQeu3aZuc_0xTE2dY3juntHF5xJY&index=11)


