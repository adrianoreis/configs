configs
=======


**eclipse.ini** 
* vmargs
http://www.oracle.com/technetwork/java/javase/tech/vmoptions-jsp-140102.html


**Eclipse application launcher Ubuntu Unity (Ubuntu 13.10)**


1. Create eclipse.desktop under ~/.local/share/applications

2. eclipse.desktop contents

```
[Desktop Entry]
Type=Application
Name=Eclipse
Comment=Eclipse Integrated Development Environment
Icon=eclipse
Exec=sh -c 'GTK2_RC_FILES=$GTK2_RC_FILES:~/gtkrc-eclipse eclipse'
Terminal=false
Categories=Development;IDE;Java;
```


3. open nautilus
me@laptop:~$ nautilus .local/share/applications/

4. Drag eclipse.desktop and drop it on to the "application laucher" (panel on the left)
