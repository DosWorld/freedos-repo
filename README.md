# FreeDOS-repo

-----

## <a name="contents"></a>Contents
[Introduction](#Introduction)  
[Installation instructions](#Installation)

[What's new?](#Whatsnew)

[My FreeDOS apps](My_apps.md)

[Program launchers, file managers and environments](Launchers.md)  
[Productivity applications](Productivity.md)  
[Graphics applications](Graphics.md)  
[Programming languages etc.](Development.md)  
[Really simple games](Games.md)  
[Educational Programs](Education.md)  
[Screensavers and other eye candy](Eyecandy.md)  
[Command-line utilities](Commandline.md)  
[Miscellaneous applications](Misc.md)  
[Terminate-and-stay-resident utilities](TSR.md)  
[Tutorials](Tutorials.md)  
[Example Code collections](Example.md)  
[Document collections](Documents.md)  

[FreeDOS tips](Tips.md)

-----

## <a name="Introduction"></a>Introduction

This is a repository of [FreeDOS](http://www.freedos.org/)-compatible freeware and OSS software. Not "abandonware", by which I mean that you will not find formerly commercial software here that have not been explicitly made open-source or at least freeware.

However, non-crippled shareware with a single nag screen at the beginning or end is fair game. Whether you are going to try to send money to a developer from thirty or forty years ago who could be dead by now is up to you.

Having said all that, there are a lot of little utilities from a kinder, gentler age, when people would just make their stuff available without worrying about licenses. These will be regarded as public domain until someone informs me otherwise.

Source code is included wherever possible.

This is not meant to be a conclusive collection of DOS applications. These are apps that I have tested on *FreeDOS 1.2* (on bare silicon and in the *DOSBox* emulator) and that I find useful, fun or interesting. If you need something more comprehensive, try [this site](http://reimagery.com/fsfd/) or [this one](https://www.opus.co.tt/dave/indexall.htm). I am not a gamer at all, so if that is what you are looking for, well, sorry, I only have a few of the simplest ones.

An example: FreeDOS comes with DosZip Commander. I use it all the time. And if you don't like that one, it also has DOS Navigator. There are dozens of Norton Commander clones out there: Directory Maven, Volkov Commander, you name it. But generally one is only going to end up in this repository if it offers a clear difference to and advantage over Doszip Commander.

Since I started this site, some apps have been incorporated into the FreeDOS installation itself. I'll weeed them out if I see that happening.


I also slip in a few little apps that [I wrote myself](My_apps.md). You will know them by a certain primitive look and feel :-)

-----

{: style="text-align:center"}
[Return to Table of Contents](#contents)

-----

## <a name="Installation"></a>To install these packages:

Download the package, transfer it to your FreeDOS system and extract the zip file to the **ROOT directory** (C:\\). 

    unzip packagename.zip -d c:\

You might be tempted to use the *DosZip Commander*, which is bundled with FreeDOS and can be called up with the command *dz*, or similar utilities. I advise against this. These packages were actually created under Linux and you may come across weird crc errors if you use *dz* or similar apps. The command line works fine.

*It is important to extract these packages to the root directory!* This is different from official FreeDOS packages, wich expect to be extracted to *C:\FDOS*. There is an actual reason for this. Some of these very old programs are not relocatable: They have hardcoded paths inside them and will crash or refuse to load if you try to run them from a strange directory. I have tried really hard to stick to the FreeDOS file system and not litter your root with directories, but sometimes I simply can't. Better then, to have a single installation procedure for all my packages.

Programs that do not run directly from *c:\FDOS\BIN* will have a convenient batch file placed in *C:\FDOS\LINKS*. If a program requires changes to *CONFIG.SYS* or *AUTOEXEC.BAT*, that will be documented here. 

Sorry, there is no uninstall facility. But most of these packages consist of a single directory in C:\FDOS\PROGS (or C:\FDOS\DEVEL), a batch file in C:\FDOS\LINKS and an information file in C:\FDOS\APPINFO, so it shouldn't be too hard.

-----

{: style="text-align:center"}
[Return to Table of Contents](#contents)

-----

## <a name="Whatsnew"></a>What's new?

8 May 2021 - Added Snarf to [TSR](TSR.md)  
8 May 2021 - Added Costa to [Program launchers](Launchers.md)  
14 April 2021 - Added Amb-utils to [My FreeDOS apps](My_apps.md)  
3 April 2021 - Added Compushow to [Graphics Applications](Graphics.md)  
3 April 2021: Added GeoClock to [Miscellaneous applications](Misc.md)  
3 April 2021: Added WordPerfect Graphics to [Documents](Documents.md)  
20 December 2020: Added AMB to [Miscellaneous applications](Misc.md)  
24 December 2020: Updated DWED in [Programming languages etc.](Development.md)  
22 November 2020: Added Alite to [TSR](TSR.md)  
22 November 2020: Added Shass to [Productivity Applications](Productivity.md)  

-----

{: style="text-align:center"}
[Return to Table of Contents](#contents)

-----
