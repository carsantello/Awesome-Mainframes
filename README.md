# Awesome-Mainframes
Awesome list of mainframe related resources &amp; projects and is currently in a very early stage.

## Getting Started

## General

## Emulators
* [Hercules Spinhawk](https://github.com/rbowler/spinhawk) - Hercules 3.x - spinhawk is the repository for the production-quality version (release 3.xx) of the Hercules mainframe virtualization platform
* [Hercules Hyperion](https://github.com/hercules-390/hyperion)  The Hyperion version of Hercules is the official development version of the Hercules emulator and contains the latest bleeding edge changes made by Hercules developers to address various bugs that may exist in the production version.
* [SDL Hercules Hyperion](http://www.softdevlabs.com/hyperion.html) - [(github repo)](https://github.com/SDL-Hercules-390/hyperion) SoftDevLabs (SDL) version of Hercules 4.x 
  * [Installing SDL Hyperion](https://geronimo370.nl/s370/hercules-installing/installing-sdl-hyperion/) - Gerrard Wassink's tutorial for compiling and installing SDL Hercules Hyperion on various architectures.
  * [Build your latest version of Hercules from source - M82](https://www.youtube.com/watch?v=ZJI5v3-zEww&feature=youtu.be) (YOUTUBE) - Video from Moshix demonstrating building the latest version of Hercules from source code.

## Hercules GUI Front Ends
* [Jason](http://ollydbg.de/Jason/index.htm)- *"Jason 1.00 is an integrated graphical frontend to the Hercules S/370, ESA/390 and z/Architecture Emulator. What, you haven't heard of Hercules before? It's a masterpiece that emulates IBM mainframes, from old good IBM System/360 and up to the modern z Series."*
* [HercGUI](http://softdevlabs.com/hercgui.html) - *"HercGUI The Hercules graphical user interface for Windows is a standard Windows program that makes using the Hercules emulator much easier and more enjoyable. It automatically maintains your Hercules configuration and log files by means of standard Windows dialogs and provides realistic real-time feedback of your virtual mainframe's activity."*  From Software Development Laboratories.
* [HercStudio](http://hercstudio.sourceforge.net) - Hercules Studio is a GUI front-end to the Hercules mainframe Emulator on Mac and Linux.  Written by Jacob Dekel.
* [MVS Ops](https://mvs.gadsby.me.uk) - A web application that simplifies management of MVS running on Hercules.

## TN3270 Terminal Emulators
* [Vista TN3270](https://www.tombrennansoftware.com/index.html) - Tom Brennan's feature packed TN3270 emulator for Microsoft Windows and runs on Linux and Mac with WINE. *"Vista tn3270 is a Windows program designed to emulate IBM 3270 terminals connected to a host via IP link. Currently it is available for a free 30 day trial, and costs only $30.  If you are looking for an emulator created with mainframe programmers in mind, then give this one a try.  You might find some unique features unavailable even on the highest priced commercial emulators."*
* [x3270](http://x3270.bgp.nu) - x3270 is an IBM 3270 terminal emulator for the X Window System and Windows. It runs on most Unix-like operating systems -- e.g., Linux, Mac OS X, Solaris and Cygwin. It also runs natively on Windows. 
* [tn3270 for Macintosh](https://www.brown.edu/cis/tn3270/) - Free TN3270 emulator for macOS X versions prior to 10.15 (Catalina) as it requires 32-bit application support.
* [PW3270](https://softwarepublico.gov.br/social/pw3270) ([github](https://github.com/PerryWerneck/pw3270)) - Opensource (GPL2) TN3270 emulator
* [ZOC: SSH Client and Terminal Emulator for Windows and macOS](https://www.emtec.com/zoc/) - ZOC is a commercial, cross-platform terminal emulator with TN3270 emulation support.
### TN3270/3270 Tech Info
* [3270 Data Stream Programming](https://www.tommysprinkle.com/mvs/P3270/start.htm) - Tommy Sprinkle's refrence on 3270 Data Streams.  
## Operating Systems
### MVS
* [Tur(n)key MVS 3.8j TK4-](http://wotho.ethz.ch/tk4-/) - The easiest way to get started with MVS.  TK4- is a pre-built distribution of MVS with many enhancements, bundled with programming languages and additional tools.
* [Tur(n)key MVS 3.8j TK3](http://www.bsp-gmbh.com/turnkey/)- Volker Bandke's Tur(n)key MVS 3.8 TK3 distribution. 
#### MVS Information
* [MIB Mainframe Useful Commands - Basic V1.10](https://www.yumpu.com/it/document/read/7780434/mib-mainframe-useful-commands-basic-v110) - Cheatsheet of useful zOS / MVS commands from ibmmainframe.cn 
* [TSO Tutorial](http://www.jaymoseley.com/hercules/tso_tutor/tsotutor.htm) - Jay Moseley's TSO Tutorial, based on MVS 3.8.
* [The MVS Tur(n)key New Users Cookbook](http://www.bsp-gmbh.com/turnkey/cookbook/index.html) - A great resource for new users by Volker Bandke, creator of TK3.
* [MVS FAQ](http://www.jaymoseley.com/hercules/faq/mvsfaq.htm) - MVS related Frequently Asked Questions answered by Jay Mosley.
### VM/370
* [VM/370 Downloads - Multiple Versions](http://www.smrcc.org.uk/members/g4ugm/VM370.htm) - This site includes Robert O'Hara's Six Pack Version 1.2, Paul Gorinskey's 5-Pack System, Andy Norrie's 4-Pack system, and Bob Abele's Original 3-Pack System.
* [Six Pack, Version 1.3 Beta](http://www.smrcc.org.uk/members/g4ugm/SixPack-1.3.Beta.htm)
* [Six Pack Extended (6PExt)](https://geronimo370.nl/vm6pext/vm-370/)-René Farland's unofficial update to the original Six Pack Version 1.2 Distribution. 6PExt includes the recent RSCS nucleus of Peter Coghlan for NJE support.
### MUSIC/SP
MUSIC/SP (Multi-User System for Interactive Computing/System Product; originally "McGill University System for Interactive Computing") was developed at McGill University in the 1970s from an early IBM time-sharing system called RAX (Remote Access Computing System). The system ran on IBM S/360, S/370, and 4300-series mainframe hardware, and offered novel features (for the time) such as file access control and data compression. It was designed to allow academics and students to create and run their programs interactively on terminals, in an era when most mainframe computing was still being done from punched cards. Over the years, development continued and the system evolved to embrace email, the Internet and eventually the World Wide Web. At its peak in the late 1980s, there were over 250 universities, colleges and high school districts that used the system in North and South America, Europe and Asia.
* [MUSIC/SP](http://www.canpub.com/teammpg/de/mcgweb/msi/musicsp.htm)- MUSIC/SP is short for Multi-User System for Interactive Computing / System Product. It is an operating system, similar in some ways to Unix. It is a true multi-tasking, multi-user system. 
### Michigan Terminal System
The Michigan Terminal System (MTS) is one of the first time-sharing computer operating systems.[1] Developed in 1967 at the University of Michigan for use on IBM S/360-67, S/370 and compatible mainframe computers, it was developed and used by a consortium of eight universities in the United States, Canada, and the United Kingdom over a period of 33 years (1967 to 1999)
* [Michigan Terminal System Archive](http://archive.michigan-terminal-system.org)

### Linux
* [Linux/390 at Princeton University](http://linuxvm.org/penguinvm/)
* [Gentoo Linux/390 on Hercules](https://wiki.gentoo.org/wiki/S390/Hercules) - This guide is about installing Gentoo in a emulated S390 machine using Hercules.
* [Installing Ubuntu 18.04 Server for S390 on Hercules](https://astr0baby.wordpress.com/2018/06/03/installing-ubuntu-18-04-server-s390x-in-hercules-mainframe-simulator/)
### DOS/360
### OS/360
### MVT
### MFT
### DOS/VS



## CICS
* [KICKS for TSO](http://kicksfortso.com) - A free replacement for CICS which runs in the TSO or CMS environments
* [Mainframe CICS World](https://sites.google.com/site/mainframecicsworld/) - Lots of information about CICS

## Programming Languages
## Assembler
* [IBM Mainframe Assembler - Hints and Tips](http://www.les-smith.com/software/assembler/assembler-hints-and-tips.htm)
### BASIC
### C
### CLIST
### COBOL
### JCL
### REXX
* [BREXX/370](https://github.com/mgrossmann/brexx370) - MVS only fork of Vasilis Vlachoudis' awesome rexx implementation.  This seems to be the only version of REXX available that will run on MVS 3.8.

## Mainframe Related YouTube Channels
The list below are YouTube Channels that feature mainframe related videos.
* [Moshix Mainframe Channel](https://www.youtube.com/user/moshe5760) - Moshix is a mainframe veteran with a large following of nearly 4,000 subscribers.  He frequently posts new videos covering everything mainframe-related.
* [Mainframes & More with Matthew](https://www.youtube.com/channel/UCFvM_17zCxRhXHIhOyg-N3Q) - Videos on IBM mainframes and mini-computers.  He has a series of videos detailing how to sysgen (install) MVS 3.8 from scratch.

## Mainframe Blogs
* [Geronimo/370](https://geronimo370.nl) - Gerrard Wassink's Blog
* [An idiot at a mainframe](https://idiotmainframe.blogspot.com) - Johan's Blog.  Lots of information on using KICKS.
* [Astr0baby's not so random thoughts](https://astr0baby.wordpress.com) - Astr0baby's blog -- large variety of posts including many mainframe related.
* [mainframe.dev](https://blog.mainframe.dev) Christian Svensson's blog
## Courses
* [The Complete Mainframe Professional Course : TSO/ISPF](https://www.udemy.com/course/the-complete-mainframe-professional-course-tso-ispf/) (UDEMY) by Abhishek Rathi. *"The first step in learning about Mainframes. 4 Courses in 1. Covers TSO, ISPF, JCL, VSAM, COBOL and CICS."*
* [Mainframe : The Complete TSO/ISPF from Beginner to Expert](https://www.udemy.com/course/master-tso-ispf-on-mainframe-from-scratch-to-advanced-level/) (UDEMY) by Sandeep Kumar. *"Best TSO/ISPF Course. TSO and ISPF commands are explained in detail. Simplified COBOL covered as bonus along with JCL."*
* [Mainframe: The Complete JCL Course from Beginner to Expert](https://www.udemy.com/course/the-complete-jcl-course-from-beginner-to-expert-on-mainframe/) (UDEMY) by Sandeep Kumar. *"Become an expert on JCL. Jcls are used for COBOL Programs. Procedures, Utilities, GDG and basics of TSO/ISPF are covered"*
* [IBM z/OS Mainframe Practitioner Professional Certificate](https://www.coursera.org/professional-certificates/ibm-z-mainframe#courses) (COURSEA) This is actually a collection of 3 courses by Jeff Bisti: [Introduction to Enterprise Computing](https://www.coursera.org/learn/introduction-enterprise-computing), [Getting Started on Mainframe with z/OS Commands and Panels](https://www.coursera.org/learn/z-commands-and-panels), and [Basic System Programming on IBM Z](https://www.coursera.org/learn/system-programming).
* [OpenMainframe Project's COBOL Programming](https://github.com/openmainframeproject/cobol-programming-course) - Opensource COBOL Programming course created during the COVID-19 pandemic.

## Free or Opensource Software to run on your Mainframe
* [CBT Tape](http://www.cbttape.org)- The CBT tape is a collection of freeware almost all open-source distribution for the IBM mainframe MVS and OS/390 operating system environment.
* [Pycroft Six](http://www.prycroft6.com.au/software.html) Pycroft Six's free MVS User Mods and Software, including REVIEW, a full-screen TSO browser and editor.

