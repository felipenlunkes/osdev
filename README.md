<p align="center">
<img src="https://github.com/felipenlunkes/osdev/blob/main/img/banner.png">
</p>

<div align="center">

![](https://img.shields.io/github/license/felipenlunkes/osdev.svg)
![](https://img.shields.io/github/stars/felipenlunkes/osdev.svg)
![](https://img.shields.io/github/issues/felipenlunkes/osdev.svg)
![](https://img.shields.io/github/issues-closed/felipenlunkes/osdev.svg)
![](https://img.shields.io/github/issues-pr/felipenlunkes/osdev.svg)
![](https://img.shields.io/github/issues-pr-closed/felipenlunkes/osdev.svg)
[![](https://img.shields.io/twitter/follow/felipeldev.svg?style=social&label=Follow%20%40felipeldev)](https://twitter.com/felipeldev)

</div>

<hr>

# Operating system projects and reference material

<div align="justify">

This repository aims to count and list the open source operating system projects in activity, in addition to cataloging bibliographic references and useful material for the development and administration of operating systems.

</div>

<hr>

## Summary

<div align="justify">

This document is divided into a few sections to make it easier to search for a specific topic. You will find reference material on operating systems already consolidated, such as UNIX, Linux and Windows in a dedicated section, which will bring documents, papers, books and a short history of each one of them. In another section, you'll find material geared toward operating system development, reference material for systems administration, and more information about software licenses that you can use in your projects. In the third section we have the classification of operating systems in families. In this case, both established commercial products and systems projects (hobbies) are available. In the fourth section, the same projects are classified according to the languages ​​used for their development. More information about each is also displayed, such as the target architecture, whether it is an active project, whether it is available on GitHub, and more information about the license used. There will always be links to the project's main repository (or another repository that can be used). In the fifth section, you'll find tutorials for operating system development, sorted by target architecture. These tutorials may be available on video, on YouTube, or in text, present or not in GitHub repositories. In the next section, you will find other sites with more information and useful curiosities. Finally, in the last section, you can learn more about testing older operating systems that don't run on current hardware using the SSH utility (Linux, Windows, and macOS).

> A quick summary of the sections in this document:

* [Reference material on Operating Systems](#reference-material---operating-systems)
* [OSDev, system administration, applications and software licenses](#osdev-system-administration-applications-and-software-licenses)
* [Operating Systems sorted by family](#os-projects-sorted-by-family)
* [Operating Systems sorted by language](#os-projects-sorted-by-language)
* [Tutorials](#tutorials)
* [Websites and other resources](#websites-and-other-resources)
* [Test historical OSes via SSH](#test-historical-oses-via-ssh)

</div>

<hr>

## Reference material on Operating Systems

<div align="justify">

This section will address several operating systems that have revolutionized computing over the decades, changing the way we relate to our computers. These mainline systems were responsible for influencing the development of modern alternatives, and many of them (in their various incarnations) are still a part of our lives. In each topic, you will find references to the source code (if available), manuals, papers, books and other pages with more information, as well as forums that discuss aspects of each operating system. You will also be able to obtain information on how to run these systems, natively or in emulators/simulators. To get started, click on one of the options listed below!

This session addresses:

- [x] A quick resume on each operating system;
- [x] History of operating systems;
- [x] Historical material;
- [x] Internal technical documentation (kernel, interfaces, etc);
- [x] Source code of historical operating systems;
- [x] User manuals;
- [x] Manuals for the development of each operating system;
- [x] Guides for administration of each operating system;
- [x] Documentation on operating systems development;
- [x] Hardware documentation.

> Click on each highlighted operating system to access material for that operating system.

</div>

<div align="justify">

<details title="UNIX" align='left'>
<br>
<summary align='left'>UNIX</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Simh-pdp11-unix-sysiii.png" width="400" height="200">
</p>

Have you ever heard of UNIX? UNIX was a revolutionary operating system, initially developed in 1969 by Ken Thompson, Dennis Ritchie and other employees of Bell Laboratories, owned by the American company AT&T. Initially developed as a hobby on an old unused PDP-7 computer, UNIX created countless foundations that define a modern operating system, influencing virtually all operating systems developed since then. UNIX instituted features such as support for multiple users and processes running at the same time (multitasking), implemented in a lightweight way (requiring few machine resources), and was initially written in Assembly language for PDP-7 and later rewritten for C language (developed by the same authors and used until today). Initially, the source code was distributed to Universities, including the University of California at Berkeley. At that University, UNIX was extensively studied and extended. Graduate students and researchers added advanced features to UNIX, such as virtual memory support, more modern file systems, and network support, leading to BSD (Berkeley Software Distribution) releases. The BSD were nothing more than the UNIX released by AT&T with improvements, then called BSD UNIX. With that, UNIX became very popular. UNIX was licensed to several companies, originating derived systems, such as Xenix, ULTRIX, Venix, Solaris and so on. The BSDs served as the basis for others, such as SunOS. Whereas the BSDs were distributed with a free license, AT&T's UNIX had a paid license. BSD then became the main free implementation of UNIX, giving rise to projects based on version 4.4 of BSD, now just called 4.4 BSD, FreeBSD, NetBSD and OpenBSD. FreeBSD is heavily used on servers these days, as well as forming the basis of macOS and iOS. Other companies' systems, such as Microsoft's MS-DOS and Windows, were heavily influenced by UNIX. UNIX was also an inspiration for the development of non-derived free systems, the so-called Unix-like, such as Minix and Linux itself.

#### Original source code

* [The Unix Tree - The UNIX Heritage Society](https://minnie.tuhs.org/cgi-bin/utree.pl)
* [Research UNIX Version 1 - Version 7 source code (documentation)](https://github.com/dspinellis/unix-history-repo)
* [Research UNIX v10 source code (documentation)](https://github.com/Alhadis/Research-Unix-v10)
* [UNIX System V source code (documentation)](https://archive.org/details/ATTUNIXSystemVRelease4Version2)
* [Version 7 UNIX ported do x86 by Robert Nordier (BSD license)](https://www.nordier.com/v7x86/v7x86-0.8a-all.tar.xz)
* [Old Unix XRef](https://wfjm.github.io/home/ouxr/)

#### Specifications, documentation, manuals and historical material

* [UNIX History - Figure](https://upload.wikimedia.org/wikipedia/commons/7/77/Unix_history-simple.svg)
* [History of UNIX](http://ibgwww.colorado.edu/~lessem/psyc5112/usail/concepts/hx-of-unix/unixhx.html)
* [History and Timeline - UNIX.org](https://unix.org/what_is_unix/history_timeline.html#:~:text=The%20history%20of%20UNIX%20starts,what%20was%20to%20become%20UNIX.&text=It%20had%20a%20assembler%20for,text%20processing%20of%20patent%20documents.)
* [Read The Single UNIX® Specification](https://unix.org/online.html)
* [A Brief History of Everything UNIX](https://illumos.org/docs/about/history/)
* [UNIX releases](https://www.tuhs.org/Archive/Distributions/Research/)
* [About the Unix Boot Process](https://www.oreilly.com/library/view/essential-system-administration/0596003439/ch04s01.html)
* [UNIX Documentation at Stanford](https://uit.stanford.edu/service/sharedcomputing/unix)
* [X Window System at Stanford](https://web.stanford.edu/group/farmshare/cgi-bin/wiki/index.php/X_Window_System)
* [A Brief History of Unix and How did Linux came into being](https://medium.com/@safiuddinkhan/a-brief-history-of-unix-dcd41d0816c1)
* [Multics - The ancestor of UNIX](https://www.multicians.org/)
* [UNIX® on the Game Boy Advance](https://web.archive.org/web/20060831141959/http://www.kernelthread.com/publications/gbaunix/)
* [X.Org](https://www.x.org/wiki/)

#### Books and papers

* [The Evolution of the Unix Time-sharing System - Dennis M. Ritchie (Bell Labs), 1984](https://www.bell-labs.com/usr/dmr/www/hist.html)
* [The Evolution of the UNIX Time-sharing System - PDF (same as above)](https://curtsinger.cs.grinnell.edu/teaching/2019S/CSC213/files/unix_evolution.pdf)
* [Spinellis, D. A repository of Unix history and evolution. Empir Software Eng 22, 1372–1404 (2017)](https://link.springer.com/article/10.1007/s10664-016-9445-5)
* [A COMMENTARY ON THE SIXTH EDITION UNIX OPERATING SYSTEM](http://warsus.github.io/lions-/)
* [UNIX Seventh Edition Manual, Volume 2](https://wolfram.schneider.org/bsd/7thEdManVol2/)
* [The UNIX HATERS Handbook - PDF](https://web.mit.edu/~simsong/www/ugh.pdf)

#### Websites

* [The UNIX Heritage Society](https://www.tuhs.org/)

#### Wikipedia content

* [UNIX](https://en.wikipedia.org/wiki/Unix)
* [History of UNIX](https://en.wikipedia.org/wiki/History_of_Unix)
* [UNIX System V](https://en.wikipedia.org/wiki/UNIX_System_V)
* [UNIX/32V](https://en.wikipedia.org/wiki/UNIX/32V)
* [UNIX Wars](https://en.wikipedia.org/wiki/Unix_wars)
* [Xenix](https://en.wikipedia.org/wiki/Xenix)
* [PWB/UNIX](https://en.wikipedia.org/wiki/PWB/UNIX)
* [UnixWare](https://en.wikipedia.org/wiki/UnixWare)
* [Ancient UNIX](https://en.wikipedia.org/wiki/Ancient_UNIX)  

#### Run UNIX

* [Run ancient UNIX on modern hardware (Version 1 to Version 7 UNIX and BSD UNIX)](https://github.com/felipenlunkes/run-ancient-unix)

<hr>

</details>

<details title="BSD" align='left'>
<br>
<summary align='left'>BSD</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/e/e6/386BSD_installer_screenshot.png" width="400" height="200">
</p>

During its development in the 1960s, 1970s and 1980s, UNIX had its source code distributed to several research and teaching institutions. At the beginning of its life cycle, AT&T, the developer of the system, did not see UNIX as commercial software. Among the institutions that gained access to the system's source code, the University of California at Berkeley stood out. At the University, UNIX was used in teaching operating systems theory, as well as being the focus of research and development work, being the basis for several dissertations and postgraduate theses. Thousands of utilities were developed there that expanded on UNIX, including mail servers, text editors, and scientific and graphical modeling utilities. In addition, the researchers expanded the core of the system, inserting new functionalities and compatibility with new peripherals. When several companies and institutions became interested in the software developed at the University, the team began to group all the software produced, in the form of utilities or extensions to the core (kernel) of the system, creating and releasing the first BSD distribution (Berkeley Software Distribution), in March 1978. This release extended UNIX version 6 from AT&T. Over time, more and more software was developed, giving rise to BSD UNIX, a UNIX system adapted by the University and its researchers and students. Several milestones in UNIX development took place within the walls of the University of California, using AT&T's proprietary code as a base. Several commercial systems at the time derived from BSD UNIX software, such as SunOS, and DEC Ultrix. Within BSD UNIX came the TCP/IP implementation, essential for the internet and device-to-device communication as we have it today. All code developed at the University was released as free software under a permissive license, the BSD license. However, the original UNIX code was limited to the paid licensing imposed by AT&T. After a series of legal developments and changes in the point of view of AT&T, which started to market UNIX, all AT&T's proprietary code inside BSD UNIX had to be removed, creating an incomplete system. The missing components were rewritten again without proprietary code, including parts of the kernel, generating BSD Net/2, which loses the right to use the UNIX name. This system was used as a basis for the development of modern BSD systems, after the release of the last version from the University, 4.4BSD-Lite Release 2. After gaining compatibility with Intel processors, used in personal computers, this software, now called 386BSD, became the basis of modern systems such as FreeBSD and NetBSD (released in 1993). FreeBSD, for example, along with components from another project (the Mach kernel), is the basis for macOS, iOS, iPadOS and other Apple software, as well as being used on high-demand servers and personal computers, too. Today there are several descendant systems of 386BSD, which branched out from FreeBSD and NetBSD, such as OpenBSD, MidnightBSD, DragonFlyBSD, Darwin (base of macOS, iOS and others), among others. In addition, FreeBSD is the basis of the operating system for the Playstations 3, 4 and 5, Playstation Vita and borrows components for the operating system of the Nintendo Switch. If you have a Playstation, you have a BSD system in your house. In addition, BSD influenced several Windows components, which borrow the code responsible for the TCP/IP protocol, for example, in addition to several other operating systems. BSD UNIX, from 1978, is still alive today in its descendants, influencing even today how operating systems and utilities are written.

#### Specifications, books, papers, documentation, manuals and historical material

* [The Design and Implementation of the 4.4BSD Operating System](https://docs.freebsd.org/en/books/design-44bsd/)
* [Explaining BSD](https://docs.freebsd.org/en/articles/explaining-bsd/)
* [4.4BSD Documents](https://docs-legacy.freebsd.org/44doc/)
* [Berkeley Software Architecture Manual 4.4BSD Edition](https://docs-legacy.freebsd.org/44doc/psd/05.sysman/paper.html)
* [4.4 Berkeley Software Distribution Documentation](https://www.netbsd.org/docs/bsd/lite2/)
* [4.3 Berkeley Software Distribution Documentation](https://www.netbsd.org/docs/bsd/net2/)
* [Utah Lites Release 1.1.u3 - 4.4BSD Lite based server and library for Mach kernel](https://www.cs.utah.edu/flux/lites/html/)
* [BSD Now, a BSD podcast](https://www.bsdnow.tv/)
* [2.11BSD UNIX system studies](https://wfjm.github.io/home/211bsd/)

#### Wikipedia content

* [Berkeley Software Distribuition](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution)
* [386BSD](https://en.wikipedia.org/wiki/386BSD)
* [List of BSD operating systems](https://en.wikipedia.org/wiki/List_of_BSD_operating_systems)
* [Comparison of BSD operating systems](https://en.wikipedia.org/wiki/Comparison_of_BSD_operating_systems)

<hr>

</details>

<details title="Plan 9 from Bell Labs" align='left'>
<br>
<summary align='left'>Plan 9 from Bell Labs</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/e/e6/Plan_9_Fourth_Edition_rio_interaction_screenshot.png" width="400" height="200">
</p>

#### Original source code

* [Plan 9 from Bell Labs](https://9p.io/sources/plan9/sys/src/)
* [Plan 9 kernel history](https://github.com/0intro/9hist)

#### Specifications, books, papers, documentation, manuals and historical material

* [Plan 9 — The Documents (Volume 2)](https://9p.io/sys/doc/)
* [Plan 9 from Bell Labs - Paper](https://9p.io/sys/doc/9.html)
* [The Use of Name Spaces in Plan 9 - Paper](https://9p.io/sys/doc/names.html)
* [The Organization of Networks in Plan 9 - Proc. of the Winter 1993 USENIX Conf., pp. 271-280, San Diego, CA](https://9p.io/sys/doc/net/net.html)
* [Security in Plan 9 - Proc. of the 2002 Usenix Security Symposium, San Francisco](https://9p.io/sys/doc/auth.html)
* [How to Use the Plan 9 C Compiler - Paper](https://9p.io/sys/doc/comp.html)
* [ Changes to the Programming Environment in the Fourth Release of Plan 9 - Paper](https://9p.io/sys/doc/prog4.html)
* [APE — The ANSI/POSIX Environment - Paper](https://9p.io/sys/doc/ape.html)
* [Acid: A Debugger Built From A Language - Proc. of the Winter 1994 USENIX Conf., pp. 211-222, San Francisco, CA](https://9p.io/sys/doc/acidpaper.html)
* [Maintaining Files on Plan 9 with Mk - Paper](https://9p.io/sys/doc/mk.html)
* [Acid Manual - Paper](https://9p.io/sys/doc/acid.html)
* [Plan 9 Mkfiles - Paper](https://9p.io/sys/doc/mkfiles.html)
* [A Manual for the Plan 9 assembler](https://9p.io/sys/doc/asm.html)
* [8½, the Plan 9 Window System - Proc. of the Summer 1991 USENIX Conf., pp. 257-265, Nashville](https://9p.io/sys/doc/8%C2%BD/8%C2%BD.html)
* [Rc — The Plan 9 Shell](https://9p.io/sys/doc/rc.html)
* [The Text Editor sam - Paper](https://9p.io/sys/doc/sam/sam.html)
* [Acme: A User Interface for Programmers - Proc. of the Winter 1994 USENIX Conf., pp. 223-234, San Francisco, CA ](https://9p.io/sys/doc/acme/acme.html)
* [Plumbing and Other Utilities - Paper](https://9p.io/sys/doc/plumb.html)
* [Hello World or Καλημέρα κόσμε or こんにちは 世界 - Proc. of the Winter 1993 USENIX Conf., pp. 43-50, San Diego](https://9p.io/sys/doc/utf.html)
* [Plan 9 C Compilers - Proceedings of the Summer 1990 UKUUG Conference, pp. 41-51, London, 1990](https://9p.io/sys/doc/compiler.html)
* [Adding Application Support for a New Architecture in Plan 9 - Paper](https://9p.io/sys/doc/libmach.html)
* [The 64-bit Standalone Plan 9 File Server - Paper](https://9p.io/sys/doc/fs/fs.html)
* [Venti: a new approach to archival storage - Paper](https://9p.io/sys/doc/venti/venti.html)
* [The Various Ports - Paper](https://9p.io/sys/doc/port.html)
* [Plan 9 from Bell Labs manuals](https://9p.io/sys/man/)
* [Plan 9 Wiki](https://9p.io/wiki/plan9/plan_9_wiki/)

#### Specifications, documentation, manuals and historical material

* [Software for Plan 9 ](https://9p.io/plan9/addons.html)
* [Download and install Plan 9 from Bell Labs](https://9p.io/plan9/download.html)

#### Websites

* [Plan 9 from Bell Labs Community](https://9p.io/wiki/plan9/community/)
* [Plan 9 - Linux Universe (Brazil)](https://linuxuniverse.com.br/artigo/plan9)

#### Wikipedia content

* [Plan 9 from Bell Labs](https://en.wikipedia.org/wiki/Plan_9_from_Bell_Labs)

<hr>

</details>

<details title="FreeBSD" align='left'>
<br>
<summary align='left'>FreeBSD</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/5/53/FreeBSD_13.0_welcome_prompt_screenshot.png" width="400" height="200">
</p>

#### Source code

* [FreeBSD source code](https://github.com/freebsd/freebsd-src)

#### Specifications, books, papers, documentation, manuals and historical material

* [FreeBSD Handbook](https://docs.freebsd.org/en/books/handbook/)
* [FreeBSD Porter's Handbook](https://docs.freebsd.org/en/books/porters-handbook/)
* [FreeBSD Developers' Handbook](https://docs.freebsd.org/en/books/developers-handbook/)
* [FreeBSD Documentation Project Primer for New Contributors](https://docs.freebsd.org/en/books/fdp-primer/)
* [A project model for the FreeBSD Project](https://docs.freebsd.org/en/books/dev-model/)
* [FreeBSD Architecture Handbook](https://docs.freebsd.org/en/books/arch-handbook/)
* [For People New to Both FreeBSD and UNIX®](https://docs.freebsd.org/en/articles/new-users/)
* [FreeBSD Licensing Policy](https://docs.freebsd.org/en/articles/license-guide/)
* [Instroduction to NanoBSD](https://docs.freebsd.org/en/articles/nanobsd/)
* [Linux® emulation in FreeBSD](https://docs.freebsd.org/en/articles/linux-emulation/)
* [DistroWatch - FreeBSD](https://distrowatch.com/table.php?distribution=freebsd)
* [FreeBSD' IdeasPage](https://wiki.freebsd.org/IdeasPage)
* [Wiki](https://wiki.freebsd.org/)

#### Wikipedia Content

* [FreeBSD](https://en.wikipedia.org/wiki/FreeBSD)

<hr>

</details>

<details title="NetBSD" align='left'>
<br>
<summary align='left'>NetBSD</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/3b/NetBSD_9.2_xdm_screenshot.png" width="400" height="200">
</p>

#### Source code

* [NetBSD source code](https://github.com/NetBSD/src)

#### Specifications, books, papers, documentation, manuals and historical material

* [The NetBSD Guide](https://www.netbsd.org/docs/guide/en/index.html)
* [NetBSD Internals](https://www.netbsd.org/docs/internals/en/index.html)
* [Hardware Documentation - NetBSD](https://www.netbsd.org/docs/Hardware/index.html)

#### Wikipedia content

* [NetBSD](https://en.wikipedia.org/wiki/NetBSD)

<hr>

</details>

<details title="OpenBSD" align='left'>
<br>
<summary align='left'>OpenBSD</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/OpenBSD_7.0_fvwm_screenshot.png" width="400" height="200">
</p>

#### Source code

* [OpenBSD source code](https://github.com/openbsd/src)

#### Specifications, books, papers, documentation, manuals and historical material

* [OpenBSD FAQ](https://www.openbsd.org/faq/index.html)
* [OpenBSD Porter's Handbook](https://www.openbsd.org/faq/ports/index.html)

#### Wikipedia content

* [OpenBSD](https://en.wikipedia.org/wiki/OpenBSD)

<hr>

</details>

<details title="Sun Microsystems/Oracle Solaris (and SunOS)" align='left'>
<br>
<summary align='left'>Sun Microsystems/Oracle Solaris (and SunOS)</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/Solaris_Snapshot.jpg" width="400" height="200">
</p>

#### Specifications, books, papers, documentation, manuals and historical material

* [Oracle Solaris Documentation](https://docs.oracle.com/en/operating-systems/solaris.html)

#### Wikipedia content

* [Oracle Solaris](https://en.wikipedia.org/wiki/Oracle_Solaris)

<hr>

</details>

<details title="illumos (OpenSolaris)" align='left'>
<br>
<summary align='left'>illumos (OpenSolaris)</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/9/95/OpenIndiana_Hipster_2021.10_MATE_desktop_environment_screenshot.png" width="400" height="200">
</p>

#### Source code

* [illumos source code](https://github.com/illumos/illumos-gate)

#### Specifications, books, papers, documentation, manuals and historical material

* [illumos Documentation](https://illumos.org/docs/)
* [illumos developer's guide](https://illumos.org/books/dev/)
* [Dynamic Tracing Guide](https://illumos.org/books/dtrace/preface.html#preface)
* [Modular Debugger Guide](https://illumos.org/books/mdb/preface.html#preface)
* [Writing Device Drivers](https://illumos.org/books/wdd/preface.html#preface)
* [Memory and Thread Placement Optimization Developer's Guide](https://illumos.org/books/lgrps/preface.html#preface)

#### Wikipedia content

* [openSolaris](https://en.wikipedia.org/wiki/OpenSolaris)
* [illumos](https://en.wikipedia.org/wiki/Illumos)

<hr>

</details>

<details title="Minix" align='left'>
<br>
<summary align='left'>Minix</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/35/Minix_3.png" width="400" height="200">
</p>

Under construction!

<hr>

</details>

<details title="Linux" align='left'>
<br>
<summary align='left'>Linux</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Ubuntu_22.10_Kinetic_Kudu.png" width="400" height="200">
</p>

#### Source code

* [Linux kernel source code](https://kernel.org)

#### Specifications, books, papers, documentation, manuals and historical material

* [Linux Device Drivers, Second Edition](https://www.oreilly.com/library/view/linux-device-drivers/0596000081/ch03s02.html)
* [The Linux Kernel Module Programming Guide](https://sysprog21.github.io/lkmpg/)
* [The Linux Kernel documentation](https://www.kernel.org/doc/html/latest/)
* [Working with the kernel development community](https://www.kernel.org/doc/html/latest/process/)
* [Linux Kernel Teaching](https://linux-kernel-labs.github.io/refs/heads/master)
* [linux-insides](https://0xax.gitbooks.io/linux-insides/content/)
* [Linux Kernel Workbook](https://lkw.readthedocs.io/en/latest/index.html)
* [bootlins interactive Linux kernel map](https://makelinux.github.io/kernel/map/)
* [OldLinux](http://www.oldlinux.org/)
* [sam4ks Linux Kernel Resources](https://github.com/sam4k/linux-kernel-resources)
* [xairys Linux Kernel Exploitation](https://github.com/xairy/linux-kernel-exploitation)
* [Linux kernel system call table for all archs](https://marcin.juszkiewicz.com.pl/download/tables/syscalls.html)
* [The Revised Slackware Book Project](http://www.slackbook.org/)

#### Courses

* [Linux Training Course Notes - LPI 101 - PDF](http://academy.delmar.edu/Courses/ITSC1358/eBooks/LPI-101.LinuxTrainingCourseNotes.pdf)
* [Linux Kernel in a Nutshell](http://www.kroah.com/lkn/)
* [HowToForge Linux Tutorials](https://howtoforge.com/)

<hr>

<details title="Mach kernel based OSes - NEXTSTEP, OpenStep, Darwin (macOS, iOS...) and DEC OSF/1" align='left'>
<br>
<summary align='left'>Mach kernel based OSes - NEXTSTEP, OpenStep, Darwin (macOS, iOS...) and DEC OSF/1</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/en/1/1d/NeXTSTEP_desktop.png" width="400" height="200">
</p>

#### Source code

* [Mach 3 original source](https://www.cs.cmu.edu/afs/cs/project/mach/public/www/sources/sources_top.html)
* [Mach 3 - GitHub (maintained by user)](https://github.com/Prajna/mach)

#### Specifications, books, papers, documentation, manuals and historical material

* [The Mach Project](https://www.cs.cmu.edu/afs/cs/project/mach/public/www/mach.html)
* [MACH threads and the UNIX kernel: the battle for control](https://kilthub.cmu.edu/articles/journal_contribution/MACH_threads_and_the_UNIX_kernel_the_battle_for_control/6607079/1)
* [A Trusted, Scalable, Real-Time Operating System Environment - PDF](https://web.archive.org/web/20170822053715/https://pdfs.semanticscholar.org/03ac/1296f530719497b49d7580b55a2d9b8353ab.pdf)
* [Mach: A New Kernel Foundation For UNIX Development - PDF](https://www.cs.ubc.ca/~norm/508/2009W1/mach_usenix86.pdf)
* [A comparison of Mach, Amoeba and Chorus](https://web.archive.org/web/20050513191623/http://www.cdk3.net/oss/Ed2/Comparison.pdf)
* [The Mach System](https://web.archive.org/web/20130511223918/http://codex.cs.yale.edu/avi/os-book/OS8/os8e/appendices-dir/b.pdf)
* [Mach Overview - Apple](https://developer.apple.com/library/archive/documentation/Darwin/Conceptual/KernelProgramming/Mach/Mach.html)
* [Mach Kernel Interface Reference - MIT](http://web.mit.edu/darwin/src/modules/xnu/osfmk/man/)
* [The GNU Mach Reference Manual - PDF](https://www.gnu.org/software/hurd/gnumach-doc/mach.pdf)
* [A Technical History of Apple's Operating Systems](https://web.archive.org/web/20190827125517/http://www.osxbook.com/book/bonus/chapter1/)
* [Mac OS X Internals: A Systems Approach - Amazon](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542)
* [Mach Concepts](https://www.nextcomputers.org/NeXTfiles/Docs/NeXTStep/3.3/nd/OperatingSystem/Part1_Mach/01_Concepts/Concepts.htmld/index.html)

#### Wikipedia content

* [NeXTSTEP](https://en.wikipedia.org/wiki/NeXTSTEP)
* [XNU kernel](https://en.wikipedia.org/wiki/XNU)
* [Darwin Operating System](https://en.wikipedia.org/wiki/Darwin_(operating_system))

<hr>

</details>

</details>

<details title="DEC VAX/VMS and OpenVMS" align='left'>
<br>
<summary align='left'>DEC VMS</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/en/4/4b/DECwindows-openvms-v7.3-1.png" width="400" height="200">
</p>

Under construction!

<hr>

</details>

</details>

<details title="CP/M" align='left'>
<br>
<summary align='left'>CP/M</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/e/ec/Commodore_C128_CPM_Screenshot_2_full.jpg" width="400" height="200">
</p>

Under construction!

<hr>

</details>

<details title="DOS (Disk Operating System)" align='left'>
<br>
<summary align='left'>DOS (Disk Operating System)</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/b/b0/Ms-dosdir.png" width="400" height="200">
</p>

#### 86-DOS and MS-DOS

* [MS-DOS v1.25 and v2.0 source code](https://github.com/microsoft/MS-DOS)
* [VCF West XIII -- Tim Paterson -- Original DOS and the old days - YouTube](https://www.youtube.com/watch?v=R2Qh0O3Dt10)
* [The roots of DOS: Tim Paterson](https://patersontech.com/dos/softalk.aspx)
* [A Short History of MS-DOS](https://patersontech.com/dos/byte%E2%80%93history.aspx)
* [An Inside Look at MS-DOS](https://patersontech.com/dos/byte%E2%80%93inside-look.aspx)
* [The Origins of DOS - PDF](https://web.archive.org/web/20120531090452/http://www.ece.umd.edu/courses/enee759m.S2000/papers/paterson1994-kildall.pdf)
* [Undocumented DOS: a programmer's guide to reserved MS-DOS functions and data structures](https://archive.org/details/undocumenteddosp00andr_0)
* [86-DOS 1.0 Addendum - PDF](http://bitsavers.informatik.uni-stuttgart.de/pdf/seattleComputer/86-DOS_1.0_Addendum.pdf)

#### FreeDOS

* [FreeDOS Wiki](http://wiki.freedos.org/wiki/index.php/Main_Page)
* [Using FreeDOS - PDF](https://www.freedos.org/books/download/using-freedos-24.pdf)
* [Writing FreeDOS programs in C](https://www.freedos.org/books/cprogramming/)

#### Wikipedia content

* [86-DOS](https://en.wikipedia.org/wiki/86-DOS)
* [MS-DOS](https://en.wikipedia.org/wiki/MS-DOS)
* [IBM PC DOS](https://en.wikipedia.org/wiki/IBM_PC_DOS)
* [DR-DOS](https://en.wikipedia.org/wiki/DR-DOS)
* [FreeDOS](https://en.wikipedia.org/wiki/FreeDOS)

<hr>

</details>

<details title="OS/2" align='left'>
<br>
<summary align='left'>OS/2</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/en/f/f0/Os2W4.png" width="400" height="200">
</p>

Under construction!

<hr>

</details>

<details title="Windows" align='left'>
<br>
<summary align='left'>Windows</summary>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/en/b/bb/Windows_NT_3.51.png" width="400" height="200">
</p>

#### Specifications, books, papers, documentation, manuals and historical material

* [Windows technical documentation for developers and IT Pros.](https://learn.microsoft.com/en-us/windows/)
* [Windows kernel - Microsoft](https://learn.microsoft.com/en-us/windows-hardware/drivers/ddi/_kernel/)
* [NTAPI Undocumented Functions](http://undocumented.ntinternals.net/)
* [Memory management in the Windows XP kernel](https://reactos.org/wiki/Techwiki:Memory_management_in_the_Windows_XP_kernel)

#### Wikipedia content

* [Architecture of Windows NT - Wikipedia](https://en.wikipedia.org/wiki/Architecture_of_Windows_NT)

<hr>

</details>

- [x] [Go to the next section](#osdev-system-administration-applications-and-software-licenses)
- [x] [Go back to summary](#summary)

</div>

<hr>

## OSDev, system administration, applications and software licenses

<div align="justify">

In this section you will find theoretical material on the following topics:

- [x] Design and implementation of operating systems;
- [x] Hardware and architectures;
- [x] Systems administration tools and techniques;
- [x] Applications available for legacy systems and useful for project development; 
- [x] Software licenses.

> Click on one of the categories below to continue.

<details title="OSDev" align='left'>
<summary align='left'>OSdev</summary>

#### Consolidated projects for learning

* [xv6: a simple, Unix-like teaching operating system](https://pdos.csail.mit.edu/6.828/2019/xv6/book-riscv-rev0.pdf)

#### Courses

* [How to Make a Computer Operating System](https://github.com/SamyPesse/How-to-Make-a-Computer-Operating-System)
* [Operating Systems: From 0 to 1](https://github.com/tuhdo/os01)
* [Operating System Development Series](http://www.brokenthorn.com/Resources/OSDevIndex.html)
* [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
* [The little book about OS development](http://littleosbook.github.io/)
* [Think OS](http://greenteapress.com/thinkos/)
* [Operating System Concepts](https://www.os-book.com/OS9/index.html)
* [FreeBSD/Linux Kernel Cross Reference](http://fxr.watson.org/fxr/source/?v=MK84)
* [Operating System Concepts - 10th edition](https://github.com/greggagne/osc10e)
* [Open source compatible BIOS for PC - GLaBIOS](https://github.com/640-KB/GLaBIOS)

<hr>

</details>

<details title="Hardware" align='left'>
<br>
<summary align='left'>Hardware</summary>

* [w11: PDP-11/70 CPU and SoC](https://wfjm.github.io/home/w11/)

<hr>

</details>

<details title="Systems administration" align='left'>
<summary align='left'>Systems administration</summary>

#### Unix-like (general)

* [Reading UNIX Manual Pages - Apple](https://developer.apple.com/documentation/os/reading_unix_manual_pages)

<hr>

</details>

<details title="Applications" align='left'>
<summary align='left'>Applications</summary>

#### Unix-like (general)

* [WINE](https://www.winehq.org/)

<hr>

</details>

<details title="Software licenses" align='left'>
<br>
<summary align='left'>Software licenses</summary>

Here you can get more information about the main free licenses to apply in your project, or understand your rights and duties when using free software.

#### Wikipedia content

* [BSD licenses](https://en.wikipedia.org/wiki/BSD_licenses)
* [Apache license](https://en.wikipedia.org/wiki/Apache_License)
* [Apple Public Source License (APSL)](https://en.wikipedia.org/wiki/Apple_Public_Source_License)
* [Creative Commons license (CC)](https://en.wikipedia.org/wiki/Creative_Commons_license)
* [Common Development and Distribution License (CDDL)](https://en.wikipedia.org/wiki/Common_Development_and_Distribution_License)
* [GNU General Public License (GPL)](https://en.wikipedia.org/wiki/GNU_General_Public_License)
* [GNU Lesser General Public License (LGPL)](https://en.wikipedia.org/wiki/GNU_Lesser_General_Public_License)
* [MIT License](https://en.wikipedia.org/wiki/MIT_License)
* [ISC license](https://en.wikipedia.org/wiki/ISC_license)
* [Mozilla Public License (MPL)](https://en.wikipedia.org/wiki/Mozilla_Public_License)
* [Unlicense](https://en.wikipedia.org/wiki/Unlicense)

#### Exemples

<div align="center">

| License | Software |
|:-------:|:--------:|
|BSD|FreeBSD, NetBSD, Hexagonix, BareMetal, Chromium|
|Apache|Android, Clang, Fuchsia OS, Kotlin|
|APSL|XNU, Darwin|
|CC|-|
|CDDL|OpenSolaris, illumos|
|GPL|Linux Kernel, Audacity, Gedit, Git|
|LGPL|PulseAudio, FreeCAD, Qt, Wine, VLC|
|MIT|.NET, Laravel, X11|
|ISC|Hw.sensors (OpenBSD), OpenBSD (ISC modified)|
|MPL|Mozilla Firefox, LibreOffice|
|Unlicense|youtube-dl|

</div>

<hr>

</details>

- [x] [Go to the next section](#os-projects-sorted-by-family)
- [x] [Go back to summary](#summary)

</div>

<hr>

## OS projects sorted by family

<div align="justify">

In this session, the projects were separated by the operating system family to which they belong/declare. You can go straight to each repository by clicking on the project name. In the [next section](#os-projects-sorted-by-language) you can get more information about each of them.

</div>

<div align="justify">

<details title="UNIX and direct descendants" align='left'>
<br>
<summary align='left'>UNIX and direct descendants</summary>

* [Version 1 to Version 7 UNIX](https://github.com/dspinellis/unix-history-repo)
* [Version 10 UNIX](https://github.com/Alhadis/Research-Unix-v10)
* [UNIX System V](https://archive.org/details/ATTUNIXSystemVRelease4Version2)
* [UNIX PDP-7](https://github.com/asegid/pdp7-unix)
* [Plan 9 from Bell Labs](https://9p.io/plan9/)
* [9front](https://code.9front.org/hg/plan9front)
* [4.4BSD-Lite2](https://github.com/sergev/4.4BSD-Lite2)
* [FreeBSD](https://github.com/freebsd/freebsd-src)
* [NetBSD](https://github.com/NetBSD/src)
* [OpenBSD](https://github.com/openbsd/src)
* [DragonFly BSD](https://github.com/DragonFlyBSD/DragonFlyBSD)
* [MirBSD](http://www.mirbsd.org/)
* [illumos (OpenSolaris)](https://github.com/illumos/illumos-gate)

</details>

<details title="Unix-like" align='left'>
<br>
<summary align='left'>Unix-like</summary>

* [The Apollo Project](https://github.com/primis/Apollo)
* [AquilaOS](http://github.com/thethumbler/Aquila)
* [BeeOS](https://github.com/davxy/beeos)
* [Brutal](https://github.com/brutal-org/brutal)
* [dahliaOS](https://dahliaos.io/)
* [Darwin (XNU kernel)](https://github.com/apple/darwin-xnu)
* [Dennix](https://github.com/dennis95/dennix)
* [duckOS](https://github.com/byteduck/duckOS)
* [eduOS-rs](https://github.com/RWTH-OS/eduOS-rs)
* [Escape](https://github.com/Nils-TUD/Escape)
* [Fiwix](http://github.com/mikaku/Fiwix)
* [Fuchsia OS](https://fuchsia.dev/)
* [GNU Hurd](https://www.gnu.org/software/hurd/) 
* [Gramado](https://github.com/frednora/gramado) 
* [Harvey](https://github.com/Harvey-OS/harvey)
* [HelenOS](https://github.com/HelenOS/helenos)
* [Hexagonix](https://github.com/hexagonix)
* [KnightOS](https://github.com/KnightOS/KnightOS)
* [Lemon OS](https://github.com/LemonOSProject/LemonOS)
* [Linux (kernel)](https://github.com/torvalds/linux)
* [lk](https://github.com/littlekernel/lk)
* [Lunix OS](https://github.com/felipenlunkes/lunix)
* [MentOS](https://github.com/mentos-team/MentOS)
* [Mimiker](https://github.com/cahirwpz/mimiker)
* [Minix](http://minix3.org/)
* [Nanvix](https://github.com/nanvix/nanvix)
* [NexNix](https://github.com/nexos-dev/nexnix)
* [nightingale](https://github.com/tyler569/nightingale)
* [OS67](https://github.com/SilverRainZ/OS67)
* [qword-OS](https://github.com/qword-os/qword)
* [SeaOS](https://github.com/dbittman/seakernel)
* [SerenityOS](https://github.com/SerenityOS/serenity)
* [Sortix](https://sortix.org/)
* [Soso](https://github.com/ozkl/soso)
* [Tilck](https://github.com/vvaltchev/tilck)
* [ToaruOS](http://github.com/klange/toaruos)
* [TravorOS](https://github.com/TravorLZH/TravorOS)
* [TROPIX (NCE/UFRJ)](https://github.com/felipenlunkes/TROPIX)
* [Tupai](https://gitlab.com/zesterer/tupai/)
* [µnix](https://github.com/cute-engineewing/munix)
* [Unix-like](https://github.com/MaoKo/Unix-Like)
* [Uzi](https://github.com/paulie-g/uzi)
* [UZIX](https://uzix.sourceforge.net/uzix2.0/index.php?page=down&lang=pt)
* [Upanix](https://github.com/prajwal83/upanix)
* [Vanadium OS](https://github.com/p-durlej/newsys)
* [xv6](https://github.com/mit-pdos/xv6-public)
* [ZeldaOS](https://github.com/chillancezen/ZeldaOS)

</details>

<details title="DOS (Disk Operating System)" align='left'>
<br>
<summary align='left'>DOS (Disk Operating System)</summary>

* [AtieDOS](https://github.com/AtieP/AtieDOS)
* [FreeDOS](http://www.freedos.org/)
* [JSD/OS](https://github.com/pgrAm/JSD-OS)
* [MS-DOS](https://github.com/microsoft/MS-DOS)
* [NetDOS/32](https://github.com/clementtttttttt/NetDOS-32)
* [NightKernel](https://github.com/mercury0x000d/NightKernel)
* [Public Domain Operating System](http://pdos.org/)
* [PC-MOS/386](https://github.com/roelandjansen/pcmos386v501)
* [PX-DOS](https://github.com/felipenlunkes/PX-DOS-Core)
* [SimpleOS](https://github.com/xing1357/SimpleOS/)

</details>

<details title="Windows and Windows-like" align='left'>
<br>
<summary align='left'>Windows and Windows-like</summary>

* [ReactOS](http://www.reactos.com/)

</details>

<details title="BeOS-like" align='left'>
<br>
<summary align='left'>BeOS-like</summary>

* [Haiku](https://github.com/GreenteaOS)
* [NewOS](https://github.com/travisg/newos)

</details>

<details title="Other (original design)" align='left'>
<br>
<summary align='left'>Other (original design)</summary>

* [ackOS](https://github.com/ackOS-project/ackOS)
* [Alotware](https://github.com/0x5CE/alotware)
* [Amiga Research Operating System](https://github.com/aros-development-team/AROS)
* [AQUA OS](https://github.com/inobulles/aquabsd-core)
* [Asuro](https://www.spexeah.com/index.php/asuro/)
* [Aura](https://github.com/projectasiago/aura)
* [AwooOS](https://github.com/awooos/awooos)
* [aurora-xeneva](https://github.com/manaskamal/aurora-xeneva)
* [azOS](https://github.com/azarovalex/azOS)
* [Banana Operating System](https://github.com/alexdboxall/Banana-Operating-System)
* [BareMetal](https://github.com/ReturnInfinity/BareMetal-OS)
* [BCOS](http://bcos.hopto.org/)
* [Beelzebub](https://github.com/vercas/Beelzebub)
* [BetaOS](https://github.com/admkopec/BetaOS)
* [Bin S.O](https://github.com/felipenlunkes/Bin-S.O)
* [BleskOS](https://github.com/Klaykap/BleskOS)
* [BlueKernel](http://www.bluekernel.com.au/)
* [BoneOS](https://github.com/Bone-Project/BoneOS)
* [Carbon](https://github.com/davidaylaian/carbon)
* [ChaiOS](https://github.com/ChaiSoft/ChaiOS)
* [Cloudium OS](https://sourceforge.net/projects/cloudium-os/)
* [Cthulhu OS](https://github.com/Enerccio/Cthulhu-OS)
* [Cyjon](https://github.com/CorruptedByCPU/Cyjon/)
* [Dawn OS](http://gerigeri.uw.hu/DawnOS/index.html)
* [DreamOS](https://github.com/inuyasha82/DreamOs)
* [DreamOS64](https://github.com/dreamos82/Dreamos64)
* [Dux](https://github.com/duckinator/dux)
* [Einherjar](https://github.com/narke/Einherjar)
* [ErdOS](https://github.com/gabrielbiga/ErdOS)
* [Everest OS](https://github.com/felipenlunkes/EverestOS)
* [Fling OS](https://github.com/FlingOS/FlingOS)
* [FoxOS](https://github.com/TheUltimateFoxOS/horizon)
* [FROST](https://github.com/thrimbor/frost)
* [Fudge](http://github.com/jezze/fudge/)
* [FuzzyOS](https://github.com/scopeInfinity/FuzzyOS)
* [GeckOS version 2](https://github.com/fachat/GeckOS-V2)
* [Ghost OS](https://github.com/maxdev1/ghost/)
* [Gubernatrix](https://gitlab.com/hgoel0974/gubernatrix)
* [GreenteaOS](https://github.com/GreenteaOS)
* [HeliX](https://github.com/Helix-OS/helix-os)
* [HelloOS](https://github.com/kbu1564/HelloOS)
* [Hoho](https://github.com/davidepianca98/hoho-os)
* [Hydrogen](https://moondeck.github.io/hydrogen/)
* [HypnoticOS](https://github.com/hypnoticos/hypnoticos)
* [Interim](https://github.com/mntmn/interim)
* [JaeOS](https://github.com/azsoter/jaeos-devel)
* [JSLK](https://github.com/sofferjacob/jslk)
* [Kan](https://github.com/kan-os/kan)
* [KLIKA-OS](https://github.com/klikaba/klika-os)
* [Kolibri OS](http://www.kolibrios.org/)
* [Kora OS](https://github.com/AxFab/kora-kernel)
* [KOS](https://github.com/guilt/KOS)
* [Kot](https://github.com/kot-org/Kot)
* [Lambda OS](https://github.com/farlepet/lambda-os)
* [LFOS](https://github.com/LittleFox94/lf-os_amd64)
* [Lotus-Effect](https://github.com/CorruptedByCPU/Lotus-Effect/)
* [Lyre](https://github.com/lyre-os/lyre)
* [MajickOS](https://github.com/MajickTek/MajickOS/wiki)
* [Managarm](http://www.managarm.org/)
* [MenuetOS](http://www.menuetos.net/)
* [Metta](https://github.com/berkus/metta/wiki)
* [Mezzano](https://github.com/froggey/Mezzano)
* [MicroBe OS](http://www.microbe.cz/)
* [mikanos](https://github.com/uchan-nos/mikanos)
* [MikeOS](http://mikeos.sourceforge.net/)
* [Minoca](https://github.com/minoca/os)
* [Minos](https://github.com/triforce/minos)
* [MiraiOS](https://github.com/LNooteboom/MiraiOS)
* [mkfreeOS](https://github.com/ramonmayedo/mkfreeOS)
* [MollenOS](https://github.com/Meulengracht/MollenOS)
* [MOROS](https://github.com/vinc/moros)
* [mos](https://github.com/MQuy/mos)
* [Mu](https://github.com/akkartik/mu)
* [MysticOS](http://www.d-rift.nl/combuster/mos3/)
* [Nano16](https://github.com/NANO-DEV/NANO-S16)
* [Nano32](https://github.com/NANO-DEV/NANO-S32)
* [NanoShellOS](https://github.com/iProgramMC/NanoShellOS)
* [NOS](https://github.com/xenos1984/NOS)
* [OLOS](https://github.com/leonardo-ono/Assembly8086OLOS)
* [OS](http://sourceforge.net/projects/lowest-kernel/files/)
* [OSv](https://github.com/cloudius-systems/osv)
* [OS/K](https://git.a-lec.org/os-k-team/os-on-kaleid)
* [OS/Z](https://bztsrc.gitlab.io/osz/)
* [opuntiaOS](https://github.com/opuntiaOS-Project/opuntiaOS)
* [PastaOS](https://github.com/arighi/pastaos)
* [PC/GEOS](https://github.com/bluewaysw/pcgeos)
* [Perception](https://github.com/AndrewAPrice/Perception)
* [pidi-os](https://github.com/GandelXIV/pidi-os)
* [PiscisOS](https://github.com/tishion/PiscisOS)
* [Plan 42](https://github.com/mooseman/plan_42)
* [PlusOS](https://sourceforge.net/projects/plusos/)
* [Polaris](https://github.com/NSG650/Polaris)
* [PowerNex](https://github.com/PowerNex/PowerNex)
* [PrettyOS](http://prettyos.de/)
* [primus-os](https://github.com/araujo88/primus-os)
* [Q Operating System](https://github.com/raphydaphy/Q-Operating-System)
* [Quark Operating System](https://github.com/quark-os/quark-os)
* [QuasiOS](https://git.imada.sdu.dk/Sandsized/QuasiOS-64-bit)
* [RDOS](http://www.rdos.net/)
* [Reaver OS](https://github.com/griwes/ReaverOS)
* [Red OS](https://github.com/primis/redos)
* [Redox-OS](https://github.com/redox-os/redox/)
* [RISC OS](http://riscosopen.org/)
* [Segmented Kernel (educational)](https://github.com/MaoKo/Segmented_Kernel)
* [seL4](https://github.com/seL4/seL4)
* [SerpaeOS](https://serpaeos.sourceforge.io/)
* [Silcos](https://github.com/SukantPal/Silcos-Kernel)
* [SingOS](https://git.imada.sdu.dk/Sandsized/SingOS)
* [SivelkiriaOS](https://git.sivelkiria.org/)
* [skiftOS](https://github.com/skiftOS/skift)
* [Snowdrop OS](http://sebastianmihai.com/snowdrop/)
* [SnowflakeOS](https://github.com/29jm/SnowflakeOS)
* [SO3](https://gitlab.com/smartobject/so3)
* [SynapseOS](https://github.com/0Nera/SynapseOS)
* [The Stupid Operating System](https://github.com/sos-os/kernel)
* [Synergy OS](https://github.com/JackScottAU/Synergy-OS)
* [tachyon](https://github.com/mduft/tachyon3)
* [tatOS](https://github.com/tatimmer/tatOS)
* [TempleOS](http://templeos.org/)
* [Theseus](https://github.com/theseus-os/Theseus)
* [Thor Operating System](https://github.com/wichtounet/thor-os)
* [TinyOS](https://github.com/tinyos/tinyos-main)
* [Týndur](https://git.tyndur.org/lowlevel/tyndur/commits/master)
* [Tysos](https://github.com/jncronin/tysos)
* [Unet Operating System](https://unet.lithicsoft.repl.co/)
* [Ultibo Core](https://github.com/ultibohub/Core)
* [ultronOS](https://github.com/aswinmohanme/ultronOS)
* [U365](http://gitlab.com/bps-projs/U365)
* [Visopsys](http://visopsys.org/)
* [VSTa](http://sources.vsta.org:7100/vsta/index)
* [WingOS](https://github.com/Supercip971/WingOS_x64/)
* [XEOS](http://www.xs-labs.com/en/projects/xeos/)
* [xOS](https://github.com/BrownieOS/xOS)
* [YaxOS](https://gitlab.com/SopaXorzTaker/yaxos)
* [ZealOS](https://github.com/Zeal-Operating-System/ZealOS)
* [Zeal 8-bit OS](https://github.com/Zeal8bit/Zeal-8-bit-OS)

</details>

<details title="Mainframe OS" align='left'>
<br>
<summary align='left'>Mainframe OS</summary>

* [MVS/380](https://sourceforge.net/projects/mvs380/)
* [uDOS](https://github.com/SuperLeaf1995/uDOS)

</details>

- [x] [Go to the next section](#os-projects-sorted-by-language)
- [x] [Go back to summary](#summary)

</div>

<hr>

## OS projects sorted by language

<div align="justify">

In this session, the projects were separated by the main programming language used. You can also look at information like:

- [x] Architecture;
- [x] Operating system family;
- [x] If the project is hosted on GitHub;
- [x] If the project is active (commits more recent than 4 years);
- [x] License of each project.

<p><strong>Let's take a shortcut! Choose below a language used to write operating system projects:</strong></p>

</div>

<div align="center">

[![Assembly](https://img.shields.io/badge/Assembly-AB2B28?style=for-the-badge&logo=assembly&logoColor=white)](#assembly-language)
[![Basic](https://img.shields.io/badge/Basic-F2CA30?style=for-the-badge&logo=basic&logoColor=black)](#basic)
[![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)](#c)
[![Cplusplus](https://img.shields.io/badge/C_Plus_Plus-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](#c-1)
[![Csharp](https://img.shields.io/badge/C_Sharp-8419D1?style=for-the-badge&logo=csharp&logoColor=white)](#c-2)
[![Common Lisp](https://img.shields.io/badge/Common_Lisp-C9284D?style=for-the-badge&logo=lisp&logoColor=black)](#common-lisp)
[![D](https://img.shields.io/badge/D-B7472A?style=for-the-badge&logo=D&logoColor=white)](#d)
[![Pascal](https://img.shields.io/badge/Pascal-68A51C?style=for-the-badge&logo=pascal&logoColor=black)](#pascal)
[![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)](#swift)
[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](#rust)

</div>

### Assembly language

<div align="center">

| Name | Language | Architecture | OS family | Available on GitHub | Active | License |
|:----:|:--------:|:------------:|:---------:|:-------------------:|:------:|:-------:|
|[Version 1 to Version 7 UNIX](https://github.com/dspinellis/unix-history-repo)|Assembly (early versions) and C|PDP-7, PDP-11| Unix | Yes | No (historical)|![](https://img.shields.io/github/license/dspinellis/unix-history-repo.svg)|
|[UNIX PDP-7](https://github.com/asegid/pdp7-unix)|Assembly|PDP-7|Unix|Yes|No|![](https://img.shields.io/github/license/asegid/pdp7-unix.svg)|
|[Alotware](https://github.com/0x5CE/alotware)|Assembly|x86|Other|Yes|No|Public domain|
|[AtieDOS](https://github.com/AtieP/AtieDOS)|Assembly|x86 (16-bit)|DOS|Yes|Yes|![](https://img.shields.io/github/license/AtieP/AtieDOS.svg)|
|[azOS](https://github.com/azarovalex/azOS)|Assembly|x86 (16-bit)|Other|Yes|No|![](https://img.shields.io/github/license/azarovalex/azOS.svg)|
|[BareMetal](https://github.com/ReturnInfinity/BareMetal)|Assembly|x86|Other|Yes|No|![](https://img.shields.io/github/license/ReturnInfinity/BareMetal.svg)|
|[Bin S.O](https://github.com/felipenlunkes/Bin-S.O)|Assembly|x86 (16-bit)|Other|Yes|No|![](https://img.shields.io/github/license/felipenlunkes/Bin-S.O.svg)|
|[BleskOS](https://github.com/Klaykap/BleskOS)|Assembly|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/Klaykap/BleskOS.svg)|
|[Cloudium OS](https://sourceforge.net/projects/cloudium-os/)|Assembly|x86|Other|No|Yes|Unknown|
|[Cyjon](https://github.com/CorruptedByCPU/Cyjon/)|Assembly|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/CorruptedByCPU/Cyjon.svg)|
|[Everest OS](https://github.com/felipenlunkes/EverestOS)|Assembly|x86 (16-bit)|Other|Yes|No|![](https://img.shields.io/github/license/felipenlunkes/EverestOS.svg)|
|[HelloOS](https://github.com/kbu1564/HelloOS)|Assembly|x86|Other|Yes|No|![](https://img.shields.io/github/license/kbu1564/HelloOS.svg)|
|[Hexagonix](https://github.com/hexagonix/)|Assembly|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/Hexagonix/hexagonix.svg)|
|[KnightOS](https://github.com/KnightOS/KnightOS)|Assembly|Texas Instruments Calculators|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/KnightOS/KnightOS.svg)|
|[Kolibri OS](http://www.kolibrios.org/)|Assembly|x86|Other|No|Yes|GPLv2|
|[MenuetOS](http://www.menuetos.net/)|Assembly|x86, x86_64|Other|No|Yes|GPL|
|[MicroBe OS](http://www.microbe.cz/)|Assembly|x86|Other|No|Yes|Unknown|
|[MikeOS](http://mikeos.sourceforge.net/)|Assembly|x86 (16-bit)|Other|No|Yes|BSD-like|
|[Minos](https://github.com/triforce/minos)|Assembly|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/triforce/minos.svg)|
|[MS-DOS](https://github.com/microsoft/MS-DOS)|Assembly|x86 (16-bit)|DOS|Yes|No (historical)|![](https://img.shields.io/github/license/microsoft/MS-DOS.svg)|
|[Mu](https://github.com/akkartik/mu)|Assembly, Forth|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/akkartik/mu.svg)|
|[NightKernel](https://github.com/mercury0x000d/NightKernel)|Assembly|x86|DOS|Yes|No|![](https://img.shields.io/github/license/mercury0x000d/NightKernel.svg)|
|[OLOS](https://github.com/leonardo-ono/Assembly8086OLOS)|Assembly|x86 (16-bit)|Other|Yes|Yes|![](https://img.shields.io/github/license/leonardo-ono/Assembly8086OLOS.svg)|
|[PC/GEOS](https://github.com/bluewaysw/pcgeos)|Assembly|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/bluewaysw/pcgeos.svg)|
|[PC-MOS/386](https://github.com/roelandjansen/pcmos386v501)|Assembly|x86|DOS|Yes|No|![](https://img.shields.io/github/license/roelandjansen/pcmos386v501.svg)|
|[PiscisOS](https://github.com/tishion/PiscisOS)|Assembly|x86|Other|Yes|No|![](https://img.shields.io/github/license/tishion/PiscisOS.svg)|
|[Segmented Kernel (educational)](https://github.com/MaoKo/Segmented_Kernel)|Assembly|x86|Other|Yes|Yes|MIT license|
|[Snowdrop OS](http://sebastianmihai.com/snowdrop/)|Assembly|x86 (16-bit)|Other|No|Yes|Public domain|
|[tatOS](https://github.com/tatimmer/tatOS)|Assembly|x86|Other|Yes|No|![](https://img.shields.io/github/license/tatimmer/tatOS.svg)|
|[Unix-like](https://github.com/MaoKo/Unix-Like)|Assembly|x86|Unix-like|Yes|Yes|MIT license|
|[xOS](https://github.com/BrownieOS/xOS)|Assembly|x86|Other|Yes|No|![](https://img.shields.io/github/license/BrownieOS/xOS.svg)|
|[Zeal 8-bit OS](https://github.com/Zeal8bit/Zeal-8-bit-OS)|Assembly|Z80|Other|Yes|Yes|![](https://img.shields.io/github/license/Zeal8bit/Zeal-8-bit-OS.svg)|

</div>

- [x] [Go up](#os-projects-sorted-by-language)

### Basic

<div align="center">

| Name | Language | Architecture | OS family | Available on GitHub | Active | License |
|:----:|:--------:|:------------:|:---------:|:-------------------:|:------:|:-------:|
|[FROST](https://github.com/thrimbor/frost)|Basic (FreeBasic)|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/thrimbor/frost.svg)|

</div>

- [x] [Go up](#os-projects-sorted-by-language)

### C

<div align="center">

| Name | Language | Architecture | OS family | Available on GitHub | Active | License |
|:----:|:--------:|:------------:|:---------:|:-------------------:|:------:|:-------:|
|[Version 10 UNIX](https://github.com/Alhadis/Research-Unix-v10)|C|-|Unix|Yes|No (historical)|![](https://img.shields.io/github/license/Alhadis/Research-Unix-v10.svg)|
|[UNIX System V](https://archive.org/details/ATTUNIXSystemVRelease4Version2)|C|PDP-11, VAX 11/780, x86|Unix|No|No (historical)|Check files|
|[Plan 9 from Bell Labs](https://9p.io/plan9/)|C|x86|Unix|No|Yes|-|
|[9front](https://code.9front.org/hg/plan9front)|C|x86|Unix|No|Yes|-|
|[4.4BSD-Lite2](https://github.com/sergev/4.4BSD-Lite2)|C|x86, PowerPC, MIPS|Unix|Yes|No|BSD license|
|[FreeBSD](https://github.com/freebsd/freebsd-src)|C|x86, ARM, PowerPC, RISC-V|Unix|Yes|Yes|![](https://img.shields.io/github/license/freebsd/freebsd-src.svg)|
|[NetBSD](https://github.com/NetBSD/src)|C|x86, ARM, PowerPC, RISC-V|Unix|Yes|Yes|![](https://img.shields.io/github/license/NetBSD/src.svg)|
|[OpenBSD](https://github.com/openbsd/src)|C|x86, ARM, PowerPC, RISC-V|Unix|Yes|Yes|![](https://img.shields.io/github/license/openbsd/src.svg)|
|[DragonFly BSD](https://github.com/DragonFlyBSD/DragonFlyBSD)|C|x86_64|Unix|Yes|Yes|BSD license|
|[MirBSD](http://www.mirbsd.org/)|C|x86|Unix|No|Yes|BSD license|
|[illumos (OpenSolaris)](https://github.com/illumos/illumos-gate)|C|x86, SPARC|Unix|Yes|Yes|![](https://img.shields.io/github/license/illumos/illumos-gate.svg)|
|[Amiga Research Operating System](https://github.com/aros-development-team/AROS)|C|m68k, x86, x86_64, PowerPC, ARM|Other (Amiga)|Yes|Yes|![](https://img.shields.io/github/license/aros-development-team/AROS.svg)|
|[The Apollo Project](https://github.com/primis/Apollo)|C|x86, Raspberry Pi Model 4B|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/primis/Apollo.svg)|
|[AQUA OS](https://github.com/inobulles/aquabsd-core)|C|x86_64|Unix (FreeBSD)|Yes|Yes|![](https://img.shields.io/github/license/inobulles/aquabsd-core.svg)|
|[AquilaOS](http://github.com/thethumbler/Aquila)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/thethumbler/Aquila.svg)|
|[AwooOS](https://github.com/awooos/awooos)|C|x86, x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/awooos/awooos.svg)|
|[Banana Operating System](https://github.com/alexdboxall/Banana-Operating-System)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/alexdboxall/Banana-Operating-System.svg)|
|[BeeOS](https://github.com/davxy/beeos)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/davxy/beeos.svg)|
|[BlueKernel](http://www.bluekernel.com.au/)|C|x86|Other|Yes|Yes|Creative Commons Attribution-NonCommercial-NoDerivatives 4.0|
|[BoneOS](https://github.com/Bone-Project/BoneOS)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/Bone-Project/BoneOS.svg)|
|[Brutal](https://github.com/brutal-org/brutal)|C|x86, x86_64, ARM, RISC-V|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/brutal-org/brutal.svg)|
|[Carbon](https://github.com/davidaylaian/carbon)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/davidaylaian/carbon.svg)|
|[Cthulhu OS](https://github.com/Enerccio/Cthulhu-OS)|C|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/Enerccio/Cthulhu-OS.svg)|
|[Darwin (XNU kernel)](https://github.com/apple/darwin-xnu)|C|x86_64, ARM, ARM AArch64, PowerPC|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/apple/darwin-xnu.svg)|
|[DreamOS](https://github.com/inuyasha82/DreamOs)|C|x86|Other|Yes|No|![](https://img.shields.io/github/license/inuyasha82/DreamOs.svg)|
|[DreamOS64](https://github.com/dreamos82/Dreamos64)|C|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/dreamos82/Dreamos64.svg)|
|[duckOS](https://github.com/byteduck/duckOS)|C, C++|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/byteduck/duckOS.svg)|
|[Dux](https://github.com/duckinator/dux)|C|x86|Other|Yes|No|![](https://img.shields.io/github/license/duckinator/dux.svg)|
|[Einherjar](https://github.com/narke/Einherjar)|C|x86_64, PowerPC|Other|Yes|Yes|![](https://img.shields.io/github/license/narke/Einherjar.svg)|
|[Escape](https://github.com/Nils-TUD/Escape)|C, C++|x86, x86_64, ECO32, MMIX|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/Nils-TUD/Escape.svg)|
|[Fiwix](http://github.com/mikaku/Fiwix)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/mikaku/Fiwix.svg)|
|[FreeDOS](https://github.com/FDOS/kernel)|C|x86 (16-bit)|DOS|Yes|Yes|![](https://img.shields.io/github/license/FDOS/kernel.svg)|
|[Fudge](http://github.com/jezze/fudge/)|C|x86, ARM|Other|Yes|Yes|![](https://img.shields.io/github/license/jezze/fudge.svg)|
|[FuzzyOS](https://github.com/scopeInfinity/FuzzyOS)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/scopeInfinity/FuzzyOS.svg)|
|[Fuchsia OS](https://fuchsia.dev/)|C, C++|x86_64, ARM, ARM AArch64|Unix-like|No|Yes|Apache|
|[GeckOS version 2](https://github.com/fachat/GeckOS-V2)|C|6502|Other|Yes|Yes|![](https://img.shields.io/github/license/fachat/GeckOS-V2.svg)|
|[GNU Hurd](https://www.gnu.org/software/hurd/)|C|x86|Unix-like|No|Yes|GPL|  
|[Gramado](https://github.com/frednora/gramado)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/frednora/gramado.svg)|
|[Harvey](https://github.com/Harvey-OS/harvey)|C|x86|Unix (Plan 9)|Yes|Yes|![](https://img.shields.io/github/license/Harvey-OS/harvey.svg)|
|[HelenOS](https://github.com/HelenOS/helenos)|C, C++|x86, x86_64, i64, ARM, SPARC|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/HelenOS/helenos.svg)|
|[HeliX](https://github.com/Helix-OS/helix-os)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/Helix-OS/helix-os.svg)|
|[Hoho](https://github.com/davidepianca98/hoho-os)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/davidepianca98/hoho-os.svg)|
|[HypnoticOS](https://github.com/hypnoticos/hypnoticos)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/hypnoticos/hypnoticos.svg)|
|[Interim](https://github.com/mntmn/interim)|C|x86, x86_64, ARMv7, Motorola 68020|Other|Yes|Yes|![](https://img.shields.io/github/license/mntmn/interims.svg)|
|[JaeOS](https://github.com/azsoter/jaeos-devel)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/azsoter/jaeos-devel.svg)|
|[JSLK](https://github.com/sofferjacob/jslk)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/sofferjacob/jslk.svg)|
|[Kan](https://github.com/kan-os/kan)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/kan-os/kan.svg)|
|[KLIKA-OS](https://github.com/klikaba/klika-os)|C|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/klikaba/klika-os.svg)|
|[Kora OS](https://github.com/AxFab/kora-kernel)|C|x86, x86_64, ARM|Other|Yes|Yes|![](https://img.shields.io/github/license/AxFab/kora-kernel.svg)|
|[KOS](https://github.com/guilt/KOS)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/guilt/KOS.svg)|
|[Lambda OS](https://github.com/farlepet/lambda-os)|C|x86, ARMv7|Other|Yes|Yes|![](https://img.shields.io/github/license/farlepet/lambda-kern.svg)|
|[LFOS](https://github.com/LittleFox94/lf-os_amd64)|C|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/LittleFox94/lf-os_amd64.svg)|
|[Linux (kernel)](https://github.com/torvalds/linux)|C|x86, x86_64, ARM, ARM AArch64, SPARC, PowerPC, RISC-V, [...]|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/torvalds/linux.svg)|
|[lk](https://github.com/littlekernel/lk)|C|x86, ARM|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/littlekernel/lk.svg)|
|[Lotus-Effect](https://github.com/CorruptedByCPU/Lotus-Effect/)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/CorruptedByCPU/Lotus-Effect.svg)|
|[Lunix OS](https://github.com/felipenlunkes/lunix)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/felipenlunkes/lunix.svg)|
|[Lyre](https://github.com/lyre-os/lyre)|C|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/lyre-os/lyre.svg)|
|[MentOS](https://github.com/mentos-team/MentOS)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/mentos-team/MentOS.svg)|
|[Mimiker](https://github.com/cahirwpz/mimiker)|C|x86, MIPS, AArch64, RISC-V|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/cahirwpz/mimiker.svg)|
|[Minix](https://github.com/Stichting-MINIX-Research-Foundation/minix)|C|x86, arm64|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/Stichting-MINIX-Research-Foundation/minix.svg)|
|[Minoca](https://github.com/minoca/os)|C|-|Other|Yes|Yes|![](https://img.shields.io/github/license/minoca/os.svg)|
|[MiraiOS](https://github.com/LNooteboom/MiraiOS)|C|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/LNooteboom/MiraiOS.svg)|
|[MollenOS](https://github.com/Meulengracht/MollenOS)|C|-|Other|Yes|Yes|![](https://img.shields.io/github/license/Meulengracht/MollenOS.svg)|
|[mos](https://github.com/MQuy/mos)|C|-|Other|Yes|Yes|![](https://img.shields.io/github/license/MQuy/mos.svg)|
|[Nano16](https://github.com/NANO-DEV/NANO-S16)|C|x86 (16-bit)|Other|Yes|Yes|![](https://img.shields.io/github/license/NANO-DEV/NANO-S16.svg)|
|[Nano32](https://github.com/NANO-DEV/NANO-S32)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/NANO-DEV/NANO-S32.svg)|
|[NanoShellOS](https://github.com/iProgramMC/NanoShellOS)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/iProgramMC/NanoShellOS.svg)|
|[Nanvix](https://github.com/nanvix/nanvix)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/nanvix/nanvix.svg)|
|[NetDOS/32](https://github.com/clementtttttttt/NetDOS-32)|C|x86|DOS|Yes|No|![](https://img.shields.io/github/license/clementtttttttt/NetDOS-32.svg)|
|[NexNix](https://github.com/nexos-dev/nexnix)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/nexos-dev/nexnix.svg)|
|[NewOS](https://github.com/travisg/newos)|C|x86|BeOS-like|Yes|Yes|![](https://img.shields.io/github/license/travisg/newos.svg)|
|[nightingale](https://github.com/tyler569/nightingale)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/tyler569/nightingale.svg)|
|[opuntiaOS](https://github.com/opuntiaOS-Project/opuntiaOS)|C|x86, ARM|Other|Yes|Yes|![](https://img.shields.io/github/license/opuntiaOS-Project/opuntiaOS.svg)|
|[OS67](https://github.com/SilverRainZ/OS67)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/SilverRainZ/OS67.svg)|
|[OSv](https://github.com/cloudius-systems/osv)|C|x86, ARM AArch64|Other|Yes|Yes|![](https://img.shields.io/github/license/cloudius-systems/osv.svg)|
|[OS67](https://github.com/SilverRainZ/OS67)|C|-|Other|Yes|Yes|![](https://img.shields.io/github/license/SilverRainZ/OS67.svg)|
|[PastaOS](https://github.com/arighi/pastaos)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/arighi/pastaos.svg)|
|[pidi-os](https://github.com/GandelXIV/pidi-os)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/GandelXIV/pidi-os.svg)|
|[Polaris](https://github.com/NSG650/Polaris)|C|-|Other|Yes|Yes|![](https://img.shields.io/github/license/NSG650/Polaris.svg)|
|[primus-os](https://github.com/araujo88/primus-os)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/araujo88/primus-os.svg)|
|[Public Domain Operating System](http://pdos.org/)|C|x86 (16-bit, 32-bit)|DOS|No|Yes|Public Domain|
|[PX-DOS](https://github.com/felipenlunkes/PX-DOS-Core)|C|x86 (16-bit)|DOS|Yes|No|![](https://img.shields.io/github/license/felipenlunkes/PX-DOS-Core.svg)|
|[Q Operating System](https://github.com/raphydaphy/Q-Operating-System)|C|x86_64|Other|Yes|No|![](https://img.shields.io/github/license/raphydaphy/Q-Operating-System.svg)|
|[qword-OS](https://github.com/qword-os/qword)|C|x86_64|Unix-like|Yes|No|![](https://img.shields.io/github/license/qword-os/qword.svg)|
|[ReactOS](https://github.com/reactos/reactos)|C|x86|Windows|Yes|Yes|![](https://img.shields.io/github/license/reactos/reactos.svg)|
|[Red OS](https://github.com/primis/redos)|C|x86|Other|Yes|No|![](https://img.shields.io/github/license/primis/redos.svg)|
|[SeaOS](https://github.com/dbittman/seakernel)|C|x86_64|Unix-like|Yes|No|![](https://img.shields.io/github/license/dbittman/seakernel.svg)|
|[seL4](https://github.com/seL4/seL4)|C|-|L4|Yes|Yes|![](https://img.shields.io/github/license/seL4/seL4.svg)|
|[SerpaeOS](https://serpaeos.sourceforge.io/)|C|x86|Other|No|Yes|GPLv3|
|[SimpleOS](https://github.com/xing1357/SimpleOS/)|C|x86|DOS|Yes|Yes|![](https://img.shields.io/github/license/xing1357/SimpleOS.svg)|
|[SnowflakeOS](https://github.com/29jm/SnowflakeOS)|C|x86|Other|Yes|No|![](https://img.shields.io/github/license/29jm/SnowflakeOS.svg)|
|[Sortix](https://sortix.org/)|C|x86, x86_64|Unix-like|No|Yes|ISC license|
|[Soso](https://github.com/ozkl/soso)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/ozkl/soso.svg)|
|[SynapseOS](https://github.com/0Nera/SynapseOS)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/0Nera/SynapseOS.svg)|
|[Synergy OS](https://github.com/JackScottAU/Synergy-OS)|C|x86|Other|Yes|No|![](https://img.shields.io/github/license/JackScottAU/Synergy-OS.svg)|
|[tachyon](https://github.com/mduft/tachyon3)|C|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/mduft/tachyon3.svg)|
[TempleOS](http://templeos.org/)|C|x86|Other|No|No|Public domain|
|[Tilck](https://github.com/vvaltchev/tilck)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/vvaltchev/tilck.svg)|
|[TinyOS](https://github.com/tinyos/tinyos-main)|C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/tinyos/tinyos-main.svg)|
|[ToaruOS](http://github.com/klange/toaruos)|C|x86_64, ARMv8|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/klange/toaruos.svg)|
|[TravorOS](https://github.com/TravorLZH/TravorOS)|C|x86|Unix-like|Yes|No|![](https://img.shields.io/github/license/TravorLZH/TravorOS.svg)|
|[TROPIX (NCE/UFRJ)](https://github.com/felipenlunkes/TROPIX)|C|x86|Unix-like|Yes|No|![](https://img.shields.io/github/license/felipenlunkes/TROPIX.svg)|
|[Tupai](https://gitlab.com/zesterer/tupai/)|C|x86, ARM|Unix-like|No|Yes|GNU General Public License version 3|
|[Uzi](https://github.com/paulie-g/uzi)|C|z80|Unix-like|Yes|Yes|Public domain|
|[UZIX](https://uzix.sourceforge.net/uzix2.0/index.php?page=down&lang=pt)|C|z80, MSX|Unix-like|No|No|GPL|
|[Vanadium OS](https://github.com/p-durlej/newsys)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/p-durlej/newsys.svg)|
|[xv6](https://github.com/mit-pdos/xv6-public)|C|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/mit-pdos/xv6-public.svg)|
|[ZealOS](https://github.com/Zeal-Operating-System/ZealOS)|C (HolyC)|x86_64|Other (TempleOS)|Yes|Yes|![](https://img.shields.io/github/license/Zeal-Operating-System/ZealOS.svg)|
|[ZeldaOS](https://github.com/chillancezen/ZeldaOS)|C|x86, x86_64|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/chillancezen/ZeldaOS.svg)|

</div>

- [x] [Go up](#os-projects-sorted-by-language)

<!-- Em atualização -->

### C++

<div align="center">

| Name | Language | Architecture | OS family | Available on GitHub | Active | License |
|:----:|:--------:|:------------:|:---------:|:-------------------:|:------:|:-------:|
|[ackOS](https://github.com/ackOS-project/ackOS)|C++|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/ackOS-project/ackOS.svg)|
|[aurora-xeneva](https://github.com/manaskamal/aurora-xeneva)|C++|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/manaskamal/aurora-xeneva.svg)|
|[Beelzebub](https://github.com/vercas/Beelzebub)|C++|x86, x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/vercas/Beelzebub.svg)|
|[ChaiOS](https://github.com/ChaiSoft/ChaiOS)|C++|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/ChaiSoft/ChaiOS.svg)
|[Dennix](https://github.com/dennis95/dennix)|C++|x86_64|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/dennis95/dennix.svg)|
|[duckOS](https://github.com/byteduck/duckOS)|C++|-|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/byteduck/duckOS.svg)|
|[ErdOS](https://github.com/gabrielbiga/ErdOS)|C++|x86|Other|Yes|No|![](https://img.shields.io/github/license/gabrielbiga/ErdOS.svg)|
|[FoxOS](https://github.com/TheUltimateFoxOS/horizon)|C++|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/TheUltimateFoxOS/horizon.svg)
|[Ghost OS](https://github.com/maxdev1/ghost/)|C++|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/maxdev1/ghostx.svg)|
|[GreenteaOS](https://github.com/GreenteaOS)|C++|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/GreenteaOS/Tofita.svg)|
|[Haiku](https://github.com/haiku/haiku)|C++|x86, ARM|BeOS-like|Yes|Yes|![](https://img.shields.io/github/license/haiku/haiku.svg)|
|[JSD/OS](https://github.com/pgrAm/JSD-OS)|C++|x86|DOS|Yes|Yes|![](https://img.shields.io/github/license/pgrAm/JSD-OS.svg)|
|[Kot](https://github.com/kot-org/Kot)|C++|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/kot-org/Kot.svg)|
|[LemonOS](https://git[PowerNex](https://github.com/PowerNex/PowerNex)hub.com/LemonOSProject/LemonOS)|C++|-|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/LemonOSProject/LemonOS.svg)|
|[Managarm](https://github.com/managarm/managarm)|C++|-|Other|Yes|Yes|![](https://img.shields.io/github/license/managarm/managarm.svg)|
|[mikanos](https://github.com/uchan-nos/mikanos)|C++|-|Other|Yes|Yes|![](https://img.shields.io/github/license/uchan-nos/mikanos.svg)|
|[mkfreeOS](https://github.com/ramonmayedo/mkfreeOS)|C++|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/ramonmayedo/mkfreeOS.svg)|
|[NOS](https://github.com/xenos1984/NOS)|C++|x86, x86_64, ARM, ARM AArch64|Other|Yes|Yes|![](https://img.shields.io/github/license/xenos1984/NOS.svg)|
|[Perception](https://github.com/AndrewAPrice/Perception)|C++|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/AndrewAPrice/Perception.svg)|
|[Plan 42](https://github.com/mooseman/plan_42)|C++|x86|Other|Yes|No|Public Domain|
|[Quark Operating System](https://github.com/quark-os/quark-os)|C++|x86|Other|Yes|No|![](https://img.shields.io/github/license/quark-os/quark-os.svg)|
|[Reaver OS](https://github.com/griwes/ReaverOS)|C++|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/griwes/ReaverOS.svg)|
|[SerenityOS](https://github.com/SerenityOS/serenity)|C++|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/SerenityOS/serenity.svg)|
|[Silcos](https://github.com/SukantPal/Silcos-Kernel)|C++|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/SukantPal/Silcos-Kernel.svg)|
|[skiftOS](https://github.com/skiftOS/skift)|C++|-|Other|Yes|Yes|![](https://img.shields.io/github/license/skiftOS/skift.svg)|
|[Thor Operating System](https://github.com/wichtounet/thor-os)|C++|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/wichtounet/thor-os.svg)|
|[ultronOS](https://github.com/aswinmohanme/ultronOS)|C++|x86|Other|Yes|No|![](https://img.shields.io/github/license/aswinmohanme/ultronOS.svg)|
|[µnix](https://github.com/cute-engineewing/munix)|C++|Raspberry Pi Pico|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/cute-engineewing/munix.svg)|
|[Upanix](https://github.com/prajwal83/upanix)|C++|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/prajwal83/upanix.svg)|
|[WingOS](https://github.com/Supercip971/WingOS_x64/)|C++|x86_64|Other|Yes|[No](https://github.com/brutal-org/brutal)|![](https://img.shields.io/github/license/Supercip971/WingOS_x64.svg)|

</div>

- [x] [Go up](#os-projects-sorted-by-language)

### C#

<div align="center">

| Name | Language | Architecture | OS family | Available on GitHub | Active | License |
|:----:|:--------:|:------------:|:---------:|:-------------------:|:------:|:-------:|
|[Fling OS](https://github.com/FlingOS/FlingOS)|C#|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/FlingOS/FlingOS.svg)
|[Tysos](https://github.com/jncronin/tysos)|C#|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/jncronin/tysos.svg)

</div>

- [x] [Go up](#os-projects-sorted-by-language)

### Common Lisp

<div align="center">

| Name | Language | Architecture | OS family | Available on GitHub | Active | License |
|:----:|:--------:|:------------:|:---------:|:-------------------:|:------:|:-------:|
|[Mezzano](https://github.com/froggey/Mezzano)|Common Lisp|-|Other|Yes|Yes|![](https://img.shields.io/github/license/froggey/Mezzano.svg)|

</div>

- [x] [Go up](#os-projects-sorted-by-language)

### D

<div align="center">

| Name | Language | Architecture | OS family | Available on GitHub | Active | License |
|:----:|:--------:|:------------:|:---------:|:-------------------:|:------:|:-------:|
|[PowerNex](https://github.com/PowerNex/PowerNex)|D|x86_64|Other|Yes|Yes|![](https://img.shields.io/github/license/PowerNex/PowerNex.svg)|

</div>

- [x] [Go up](#os-projects-sorted-by-language)


### Pascal

<div align="center">

| Name | Language | Architecture | OS family | Available on GitHub | Active | License |
|:----:|:--------:|:------------:|:---------:|:-------------------:|:------:|:-------:|
|[Asuro](https://www.spexeah.com/index.php/asuro/)|Pascal (FreePascal)|x86|Other|No|Yes|Apache License 2.0|
|[Ultibo Core](https://github.com/ultibohub/Core)|Pascal|Raspberry Pi|Other|Yes|Yes|![](https://img.shields.io/github/license/ultibohub/Core.svg)|

</div>

- [x] [Go up](#os-projects-sorted-by-language)

### Swift

<div align="center">

| Name | Language | Architecture | OS family | Available on GitHub | Active | License |
|:----:|:--------:|:------------:|:---------:|:-------------------:|:------:|:-------:|
|[BetaOS](https://github.com/admkopec/BetaOS)|Swift, C|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/admkopec/BetaOS.svg)|

</div>

- [x] [Go up](#os-projects-sorted-by-language)

### Rust

<div align="center">

| Name | Language | Architecture | OS family | Available on GitHub | Active | License |
|:----:|:--------:|:------------:|:---------:|:-------------------:|:------:|:-------:|
|[Aura](https://github.com/projectasiago/aura)|Rust|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/projectasiago/aura.svg)|
|[eduOS-rs](https://github.com/RWTH-OS/eduOS-rs)|Rust|x86|Unix-like|Yes|Yes|![](https://img.shields.io/github/license/RWTH-OS/eduOS-rs.svg)|
|[MOROS](https://github.com/vinc/moros)|Rust|x86|Other|Yes|Yes|![](https://img.shields.io/github/license/vinc/moros.svg)|
|[Redox-OS](https://github.com/redox-os/kernel)|Rust|x86, ARM|Other|Yes|Yes|![](https://img.shields.io/github/license/redox-os/kernel.svg)|
|[snarkOS](https://github.com/AleoHQ/snarkOS)|Rust|-|Other|Yes|Yes|![](https://img.shields.io/github/license/AleoHQ/snarkOS.svg)|
|[The Stupid Operating System](https://github.com/sos-os/kernel)|Rust|-|Other|Yes|Yes|![](https://img.shields.io/github/license/sos-os/kernel.svg)|
|[Theseus](https://github.com/theseus-os/Theseus)|Rust|-|Other|Yes|Yes|![](https://img.shields.io/github/license/theseus-os/Theseus.svg)|

</div>

- [x] [Go to the next section](#tutorials)
- [x] [Go back to summary](#summary)

<hr>

## Tutorials

<div align="justify">

In this session you will find text or video tutorials for operating system development and administration. The tutorials are separated by architecture (in case of development) and target (in case of administration).

### Creating an x86 operating system

* [Kernels 101 – Let’s write a Kernel](https://arjunsreedharan.org/post/82710718100/kernels-101-lets-write-a-kernel)
* [Kernels 201 - Let’s write a Kernel with keyboard and screen support](https://arjunsreedharan.org/post/99370248137/kernels-201-lets-write-a-kernel-with-keyboard)
* [Bran's Kernel Development](http://www.osdever.net/bkerndev/Docs/title.htm)
* [Writing a Tiny x86 Bootloader](https://www.joe-bergeron.com/posts/Writing%20a%20Tiny%20x86%20Bootloader/)
* [Writing a Bootloader](http://3zanders.co.uk/2017/10/13/writing-a-bootloader/)
* [os-tutorial - How to create an OS from scratch](https://github.com/cfenollosa/os-tutorial)
* [Roll your own toy UNIX-clone OS](http://jamesmolloy.co.uk/tutorial_html/)
* [Writing an OS in Rust](https://os.phil-opp.com/)
* [Learning to write an Operating System](https://github.com/mikesmullin/OperatingSystem)

### Creating an ARM operating system

* [Baking Pi  Operating Systems Development](https://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/os/index.html)
* [Learning operating system development using Linux kernel and Raspberry Pi](https://github.com/s-matyukevich/raspberry-pi-os)
* [Build a minimal multi-tasking OS kernel for ARM from scratch](https://github.com/jserv/mini-arm-os)

### Creating an RISC-V operating system

* [Making a RISC-V Operating System using Rust](http://osblog.stephenmarz.com/)

### General OSDev

* [Operating systems development for Dummies](https://medium.com/@lduck11007/operating-systems-development-for-dummies-3d4d786e8ac)

### Linux tutorials

* [How to write a Linux kernel patch and submit it](https://github.com/gregkh/kernel-tutorial)
* [Presentation on how the Linux kernel is developed](https://github.com/gregkh/kernel-development)

### Video tutorials

* [Write your own Operating System](https://www.youtube.com/playlist?list=PLHh55M_Kq4OApWScZyPl5HhgsTJS9MZ6M)
* [Kernel dev from scratch by Dragon Zap Education](https://www.youtube.com/watch?v=HNIg3TXfdX8&list=PLrGN1Qi7t67V-9uXzj4VSQCffntfvn42v)
* [Nanobyte](https://www.youtube.com/channel/UCSPIuWADJIMIf9Erf--XAsA)

- [x] [Go to the next section](#websites-and-other-resources)
- [x] [Go back to summary](#summary)

</div>

<hr>

## Websites and other resources

<div align="justify">

In this section you will find useful websites for more material on operating system development and administration.

* [OSDev Wiki](http://wiki.osdev.org/Main_Page)
* [Images of historical operating systems](https://winworldpc.com/library/operating-systems)

- [x] [Go to the next section](#test-historical-oses-via-ssh)
- [x] [Go back to summary](#summary)

</div>

<hr>

## Test historical OSes via SSH

<div align="justify">

You can use a variety of historic operating systems kept running by the Living Computers Museum. For this, you only need to have access to the terminal (Unix systems) or command prompt (Windows) and the SSH utility, to make a remote connection.

To do this, use in the terminal:

```shell
$ ssh menu@tty.livingcomputers.org
```

You will be able to select from several systems such as UNIX (including Ancient UNIX, BSD UNIX, IRIX, HP-UX, SunOS and OSF/1), Multics, TOPS-10, TOPS-20 and OpenVMS.

- [x] [Go back to summary](#summary)

</div>
