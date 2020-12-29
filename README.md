# 4kDPI scales Qt and GTK applications.

#### I wrote this little script because I'm just too lazy to keep copying new BASH scripts, setting them up and making them ready to run, and then checking that everything is OK!
#### It also makes it possible to create a BASH that is ready to run and store it in /user/bin/XYZ, for example.
## Installation instructions
Simply copy the script into e.g. /usr/bin/4kDPI and make it executable with:

    sudo chmod +x /usr/bin/4kDPI
#### It was tested on Arch Linux as well as on Manjaro under the desktop environment Cinnamon.
![Theme](https://raw.githubusercontent.com/MTrage/4kDPI/main/Preview.jpg)
### Direct use of 4kDPI

    4kPDI q 0 2 /usr/bin/XYZ
___
### Creating a shell startup script with 4kDPI

    4kDPI q 0 2 /usr/bin/XYZ /usr/bin/XYZ-4k
___
## Function explanation of 4kDPI
<b>4kDPI</b> [GUI] [DPI] [SCALE] [Program] [Shell Script]<br>
<b>––––– [GUI]</b> <b>q</b> for Qt or <b>g</b> for GTK applications<br>
<b>––––– [DPI]</b> <b>0</b> for normal DPI or <b>1</b> for rescale Window DPI<br>
<b>––––– [SCALE]</b> Scaling factor <b>0.5</b>, <b>1</b>, <b>2</b> or <b>4</b><br>
<b>––––– [Program]	</b>	 Program which should be started (absolute path)<br>
<b><i>Optional</i></b><br>
<b>––––– [Shell Script]</b> Script which should be created (absolute path)<br>

---
## What else needs to be considered
#### Occasionally, some applications may give the impression that scales that are not to be enlarged appear reduced or, for example, require the scaling value 1 for an enlargement. This may be due to the fact that the creator of the application already uses scaling defaults or that these have been defined in the desktop environment. 
---

#### I hope it is as useful for you as it is for me,
#### have fun with it.
