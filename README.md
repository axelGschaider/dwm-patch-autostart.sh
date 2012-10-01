dwm-patch-autostart.sh
======================

This patch will make dwm run "~/.dwm/autostart\_blocking.sh" and "~/.dwm/autostart.sh &" before entering the handler loop. One or both of these files can be ommited.

Be aware that dwm will not startup as long as autostart\_blocking.sh is running and will stay completely unresponive. For obvious reasons it is generally a bad idea to start X-applications here :)

