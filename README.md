# dvorak-qwerty
Dvorak Qwerty for Linux XKB configuration files
created on Ubuntu 14.04, 104 US keyboard.


the keyboard changes to QWERTY when you hold down Control, Alt or Super key.

these files include:

Dvorak Qwerty
Dvorak Qwerty simplified (no dead keys)
Dvorak-Qwerty, international with dead keys
Dvorak-Qwerty alternative international no dead keys
Dvorak-Qwerty, classic
Dvorak-Qwerty, programmer




geometry (the picture of keyboard layout chart) is little bit strange because these layout using the first level to redirect, but these are no problem.

this configuration files overrides some keycodes in symbols/inet evdev section, line125-194.
comment out lines uses as QWERTY.

if your keyboard uses those keys e.g. when press Fn+F1-F12, change symbols/us line 859-909 and 1104-1117 to other keycode that you dont need in evdev section.

to enable these layout, just replace same named files under /usr/share/X11/xkb, and reboot.
make sure backup before changing system files.
