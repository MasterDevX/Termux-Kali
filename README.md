# KaliTermux
### Info
Install Kali Linux on Android using Termux!

The script was originally developed by <a href="https://github.com/EXALAB">EXALAB</a> for <a href="https://github.com/EXALAB/AnLinux-App">AnLinux</a> project.</br>
This version of script is slightly modified.</br>
Differences from original:
- Mounting internal storage (/sdcard) to root (/) is enabled by default
- Improved output
- Some improvements in code
### How to use
Simply copy and paste this code to Termux command line to install Kali Linux:<br/>
```pkg install wget proot -y && wget https://raw.githubusercontent.com/MasterDevX/KaliTermux/master/InstallKali.sh && bash InstallKali.sh```

After installing run ```./start-kali.sh``` to launch Kali.
