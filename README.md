 don't let your linux comouter sleep
=====================================


 Function:
-----------
Ansible role to disable or configure suspend and sleep on linux machines via systemd and xset.

The default settings should disable all kind of suspendion and sleeping by masing these systemd services and disable the screen saver feature via xset off.

This should work on probably all machines.

It is only tested on machines running systemd and xorg. Like ``Debian 9`` and ``Archlinux`` together with ``i3wm`` as window manager.

 Configuration:
-----------------
Have a look into the ``defaults`` Folder for all options!

 Something wrong?
---------------
Please feel free to expand this role or open an issue if something is not working properly!

**Maintainance:** poor
*Pull-Requests will be reviews, but don't expect any improvements of this old ansible role. Use at your own risk!*
