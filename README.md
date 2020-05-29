# TP-Troll-rings-4-cores-LUA
conky TP-Troll-rings-4-cores-LUA

![Screenshot](https://i.imgur.com/izQQxHS.png)

The theme was modified to adapt it to modern conky configuration requirements.

I took it from ArcoLinux, however I guess it has been downloaded and modified from here: https://www.deviantart.com/trollpunny/art/Conky-Rings-Revamped-591137228

Here you have the list of all conkyrs which comes from the ArcoLInux: https://gitlab.com/rzn/arcolinux-conky-collection/-/tree/master/etc/skel/.config/conky

Dependencies:
* conky
* git to clone the resource
* The theme requires conky-lua. Install it first. 
* Also, download and install Santana font. https://www.dafont.com/santana.font

Instruction:
* open terminal
* type: cd .conky
* type: git clone https://github.com/sysadmin-info/TP-Troll-rings-4-cores-LUA.git
* type: cp conky-delay.sh ~/
* type: cd ..
* type: chmod +x conky-delay.sh
* run conky delay script by typing ./conky.delay.sh
* add conky-delay.sh script to autostart to let it start after the login.

In case of errors:
double_buffer = true, set to false and check.
change
own_window_type = 'normal',
to
own_window_type = 'override',
or
own_window_type = 'desktop',
