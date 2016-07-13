# CMLinux
DIY an any scale, full customizable Linux-From-Scratch, to clear myself, it is really a ***Linux From Scratch***, but with my care and love.

***CMLinux v0.8-re-TC has just Released which may give you the Full Tool Chain to Customize Linux, see the releases to have a quick start.***

![flowchart](/resources/flowchart_0.7.2016070 .png)

Build a Linux from **zero** to **hero**, I will follow the lead of Linux-From-Sctrachs version 7.9 to build a tiny but strong Linux, and I shall call it as CMLinux.

> 
Our Goal is to make a Linux-From-Sctrach with basic tools and keeps it with high perfermance for ***VM*** usage.
> 
Our LFS need to satisfy the LSB Requirements by integrating these paskages:
> 
Bash, Bc, Binutils, Coreutils, Diffutils, File, Findutils, Gawk, Grep, GTK+2, Gzip, M4, Man-DB, Ncurses, Procps, Psmisc, Sed, Shadow, Tar, Util-linux, Zlib
>
So join us, and you will learn and build your Linux for your *VM*

# Project Progress
- 20160713
    - The project is hanging-up for my exam of ***RHCE*** in 20170711 at Beijing.
    - Package up all files for the Project.

# Steps
- Form all scripts for installing and integrating a tiny and strong Linux in ***localhost*** starting with the localhost Linux. Package them into a workable `toolchain`.

> The standards we shall follow as closely as possible:
>> 
POSIX.1-2008.
>> 
Filesystem Hierarchy Standard (FHS) Version 3.0
>> 
Linux Standard Base (LSB) Version 5.0

- Package the local tiny Linux into a Distribution and optimize it for ***VM*** usages.
- Integrate and test it with other popular open source tools like MariaDB/Apache to form an avaliable Linux for usage or teaching.


# Need Your Help
- Preparing for re-define the build_steps for more detailed and professional.
- You may fork it and create your Linux as your favor.
- Any problems and questions, **please create an issue**, and we may discuss it and solve it.

# Requirements for Partcipators
> 
No MORE requirements, and we will learn more from it.  -- from Linux with LOVE.

- First thing first, `git` and `GitHub`.
- AMD64 localhost, VT or VT-x better.
- VM Platform, KVM better. `Cent OS 7` and its previous versions are more friendly for building.
- ***DO NOT USE UBUNTU x86_64 12.02+ as the localhost, there exists a series of fatal errors in pending cross-compile***

![VM_for_build](/resources/VM_for_build.png)

> If your localhost is Windows you may first deploy a Linux in VM as the platform for developing, recommending `Ubuntu`, a really friendly Linux with `apt`.

- For developing, you should have some basic knowings about `OS`/`Linux`/`C`/`bash`, you may learn them from:

> 
**Computer Systems: A Programmer's Perspective** -  Randal E.Bryant
> 
**Linux System Programming** - Robert Love 

\* For writing documents, you shall have some knowings about `Markdown`.

# *Enjoy Yourself*

Cherry Mill - I am working hard to Re-factor the whole system to meet the need of the VM-BIOS.

![build_env_sample](resources/refactoring_0710.png)

---
README.md - 0.6.20160710
