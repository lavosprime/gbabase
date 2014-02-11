gbabase
=======

A basic Eclipse C project configured for devkitARM and libgba. Fork to start a new Game Boy Advance project more quickly than setting it up yourself.


Prerequisites
=============

I followed [this tutorial](http://forum.gbadev.org/viewtopic.php?t=5271) originally, but some of it is out of date, and more of it I've done for you, so here is a summary of the steps you actually need to follow:

1. Install Eclipse and the [Eclipse C Development Tools.](http://eclipse.org/cdt/) You can install them separately or just use the CDT distribution of Eclipse.

2. Install the devkitPro toolchain. There's an [automatic installer](http://sourceforge.net/projects/devkitpro/files/Automated%20Installer/), or you can fiddle around with it manually. If you use the installer, it will also install MSYS (on Windows) and add devkitPro to your PATH for you.

3. Download [Visual Boy Advance 1.7 SDL](http://sourceforge.net/projects/vba/files/VisualBoyAdvance/1.7/) and configure Eclipse to use it for running and debugging as described in the tutorial. This step isn't necessarily required, but you'll want to test your code somehow...


Further setup
=============

Unfortunately, I haven't figured out a way to point Eclipse to libgba dynamically, even though the makefile is supposed to do that automatically. The solution is to [manually tell Eclipse where your libgba installation is.](https://stackoverflow.com/questions/11599121/add-external-source-files-from-a-library-to-the-project-in-eclipse-cdt)

Please [contact me](mailto:lavosprime@gmail.com) if I've missed a step or you need further help.
