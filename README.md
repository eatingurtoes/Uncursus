<center>
  <h1 align="center">Uncursus</h1>
  <h3 align="center">a installation script that allows Procursus as its bootstrap</h3>
  <br/>
  <h4 align="center">Note: It's not recommended by the Procursus maintainers to run this script, support will not be provided so please do not go contacting Diatrus.</h4>
</center>

### Installation:
***Disclaimer: I am not held responsible for any damage done to your device.***<br/>
***Note: you must have a computer to launch the script via SSH, you cannot use NewTerm.***<br/>
***Note: I recommend that you know what you're doing***<br/>
***Note: After The installtion You Will have Procursus Cydia By Default Free to you to Keep Cydia or install zebra,sileo,installer or other package manager PS : For sileo use odyssey repo, PS: You can uninstall cydia after installed another package manager***<br/>
***Note: That will not give you libhooker please dont install it or that will break your unc0ver install if you really want it use odyssey***<br/>
***Note: If you install sileo from odyssey repo make sur to not update preference loader to 3.0.1 and to have 2.2.5 else tweak settings will not show***<br/>
1) You don't need to restore rootfs anymore, Tweaks/Apps are saved<br/>
2) Refresh sources in Cydia and install `OpenSSH` and `Curl`<br/>
3) Find the IP of your iDevice and connect to it via SSH on your computer. Don't know what SSH is or how to use it? Refer to: https://www.hostinger.com/tutorials/ssh-tutorial-how-does-ssh-work<br/>
4) Use the following command in your SSH session for installation:<br/>
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/eatingurtoes/Uncursus/new/installuncursus.sh)"`<br/>
5) Once your device resprings, launch Cydia and you're good to go.<br/>

***For all users that don't have a PC, I made a Non-Computer version.***<br/>
1) You don't need to restore rootfs anymore, Tweaks/Apps are saved
2) Add https://repo.yaya48.gq in cydia
3) Install `Uncursus Installer` come with MTerminal as a dependency, newterm isn't supported.
4) Open MTerminal and login as root with your password. Type `su`, then `alpine` (or your root password)
5) Type `uncursus-installer`, then run it and wait
6) When finished, your device will respring.
7) Open Cydia, update your packages and enjoy

### Questions & Support:
- Discord: Yaya4#1989
- Twitter: [@Yaya4_4](https://twitter.com/Yaya4_4)

***Note: Support is not for installation help, but for bug reports or asking questions. All installation steps are here***<br/>

### Credits:
[Procursus Team](https://github.com/ProcursusTeam/) - for the bootstrap<br/>
[CoolStar](https://github.com/coolstar/) - Previously for the deploy script (that not used anymore)<br/>
knuckles approver#1119 (on Discord) - for the testing and name of the project<br/>
