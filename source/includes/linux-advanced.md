# Linux Administration

The easiest of all Linux distribution is Ubuntu.
I have been using Linux along side from 2009,
and from 2016 Linux is my main stream operating system.
I have used Debian, Ubuntu, Fedora, OpenSUSE, and a few others.
Thanks to my under-graduate projects and {TCE's FStival 2008]().
But, now Linux Mint Cinnamon is my favourite (from 2017).
I begin to dislike Unity-Gnome in Ubuntu, so moved to Mint.
Am I ranting or self-trumpeting? Both. Okay, it is 2020. But still some
commands are still in my muscle memory. I am just logging it here.

## Admin commands

- `echo $HOME` - Displays the home of user who run it
- `ls -a` - Also list the hidden folders/files (it beging with a `.`) e.g `.bashrc` in $HOME

- `df -h`   - List all mounted partition along with used/available/% size
- `top`		  - List all running process based on % of CPU usage. press `q` to close
- `du -h .` - List the file/folder size of current directory

- `lscpu` - List the processor details
- `lsusb` - List of devices attached to the USB port
- `cat /proc/meminfo `    - List the RAM/memory details

- `dmesg | grep tty`      - Find the `tty/devName` just attached via USB
- `less /var/log/auth.log`- All login/out/suspend session are recored
- `/var/log/*`            - has all the logs file e.g. apt-get log is in ``/var/log/apt/history.log`

- `ps -ef | grep firefox`- List processes/id with the name `firefox`
- `kill <pid>`    - Kill the process with <pid> sending sigterminate
- `kill -9 <pid>` - Kill the process with <pid> sending sigkill

- `/home/<user>/.bashrc`  - User specific bashrc file
- `source .bashrc`- Run and set bachrc file in current session
- `/home/<user>/.bash_history` - List of cmd typed by the `user`


- `echo $PATH` - Displays the environment variable `PATH`
- `PATH=$PATH:/usr/local/cuda-10.0/bin` - Set path in shell
- `export PATH` - will pass this env variable for subsequent commands [eric](https://github.com/edemaine/coauthor/issues/421#issuecomment-515698521)

- `ssh  username@ip-address` # e.g `ssh rajesh@10.6.3.112`
- `scp localfile user@ip-address:/some/location/on/server`


## Installation

- Most of new machine. You may have to disable fastboot/safeboot in BIOS
- Download you favourite linux as `iso` file
- Burn iso to formatted USB/DVD using
[rufus](https://rufus.ie/ "USB Rufus"),
[UNetbootin](https://unetbootin.github.io/ "UNetbootin") ,
[usb-creator](https://askubuntu.com/a/1153429/1021108 "USB Creator") or
[Startup Disk creator](https://www.howtogeek.com/414574/how-to-burn-an-iso-file-to-a-usb-drive-in-linux/ "Startup Disk Creator")
- Reboot and press the key F12/F10 (differ based on manufacturer) to bootfrom USB/DVD
- Mostly positive answer for moast. At select drive location, use MANUALLY
- Give appropriate drives  "/", /home, and swap (/boot, /tmp optinal)
- You may leave it with / alone also.
- Upon installation and reboot. Grub will appear.

