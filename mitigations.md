---
description: This page contains links to the the security mitigations related topics.
---

# Vulnerabilities and their mitigations

The list of browser mitigations — https://docs.google.com/document/d/19dspgrz35VoJwdWOboENZvccTSGudjQ_p8J4OPsYztM/

## Stack overruns

[CWE-121: Stack-based Buffer Overflow](https://cwe.mitre.org/data/definitions/121.html)

### Userland

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://seclists.org/fulldisclosure/2012/...](http://seclists.org/fulldisclosure/2012/Jan/124) | SafeSEH+SEHOP all-at-once bypass explotation method principles | 10-01-2012 | x90c | Windows, x86-32 | N/A |
| 2 | [http://blogs.msdn.com/b/sdl/archive/2012...](http://blogs.msdn.com/b/sdl/archive/2012/01/26/enhancements-to-gs-in-visual-studio-11.aspx) | Enhancements to /GS in Visual Studio 11 | 26-01-2012 | Dave Ladd | Windows | N/A |
| 3 | [https://community.rapid7.com/community/m...](https://community.rapid7.com/community/metasploit/blog/2012/07/06/stack-smashing-when-code-execution-becomes-a-nightmare) | Stack Smashing: When Code Execution Becomes a Nightmare | 06-07-2012 | Wei Chen | Windows, x86-32 | [CVE-2012-0124](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2012-0124) |
| 4 | [https://community.rapid7.com/community/m...](https://community.rapid7.com/community/metasploit/blog/2012/08/15/the-stack-cookies-bypass-on-cve-2012-0549) | The Stack Cookies Bypass on CVE-2012-0549 | 15-08-2012 | Juan Vazquez | Windows, x86-32 | [CVE-2012-0549](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2012-0549) |

### Kernel mode

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://j00ru.vexillium.org/?p=690](http://j00ru.vexillium.org/?p=690) | Exploiting the otherwise non-exploitable: Windows Kernel-mode GS cookies subverted | 11-01-2011 | Mateusz ‘j00ru’ Jurczyk | Windows, x86-32 | <a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2010-4398" title="View CVE-2010-4398 info">CVE-2010-4398</a> |

### General

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [* http://site.pi3.com.pl/papers/ASSP.pdf *](http://site.pi3.com.pl/papers/ASSP.pdf) | Adventure with Stack Smashing Protector (SSP) | 11-11-2013 | Adam 'pi3' Zabrocki | Linux | N/A |
| 2 | [http://wiki.osdev.org/Stack_Smashing_Protec...](http://wiki.osdev.org/Stack_Smashing_Protector) | Stack Smashing Protector | 22-10-2014 | (osdev.org) | - | N/A |


## Heap overruns

[https://cwe.mitre.org/data/definitions/122.html](https://cwe.mitre.org/data/definitions/122.html)

### Userland

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://www.symantec.com/connect/articles...](http://www.symantec.com/connect/articles/new-way-bypass-windows-heap-protections) | A new way to bypass Windows heap protections | 31-08-2005 | Nicolas Falliere | Windows XP SP2, x86-32 | N/A |
| 2 | [http://blogs.technet.com/b/srd/archive/2...](http://blogs.technet.com/b/srd/archive/2009/08/04/preventing-the-exploitation-of-user-mode-heap-corruption-vulnerabilities.aspx) | Preventing the exploitation of user mode heap corruption vulnerabilities | 04-08-2009 | swiat | Windows | N/A |
| 3 | [http://blogs.technet.com/b/srd/archive/2...](http://blogs.technet.com/b/srd/archive/2013/10/29/software-defense-mitigation-heap-corruption-vulnerabilities.aspx) | Software Defense: mitigating heap corruption vulnerabilities | 29-10-2013 | swiat | Windows | N/A |
| 4 | [http://blog.lse.epita.fr/articles/74-get...](http://blog.lse.epita.fr/articles/74-getting-back-determinism-in-the-lfh.html) | Getting back determinism in the Low Fragmentation Heap | 02-11-2014 | Bruno Pujos | Windows 8 | N/A |

### Kernel mode

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://blogs.technet.com/b/srd/archive/2...](http://blogs.technet.com/b/srd/archive/2009/05/26/safe-unlinking-in-the-kernel-pool.aspx) | Safe Unlinking in the Kernel Pool | 26-05-2012 | swiat | Windows | N/A |
| 2 | [http://www.inertiawar.com/unlink/](http://www.inertiawar.com/unlink/) | Windows 8 and Safe Unlinking in NTDLL | 14-07-2012 | Note | Windows | N/A |


## Static buffer overflows

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://em386.blogspot.com/2008/05/self-p...](http://em386.blogspot.com/2008/05/self-protecting-got.html) | Self Protecting Global Offset Table (GOT) | 24-04-2008 | Chris Rohlf | - | N/A |
| 2 | [http://isisblogs.poly.edu/2011/06/01/rel...](https://web.archive.org/web/20150919130142/https://isisblogs.poly.edu/2011/06/01/relro-relocation-read-only/) | RELRO: RELocation Read-Only | 01-06-2011 | Julian Cohen | Linux | N/A |


## Uninitialized data

[https://cwe.mitre.org/data/definitions/824.html](https://cwe.mitre.org/data/definitions/824.html)

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://blogs.msdn.com/b/sdl/archive/2012...](http://blogs.msdn.com/b/sdl/archive/2012/03/08/guarding-against-uninitialized-class-member-pointers.aspx) | Guarding against uninitialized class member pointers | 08-03-2012 | Thomas Garnier | Windows | N/A |


## Lifetime issues

[https://cwe.mitre.org/data/definitions/416.html](https://cwe.mitre.org/data/definitions/416.html)
[https://cwe.mitre.org/data/definitions/415.html](https://cwe.mitre.org/data/definitions/415.html)

Use-after-free, double-free bugs.

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://blog.fortinet.com/post/is-use-aft...](http://blog.fortinet.com/post/is-use-after-free-exploitation-dead-the-new-ie-memory-protector-will-tell-you) | Is use-after-free exploitation dead? The new IE memory protector will tell you | 16-06-2014 | Zhenhua 'Eric' Liu  | Windows | N/A |
| 2 | [http://researchcenter.paloaltonetworks.c...](https://web.archive.org/web/20150913040438/http://researchcenter.paloaltonetworks.com/2014/07/beginning-end-use-free-exploitation/) | Is It the Beginning of the End For Use-After-Free Exploitation? | 16-06-2014 | Tao Yan, Bo Qu, Royce Lu  | Windows | N/A |
| 3 | [http://blog.trendmicro.com/trendlabs-sec...](http://blog.trendmicro.com/trendlabs-security-intelligence/mitigating-uaf-exploits-with-delay-free-for-internet-explorer/) | Mitigating UAF Exploits with Delay Free for Internet Explorer | 17-06-2014 | Jack Tang | Windows | N/A |
| 4 | [https://labs.mwrinfosecurity.com/blog/20...](https://web.archive.org/web/20160329134900/https://labs.mwrinfosecurity.com/blog/isolated-heap-friends-object-allocation-hardening-in-web-browsers/) | Isolated Heap & Friends - Object Allocation Hardening in Web Browsers | 20-06-2014 | mwrinfosecurity.com | - | N/A |
| 5 | [http://blog.trendmicro.com/trendlabs-sec...](http://blog.trendmicro.com/trendlabs-security-intelligence/isolated-heap-for-internet-explorer-helps-mitigate-uaf-exploits/) | Isolated Heap for Internet Explorer Helps Mitigate UAF Exploits | 01-07-2014 | Jack Tang | Windows | N/A |
| 6 | [http://h30499.www3.hp.com/t5/HP-Security...](http://h30499.www3.hp.com/t5/HP-Security-Research-Blog/Efficacy-of-MemoryProtection-against-use-after-free/ba-p/6556134) | Efficacy of MemoryProtection against use-after-free vulnerabilities | 28-07-2014 | Simon Zuckerbraun | Windows | N/A |
| 7 | [http://securityintelligence.com/understa...](http://securityintelligence.com/understanding-ies-new-exploit-mitigations-the-memory-protector-and-the-isolated-heap/#.VGoE8ZPoGu7) | Understanding IE’s New Exploit Mitigations: The Memory Protector and the Isolated Heap | 29-08-2014 | Mark Yason | Windows | N/A |
| 8 | [https://web.archive.org/web/201411020020...](https://web.archive.org/web/20141102002013/http://k33nteam.org/blog-4-use-after-free-not-dead-in-internet-explorer-part-1.htm) | USE-AFTER-FREE NOT DEAD IN INTERNET EXPLORER: PART 1 | 13-10-2014 | k33nteam | Windows 8.1 | MS14-056 |
| 9 | [* http://h30499.www3.hp.com/hpeb/attachmen... *](http://h30499.www3.hp.com/hpeb/attachments/hpeb/off-by-on-software-security-blog/444/2/SecurityBriefing_Episode18_UAFs_20141030-FINAL.pdf) | New directions in use-after-free mitigations | 18-10-2014 | HP Security | Windows | N/A |
| 10 | [http://blog.trendmicro.com/trendlabs-sec...](http://blog.trendmicro.com/trendlabs-security-intelligence/windows-10-sharpens-browser-security-with-microsoft-edge/) | Windows 10 Sharpens Browser Security With Microsoft Edge | 21-07-2015 | Henry li | Windows | N/A |
| 11 | [http://blogs.360.cn/360safe/2016/06/17/a...](http://blogs.360.cn/360safe/2016/06/17/a-quick-look-at-the-flash-memory-protector/) | A Quick Look at the Flash Memory Protector | 17-06-2016 | yukichen | - | N/A |


## NULL-pointer

[https://cwe.mitre.org/data/definitions/476.html](https://cwe.mitre.org/data/definitions/476.html)

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [* https://web.archive.org/web/201209131910... *](https://web.archive.org/web/20120913191024/http://www.mista.nu/research/nullpage.pdf) | Locking Down the Windows Kernel:Mitigating Null Pointer Exploitation | 07-07-2011 | Tarjei (kernelpool) Mandt | Windows | N/A |


## Integer bugs

[https://cwe.mitre.org/data/definitions/189.html](https://cwe.mitre.org/data/definitions/189.html)

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://forums.grsecurity.net/viewtopic.p...](http://forums.grsecurity.net/viewtopic.php?f=7&t=3043) | Inside the Size Overflow Plugin | 28-08-2012 | ephox | - | N/A |


# Exploitation techniques and their mitigations

## Return Oriented Exploitation

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [https://grsecurity.net/rap_faq.php](https://grsecurity.net/rap_faq.php) | Frequently Asked Questions About RAP | xx-xx-2016 | ? | Linux | N/A |



# Hardenings and their bypasses


## Address Space Layout Randomization (ASLR)

### Userland

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [https://web.archive.org/web/201001020008...](https://web.archive.org/web/20100102000802/http://sophsec.com/research/aslr_research.html) | Attacking ASLR on Linux 2.6 | 27-05-2009 | drraid | Linux | N/A |
| 2 | [http://recxltd.blogspot.com/2011/12/curi...](http://recxltd.blogspot.com/2011/12/curious-case-of-virtualalloc-aslr-and.html) | The Curious Case of VirtualAlloc, ASLR and an SDL | 13-12-2011 | Ollie | Windows |  N/A |
| 3 | [http://blog.duosecurity.com/2012/02/a-lo...](https://web.archive.org/web/20160124225654/https://duo.com/blog/a-look-at-aslr-in-android-ice-cream-sandwich-4-0) | A look at ASLR in Android Ice Cream Sandwich 4.0 | 17-02-2012 | Jon Oberheide | Android |  N/A |
| 4 | [http://recxltd.blogspot.com/2012/03/part...](http://recxltd.blogspot.com/2012/03/partial-technique-against-aslr-multiple.html) | A Partial Technique Against ASLR - Multiple O/Ss | 02-03-2012 | Ollie | Windows, x86-32 | N/A |
| 5 | [http://blog.ptsecurity.com/2012/12/windo...](http://blog.ptsecurity.com/2012/12/windows-8-aslr-internals.html) | Windows 8 ASLR Internals | 04-12-2012 | Artem Shishkin, Ilya Smith | Windows 8 | N/A |
| 6 | [http://kingcope.wordpress.com/2013/01/24...](http://kingcope.wordpress.com/2013/01/24/attacking-the-windows-78-address-space-randomization/) | Attacking the Windows 7/8 Address Space Randomization | 24-01-2013 | kingcope | Windows 7/8 | N/A |
| 7 | [http://www.fireeye.com/blog/technical/cy...](https://web.archive.org/web/20141111153309/http://www.fireeye.com/blog/technical/cyber-exploits/2013/10/aslr-bypass-apocalypse-in-lately-zero-day-exploits.html) | ASLR Bypass Apocalypse in Recent Zero-Day Exploits | 15-10-2013 | Xiabo Chen | Windows | <a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2013-0640" title="View CVE-2013-0640 info">CVE-2013-0640</a>, <a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2013-0634" title="View CVE-2013-0634 info">CVE-2013-0634</a>, <a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2013-3163" title="View CVE-2013-3163 info">CVE-2013-3163</a>, <a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2013-1690" title="View CVE-2013-1690 info">CVE-2013-1690</a>, <a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2013-1493" title="View CVE-2013-1493 info">CVE-2013-1493</a> |
| 8 | [https://www.cert.org/blogs/certcc/post.c...](https://www.cert.org/blogs/certcc/post.cfm?EntryID=191) | Differences Between ASLR on Windows and Linux | 10-02-2014 | Will Dormann | Windows | N/A |
| 9 | [http://ly0n.me/2015/07/30/bypass-aslr-wi...](http://ly0n.me/2015/07/30/bypass-aslr-with-partial-eip-overwrite/) | Bypass ASLR with partial EIP overwrite | 30-06-2015 | ly0n | Windows | [CVE-2007-0038](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-0038) |
| 10 | [http://www.greyhathacker.net/?p=894](http://www.greyhathacker.net/?p=894) | Bypassing Windows ASLR in Microsoft Office using ActiveX controls | 04-12-2015 | Parvez | Windows | N/A |
| 11 | [https://www.vusec.net/projects/anc/](https://www.vusec.net/projects/anc/), [* http://www.cs.vu.nl/~herbertb/download/p... *](http://www.cs.vu.nl/~herbertb/download/papers/anc_ndss17.pdf) | The AnC attack | xx-xx-2017 | VUSec | - | N/A |


### Kernel mode (KASLR)

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [* https://dl.packetstormsecurity.net/pap... *](https://dl.packetstormsecurity.net/papers/bypass/NES-BypassWin7KernelAslr.pdf) | Bypassing Windows 7 Kernel ASLR | 11-10-2011 | Stefan Le Berre | Windows, x86-32 | N/A |
| 2 | [http://shell-storm.org/blog/ASLR-impleme...](http://shell-storm.org/blog/ASLR-implementation-in-Linux-Kernel-3.7) | ASLR implementation in Linux Kernel 3.7 | 19-01-2013 | Jonathan Salwan | Linux |  N/A |
| 3 | [http://forums.grsecurity.net/viewtopic.p...](http://forums.grsecurity.net/viewtopic.php?f=7&t=3367) | KASLR: An Exercise in Cargo Cult Security | 20-03-2013 | spender | - |  N/A |
| 4 | [http://www.alex-ionescu.com/?p=82](http://www.alex-ionescu.com/?p=82) | KASLR Bypass Mitigations in Windows 8.1 | 17-11-2013 | Alex Ionescu | Windows 8.1 | N/A |
| 5 | [http://labs.bromium.com/2014/10/27/tsx-i...](http://labs.bromium.com/2014/10/27/tsx-improves-timing-attacks-against-kaslr/) | TSX improves timing attacks against KASLR | 27-10-2014 | Rafal Wojtzcuk | N/A | N/A |
| 6 | [https://copperhead.co/2015/05/11/aslr-an...](https://copperhead.co/2015/05/11/aslr-android-zygote) | The State of ASLR on Android Lollipop | 11-05-2015 | Daniel Micay | Android 5.0.1 | N/A |
| 7 | [https://marcograss.github.io/security/li...](https://marcograss.github.io/security/linux/2016/01/24/exploiting-infoleak-linux-kaslr-bypass.html) | Exploiting a Linux Kernel Infoleak to bypass Linux kASLR | 24-01-2016 | Marco Grass | Linux | N/A |
| 8 | [http://dreamsofastone.blogspot.de/2016/...](http://dreamsofastone.blogspot.de/2016/02/breaking-kasrl-with-micro-architecture.html) | Breaking KASRL with micro architecture Part 1 | 20-02-2016 | Anders Fogh | - | N/A |

### General

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [* https://www.blackhat.com/docs/eu-15/mate *](https://www.blackhat.com/docs/eu-15/materials/eu-15-Barresi-Silently-Breaking-ASLR-In-The-Cloud-wp.pdf) | Silently Breaking ASLR In The Cloud | 11-11-2015 | Antonio Barresi, Kaveh Razavi, Mathias Payer, Thomas R. Gross | VM |


## Data Execution Prevention (DEP)

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [* https://docs.google.com/viewer?a=v&pid=e... *](https://docs.google.com/viewer?a=v&pid=explorer&chrome=true&srcid=0B64ViR5GhSKINDcxZGM1YTItM2U0Ni00ZGZlLWFhNDgtZmY4YjE2Y2I1Y2Rk&hl=en) | x86-64 buffer overflow exploits and the borrowed code chunks | 28-09-2005 | Sebastian Krahmer | Linux x86-64 | N/A |
| 2 | [http://www.uninformed.org/?v=2&a=4](http://www.uninformed.org/?v=2&a=4) | Bypassing Windows Hardware-enforced Data Execution Prevention | 02-10-2005 | Matt (skape) Miller | Windows, x86-32 | <a href="http://osvdb.org/show/osvdb/875" title="View OSVDB-875 info">OSVDB-875</a> |
| 3 | [http://cseweb.ucsd.edu/~hovav/papers/s07...](http://cseweb.ucsd.edu/~hovav/papers/s07.html) | The Geometry of Innocent Flesh on the Bone: Return-into-libc without Function Calls (on the x86) | xx-10-2007 | Hovav Shacham | x86 | N/A |
| 4 | [* http://www.packetstormsecurity.org/paper... *](http://www.packetstormsecurity.org/papers/bypass/bypass-dep.pdf) | Bypassing hardware based DEP on Windows Server 2003 SP2 | 10-06-2009 | David Kennedy | Windows, x86-32 | N/A |
| 5 | [http://bernardodamele.blogspot.com/2009/...](http://bernardodamele.blogspot.com/2009/12/dep-bypass-with-setprocessdeppolicy.html) | DEP bypass with SetProcessDEPPolicy() | 09-12-2009 | Bernardo Damele | Windows, x86-32 | N/A |
| 6 | [http://vrt-blog.snort.org/2009/12/dep-an...](https://web.archive.org/web/20150420232159/http://vrt-blog.snort.org/2009/12/dep-and-heap-sprays.html) | DEP and Heap Sprays | 17-12-2009 | Lurene Grenier | Windows | N/A |
| 7 | [http://blog.zynamics.com/2010/03/12/a-ge...](http://blog.zynamics.com/2010/03/12/a-gentle-introduction-to-return-oriented-programming/) | A gentle introduction to return-oriented programming | 12-03-2010 | Tim Kornau | x86 | N/A |
| 8 | [http://archives.neohapsis.com/archives/f...](http://archives.neohapsis.com/archives/fulldisclosure/2010-03/att-0553/Windows-DEP-WPM.txt) | Exploitation With WriteProcessMemory()/Yet Another DEP Trick | xx-03-2010 | Spencer Pratt | Windows | N/A |
| 9 | [http://blog.harmonysecurity.com/2010/04/...](http://blog.harmonysecurity.com/2010/04/little-return-oriented-exploitation-on.html) | A little return oriented exploitation on Windows x86 (Part 1) | 12-04-2010 | Stephen Fewer | Windows, x86-32 | <a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2010-0838" title="View CVE-2010-0838 info">CVE-2010-0838</a> |
| 10 | [http://blog.harmonysecurity.com/2010/04/...](http://blog.harmonysecurity.com/2010/04/little-return-oriented-exploitation-on_16.html) | A little return oriented exploitation on Windows x86 (Part 2) | 16-04-2010 | Stephen Fewer | Windows, x86-32 | N/A |
| 11 | [https://web.archive.org/web/201207070114...](https://web.archive.org/web/20120707011407/http://divine-protection.com/wordpress/?p=20) | Advanced Return-Oriented Exploit | 05-05-2010 | funkyG | Linux, x86-32 | N/A |
| 12 | [http://www.corelan.be:8800/index.php/201...](https://web.archive.org/web/20150425134217/https://www.corelan.be/index.php/2010/06/16/exploit-writing-tutorial-part-10-chaining-dep-with-rop-the-rubikstm-cube/) | Exploit writing tutorial part 10 : Chaining DEP with ROP – the Rubik’s[TM] Cube | 16-06-2010 | corelanc0d3r | Windows, x86-32 | N/A |
| 13 | [http://eticanicomana.blogspot.com/2010/0...](http://eticanicomana.blogspot.com/2010/06/so-called-return-oriented-programming.html) | The so called Return Oriented Programming... | 21-06-2010 | Nicolas Waisman | Windows, x86-32 | N/A |
| 14 | [http://www.exploit-db.com/osx-rop-exploi...](http://www.exploit-db.com/osx-rop-exploits-evocam-case-study/) | OSX ROP Exploit – EvoCam Case Study | 06-07-2010 | muts | Mac | <a href="http://osvdb.org/65043" title="View OSVDB-65043 info">OSVDB-65043</a> |
| 15 | [* http://repository.root-me.org/Exploit... *](http://repository.root-me.org/Exploitation%20-%20Syst%C3%A8me/Unix/EN%20-%20Paper%20Payload%20already%20inside%20data%20reuse%20for%20ROP%20exploits.pdf) | Payload already inside: data reuse for rop exploits | 28-07-2010 | longld | Linux x86 | N/A |
| 16 | [http://www.vnsecurity.net/research/2010/...](http://www.vnsecurity.net/research/2010/10/05/simple-mac-os-x-ret2libc-exploit-x86.html) | Simple Mac ret2libc exploit (x86) | 05-10-2010 | longld | Mac, x86-32 | N/A |
| 17 | [http://vulnfactory.org/blog/2011/09/21/d...](http://vulnfactory.org/blog/2011/09/21/defeating-windows-8-rop-mitigation/) | Defeating Windows 8 ROP Mitigation | 21-09-2011 | Dan Rosenberg | Windows 8 | N/A |
| 18 | [http://www.exploit-monday.com/2011/11/ma...](http://www.exploit-monday.com/2011/11/man-vs-rop-overcoming-adversity-one.html) | Man vs. ROP - Overcoming Adversity One Gadget at a Time | 14-11-2011 | Matt Graeber | Windows, x86-32 | N/A |
| 19 | [https://web.archive.org/web/201201200400...](https://web.archive.org/web/20120120040042/http://blog.bkis.com/en/advanced-generic-rop-chain-for-windows-8/) | Advanced Generic ROP chain for Windows 8 | 16-11-2011 | Le Manh Tung | Windows 8 | <a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-0065" title="View CVE-2011-0065 info">CVE-2011-0065</a> |
| 20 | [http://www.accuvant.com/blog/2011/12/01/...](https://web.archive.org/web/20160312084000/http://www.accuvant.com/blog/measure-twice-cut-once) | Measure Twice, Cut Once | 01-12-2011 | Accuvant LABS R&D Team | Windows | N/A |
| 21 | [http://codearcana.com/posts/2013/05/28/i...](http://codearcana.com/posts/2013/05/28/introduction-to-return-oriented-programming-rop.html) | Introduction to return oriented programming (ROP) | 28-05-2013 | Alex Reece | Linux | N/A |
| 22 | [https://codeinsecurity.wordpress.com/201...](https://codeinsecurity.wordpress.com/2015/09/03/wx-policy-violation-affecting-all-windows-drivers-compiled-in-visual-studio-2013-and-previous/) | W^X policy violation affecting all Windows drivers compiled in Visual Studio 2013 and previous | 03-09-2015 | Graham Sutherland | Windows | N/A |
| 23 | [https://jandemooij.nl/blog/2015/12/29/wx...](https://jandemooij.nl/blog/2015/12/29/wx-jit-code-enabled-in-firefox/) | W^X JIT-code enabled in Firefox | 29-12-2015 | jandem | - | N/A |
| 24 | [https://rh0dev.github.io/blog/2017/the-r...](https://rh0dev.github.io/blog/2017/the-return-of-the-jit/) | The Return of the JIT (Part 1) | 13-07-2017 | Rh0 | - | [CVE-2017-5375](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-5375), [CVE-2017-5400](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-5400) |
| 24 | [https://rh0dev.github.io/blog/2017/the-r...](https://rh0dev.github.io/blog/2017/the-return-of-the-jit-part-2/) | The Return of the JIT (Part 2) | 17-07-2017 | Rh0 | - | [CVE-2017-5375](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-5375), [CVE-2017-5400](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-5400) |


## Return-Oriented-Programming (ROP) mitigations

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [* http://www.kryptoslogic.com/download/ROP... *](http://www.kryptoslogic.com/download/ROP_Whitepaper.pdf) | Security Mitigations for Return-Oriented Programming Attacks | 20-08-2010 | Piotr Bania | Windows | N/A |
| 2 | [http://c0decstuff.blogspot.com.es/2012/1...](http://c0decstuff.blogspot.com.es/2012/12/defeating-windows-8-rop-mitigation.html) | Defeating Windows 8 ROP Mitigation | 19-12-2012 | c0decstuff | Windows 8 | N/A |
| 3 | [http://blog.talosintelligence.com/2016/0...](http://blog.talosintelligence.com/2016/06/ropmemu.html) | Research Spotlight: ROPMEMU - A Framework for the Analysis of Complex Code-Reuse Attacks | 01-06-2016 | Mariano Graziano | - | N/A |


## Export Address Table Access Filtering (EAF)

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://www.greyhathacker.net/?p=483](http://www.greyhathacker.net/?p=483) | Bypassing EMET’s EAF with custom shellcode using kernel pointer | 19-12-2011 | Parvez | Windows, x86-32 | <a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2010-3654" title="View CVE-2010-3654 info">CVE-2010-3654</a> |
| 2 | [http://piotrbania.com/all/articles/anti_...](http://piotrbania.com/all/articles/anti_emet_eaf.txt) | BYPASSING EMET Export Address Table Access Filtering feature | 19-01-2012 | Piotr Bania | Windows, x86-32 | N/A |
| 3 | [http://scrammed.blogspot.de/2014/03/reve...](http://scrammed.blogspot.de/2014/03/reversing-emets-eaf-and-couple-of.html) | Reversing EMET's EAF (and a couple of curious findings...) | 20-03-2014 | giulia | Windows | N/A |
| 4 | [http://tekwizz123.blogspot.de/2015/01/by...](http://tekwizz123.blogspot.de/2015/01/bypassing-emets-eaf-protection-slightly.html) | An Theoretical Approach to Getting Around EMET's EAF Protection | 18-01-2015 | tekwizz | Windows | N/A |



## Control Flow Integrity / Control Flow Guard

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://blogs.msdn.com/b/vcblog/archive/2...](http://blogs.msdn.com/b/vcblog/archive/2014/12/08/visual-studio-2015-preview-work-in-progress-security-feature.aspx) | Visual Studio 2015 Preview: Work-in-Progress Security Feature | 08-12-2014 | Jim Hogg | Windows | N/A |
| 2 | [http://blog.trendmicro.com/trendlabs-sec...](http://blog.trendmicro.com/trendlabs-security-intelligence/exploring-control-flow-guard-in-windows-10) | Exploring Control Flow Guard in Windows 10 | 30-01-2015 | Jack Tang | Windows 10 | N/A |
| 3 | [https://blog.coresecurity.com/2015/03/25/...](https://blog.coresecurity.com/2015/03/25/exploiting-cve-2015-0311-part-ii-bypassing-control-flow-guard-on-windows-8-1-update-3/) | Exploiting CVE-2015-0311, Part II: Bypassing Control Flow Guard on Windows 8.1 Update 3 | 25-03-2015 | Francisco Falcón | Windows 8.1 | http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2015-0311 |
| 4 | [* http://sjc1-te-ftp.trendmicro.com/assets/wp... *](http://sjc1-te-ftp.trendmicro.com/assets/wp/exploring-control-flow-guard-in-windows10.pdf) | Exploring Control Flow Guard in Windows 10 | xx-05-2015 | Jack Tang | Windows | N/A |
| 5 | [* http://research.microsoft.com/pubs/64250/cc... *](http://research.microsoft.com/pubs/64250/ccs05.pdf) | Control-Flow Integrity: Principles, Implementations, and Applications | 11-07-2015 | Martın Abadi, Mihai Budiu, Ulfar Erlingsson, Jay Ligatti | - | N/A |
| 6 | [http://labs.bromium.com/2015/09/28/an-int...](http://labs.bromium.com/2015/09/28/an-interesting-detail-about-control-flow-guard/) | An interesting detail about Control Flow Guard | 28-09-2015 | Rafal Wojtczuk | Windows | N/A |
| 7 | [http://xlab.tencent.com/en/2016/01/04/use...](http://xlab.tencent.com/en/2016/01/04/use-chakra-engine-again-to-bypass-cfg/) | Use Chakra engine again to bypass CFG | 04-01-2016 | exp-sky | Windows | N/A |
| 8 | [https://securingtomorrow.mcafee.com/mcafe...](https://securingtomorrow.mcafee.com/mcafee-labs/microsofts-june-patch-kills-potential-cfg-bypass/) | Microsoft’s June Patch Kills Potential CFG Bypass | 16-06-2016 | Bing Sun | Windows | N/A |
| 9 | [https://blog.trailofbits.com/2016/10/17/l...](https://blog.trailofbits.com/2016/10/17/lets-talk-about-cfi-clang-edition/) | Let’s talk about CFI: clang edition | 17-10-2016 | Artem Dinaburg | - | N/A |
| 10 | [http://theori.io/research/chakra-jit-cfg-...](http://theori.io/research/chakra-jit-cfg-bypass) | CHAKRA JIT CFG BYPASS | 14-12-2016 | Theori | Windows | MS16-119 |
| 11 | [https://improsec.com/blog//bypassing-cont...](https://improsec.com/blog//bypassing-control-flow-guard-in-windows-10) | Bypassing Control Flow Guard in Windows 10 | 16-01-2017 | Morten Schenk | Windows | N/A |
| 12 | [https://improsec.com/blog//bypassing-cont...](https://improsec.com/blog//bypassing-control-flow-guard-on-windows-10-part-ii) | Bypassing Control Flow Guard in Windows 10 - Part II | 23-01-2017 | Morten Schenk | Windows | N/A |
| 13 | [https://forums.grsecurity.net/viewtopic.p...](https://forums.grsecurity.net/viewtopic.php?f=7&t=4490) | Close, but No Cigar: On the Effectiveness of Intel's CET Against Code Reuse Attacks | 12-06-2017 | PaX Team | - | N/A |


## Mitigations Against Use-After-Free

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [* http://h30499.www3.hp.com/hpeb/attachments/... *](http://h30499.www3.hp.com/hpeb/attachments/hpeb/off-by-on-software-security-blog/599/1/WP-Hariri-Zuckerbraun-Gorenc-Abusing_Silent_Mitigations.pdf) | Abusing Silent Mitigations: Understanding weaknesses within Internet Explorer’s Isolated Heap and MemoryProtection | 19-06-2015 | Abdul-Aziz Hariri, Simon Zuckerbraun, Brian Gorenc | Windows | N/A |
| 2 | [http://googleprojectzero.blogspot.de/2015/0...](http://googleprojectzero.blogspot.de/2015/06/dude-wheres-my-heap.html) | Dude, where’s my heap? | 15-06-2015 | Ivan Fratric | Windows | N/A |


## Arbitrary Code Guard

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [https://bugs.chromium.org/p/project-zero...](https://bugs.chromium.org/p/project-zero/issues/detail?id=1299) | Microsoft Edge: ACG bypass using DuplicateHandle | 16-06-2017 | Ivan Fratric | Windows | N/A |


## Return Flow Guard

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://xlab.tencent.com/en/2016/11/02/re...](http://xlab.tencent.com/en/2016/11/02/return-flow-guard/) | Return Flow Guard | 02-11-2016 | TenCent | Windows | N/A |
| 2 | [https://forums.grsecurity.net/viewtopic....](https://forums.grsecurity.net/viewtopic.php?f=7&t=4490) | Close, but No Cigar: On the Effectiveness of Intel's CET Against Code Reuse Attacks | 12-06-2016 | PaX Team | - | N/A |

## Information Leak Mitigations

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [https://copperhead.co/blog/2016/09/20/me...](https://copperhead.co/blog/2016/09/20/memory-disclosure-mitigations) | Memory disclosure mitigations in CopperheadOS | 20-09-2016 | Daniel Micay | CopperheadOS | N/A |



## Multiple mitigations discussed

### Userland

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [* http://www.azimuthsecurity.com/resources/... *](https://web.archive.org/web/20150513002428/https://www.trailofbits.com/resources/bypassing_browser_memory_protections_vista_paper.pdf) | Bypassing Browser Memory Protections | 07-08-2008 | Alex Sotirov, Mark Dowd | Windows, x86-32 | N/A |
| 2 | [* https://www.blackhat.com/presentations/b... *](https://www.blackhat.com/presentations/bh-europe-09/Fritsch/Blackhat-Europe-2009-Fritsch-Buffer-Overflows-Linux-whitepaper.pdf) | Buffer overflows on linux-x86-64 | 22-01-2009 | Hagen Fritsch | Linux, x86-64 | N/A |
| 3 | [http://www.corelan.be/index.php/200...](http://www.corelan.be/index.php/2009/09/21/exploit-writing-tutorial-part-6-bypassing-stack-cookies-safeseh-hw-dep-and-aslr/) | Exploit writing tutorial part 6 : Bypassing Stack Cookies, SafeSeh, SEHOP, HW DEP and ASLR | 12-09-2009 | corelanc0d3r | Windows, x86-32 | [CVE-2006-6199](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2006-6199) |
| 4 | [* https://docs.google.com/viewer?a=v&pid=e... *](https://docs.google.com/viewer?a=v&pid=explorer&chrome=true&srcid=1g5FD5gjWAIu0iGf7gaF-DBfgya-u9kYX2KT9EgAdbpyjVzXI90imHI783LIF&hl=en) | Bypassing ASLR and DEP under Windows | 17-06-2010 | mr_me | Windows, x86-32 | N/A |
| 5 | [https://labs.mwrinfosecurity.com/blog/2010...](https://web.archive.org/web/20160329140906/https://labs.mwrinfosecurity.com/blog/assessing-the-tux-strength-part-1-userspace-memory-protection/) | Assessing the Tux Strength: Part 1 - Userspace Memory Protection | 29-07-2010 | ? | Linux | N/A |
| 6 | [http://blogs.technet.com/b/srd/archive/2...](http://blogs.technet.com/b/srd/archive/2010/12/08/on-the-effectiveness-of-dep-and-aslr.aspx) | On the effectiveness of DEP and ASLR | 08-12-2010 | swiat | Windows | N/A |
| 7 | [http://msdn.microsoft.com/en-us/library/...](http://msdn.microsoft.com/en-us/library/bb430720.aspx) | Windows ISV Software Security Defenses | xx-12-2010 | Michael Howard, Matt Miller, John Lambert, Matt Thomlinson | Windows | N/A |
| 8 | [* http://www.secfence.com/whitepapers/Whit... *](http://www.secfence.com/whitepapers/Whitepaper-on-ASLR-DEP-Bypass-Secfence-Technologies.pdf) | Bypassing ASLR/DEP | 25-09-2011 | Vinay Katoch | Windows, x86-32 | <a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-0065" title="View CVE-2011-0065 info">CVE-2011-0065</a> |
| 9 | [http://www.microsoft.com/download/en/det...](https://web.archive.org/web/20120414062748/http://download.microsoft.com/download/5/0/5/505646ED-5EDF-4E23-8E84-6119E4BF82E0/Mitigating_Software_Vulnerabilities.pdf) | Mitigating Software Vulnerabilities | 12-07-2011 | Matt Miller, Time Burrell, Michael Howard | Windows | N/A |
| 10 | [http://forums.grsecurity.net/viewtopic.p...](http://forums.grsecurity.net/viewtopic.php?t=2939&p=11669) | Recent Advances: How We Learn From Exploits | 15-02-2012 | spender | Linux | N/A |
| 11 | [http://blogs.msdn.com/b/ie/archive/2012/...](http://blogs.msdn.com/b/ie/archive/2012/03/12/enhanced-memory-protections-in-ie10.aspx) | Enhanced Memory Protections in IE10 | 13-03-2012 | Forbes Higman | Windows | N/A |
| 12 | [http://esec-lab.sogeti.com/post/Bypassin...](http://esec-lab.sogeti.com/post/Bypassing-ASLR-and-DEP-on-Adobe-Reader-X) | Bypassing ASLR and DEP on Adobe Reader X | 22-06-2012 | guillaume | Windows, x86-32 | N/A |
| 13 | [http://security.stackexchange.com/questi...](http://security.stackexchange.com/questions/18556/how-do-aslr-and-dep-work) | How do ASLR and DEP work? | 12-08-2012 | polynomial | - | N/A |
| 14 | [http://blogs.technet.com/b/srd/archive/2...](http://blogs.technet.com/b/srd/archive/2013/11/06/software-defense-safe-unlinking-and-reference-count-hardening.aspx) | Software defense: safe unlinking and reference count hardening | 06-11-2013 | swiat | Windows | N/A |
| 15 | [* http://bromiumlabs.files.wordpress.com/2... *](http://bromiumlabs.files.wordpress.com/2014/02/bypassing-emet-4-1.pdf) | BYPASSING EMET 4.1 | xx-02-2014 | Jares DeMott | Windows | N/A |
| 16 | [http://www.contextis.com/resources/blog/...](http://www.contextis.com/resources/blog/windows-mitigaton-bypass/) | Bypassing Windows 8.1 Mitigations using Unsafe COM Objects | 15-06-2014 | James Forshaw | Windows 8.1 | N/A |
| 17 | [http://www.offensive-security.com/vulnde...](http://www.offensive-security.com/vulndev/disarming-enhanced-mitigation-experience-toolkit-emet/) | Disarming Enhanced Mitigation Experience Toolkit | 01-07-2014 | offensive-security.com | Windows | N/A |
| 18 | [https://www.offensive-security.com/vulnd...](https://www.offensive-security.com/vulndev/disarming-emet-v5-0/) | Disarming EMET v5.0 | 29-09-2014 | offensive-security.com | Windows | <a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2012-1876" title="View CVE-2012-1876 info">CVE-2012-1876</a> |
| 19 | [https://www.offensive-security.com/vulnd...](https://www.offensive-security.com/vulndev/disarming-and-bypassing-emet-5-1/) | Disarming and Bypassing EMET 5.1 | 18-11-2014 | Blogpost | offensive-security.com | N/A |
| 20 | [http://casual-scrutiny.blogspot.in/2015/...](http://casual-scrutiny.blogspot.in/2015/03/defeating-emet-52.html) | Defeating EMET 5.2 Protections | 15-03-2015 | r41p41 | Windows | N/A |
| 21 | [http://casual-scrutiny.blogspot.in/2015/...](http://casual-scrutiny.blogspot.in/2015/03/defeating-emet-52-protections-2.html) | Defeating EMET 5.2 Protections (2) | 21-03-2015 | r41p41 | Windows | N/A |
| 22 | [http://int3pids.blogspot.de/2015/04/conf...](http://int3pids.blogspot.de/2015/04/confidence-2015-teaser-quarantine-write.html) | Confidence 2015 Teaser: Quarantine Write-Up (pwn 500) | 30-04-2015 | Eloi Sanfelix | Linux | N/A |
| 23 | [http://googleprojectzero.blogspot.com/20...](http://googleprojectzero.blogspot.com/2015/07/significant-flash-exploit-mitigations_16.html) | Significant Flash exploit mitigations are live in v18.0.0.209 | 16-07-2015 | Mark Brand, Chris Evans | - | N/A |
| 24 | [https://www.endgame.com/blog/adobe-flash...](https://www.endgame.com/blog/adobe-flash-vulnerability-cve-2015-7663-and-mitigating-exploits) | Adobe Flash Vulnerability CVE-2015-7663 and Mitigating Exploits | xx-xx-2015 | Cody Pierce | - | [CVE-2015-7663](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2015-7663) |
| 25 | [* https://duo.com/assets/pdf/WoW64-Bypassi... *](https://duo.com/assets/pdf/WoW64-Bypassing-EMET.pdf) | WoW64 and So Can You - Bypassing EMET With a Single Instruction | xx-xx-2015 | Darren Kemp, Mikhail Davidov | Windows | N/A |
| 26 | [http://xlab.tencent.com/en/2015/12/09/by...](http://xlab.tencent.com/en/2015/12/09/bypass-dep-and-cfg-using-jit-compiler-in-charkra-engine/) | Bypass DEP and CFG using JIT compiler in Chakra engine | 09-12-2015 | tombkeeper | Windows | N/A |
| 27 | [http://casual-scrutiny.blogspot.de/2016/...](http://casual-scrutiny.blogspot.de/2016/02/cve-2015-2545-itw-emet-evasion.html) | CVE-2015-2545 ITW EMET Evasion | 04-02-2016 | r41p41 | Windows | [CVE-2015-2545](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2015-2545) |
| 28 | [https://www.fireeye.com/blog/threat-rese...](https://www.fireeye.com/blog/threat-research/2016/02/using_emet_to_disabl.html) | USING EMET TO DISABLE EMET | 23-02-2016 | Abdulellah Alsaheel , Raghav Pande | Windows | N/A |

### Kernel mode

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://sysc.tl/2010/04/26/kernel-exploit...](https://web.archive.org/web/20150913234257/http://sysc.tl/2010/04/26/kernel-exploitation-mitigations/) | FreeBSD kernel exploitation mitigations | 26-04-2010 | Patroklos (argp) Argyroudis | FreeBSD | N/A |
| 2 | [https://web.archive.org/web/201112171438...](https://web.archive.org/web/20111217143845/http://labs.mwrinfosecurity.com/notices/assessing_the_tux_strength_part_2_into_the_kernel/) | Assessing the Tux Strength: Part 2 - Into the Kernel | 02-09-2010 | Radoslaw Madej | Linux | N/A |
| 3 | [https://wiki.ubuntu.com/Security/Feature...](https://wiki.ubuntu.com/Security/Features) | Security/Features - Ubuntu Wiki | 17-02-2011 | ubuntu.com | Linux | N/A |
| 4 | [* http://census.gr/media/bheu-2011-wp.pdf *](http://census.gr/media/bheu-2011-wp.pdf) | Protecting the Core: Kernel Exploitation Mitigations | 18-03-2011 | Patroklos (argp) Argyroudis, Dimitris Glynos | FreeBSD | N/A |
| 5 | [http://blogs.msdn.com/b/sdl/archive/2012...](http://blogs.msdn.com/b/sdl/archive/2012/04/24/guarding-against-re-use-of-stale-object-references.aspx) | Guarding against re-use of stale object references | 24-04-2012 | Doug Cavit | Windows |  N/A |
| 6 | [https://blog.duosecurity.com/2012/07/exp...](https://web.archive.org/web/20160329141537/https://duo.com/blog/exploit-mitigations-in-android-jelly-bean-4-1) | Exploit Mitigations in Android Jelly Bean 4.1 | 16-07-2012 | Jon Oberheide | Android | N/A |
| 7 | [http://0xfeedface.org/blog/lattera/2012-...](http://0xfeedface.org/2012/07/19/new-exploit-protections-in-android-4-1.html) | New Exploit Protections in Android 4.1 | 19-07-2012 | Shawn Webb | Android | N/A |
| 8 | [http://blogs.technet.com/b/srd/archive/2...](http://blogs.technet.com/b/srd/archive/2012/07/24/emet-3-5-tech-preview-leverages-security-mitigations-from-the-bluehat-prize.aspx) | EMET 3.5 Tech Preview leverages security mitigations from the BlueHat Prize | 24-07-2012 | swiat | Windows | N/A |
| 9 | [http://blogs.technet.com/b/srd/archive/2...](http://blogs.technet.com/b/srd/archive/2012/07/26/technical-analysis-of-the-top-bluehat-prize-submissions.aspx) | Technical Analysis of the Top BlueHat Prize Submissions | 26-07-2012 | swiat | Windows | N/A |
| 10 | [http://forums.grsecurity.net/viewtopic.p...](http://forums.grsecurity.net/viewtopic.php?f=7&t=3292) | Recent ARM security improvements | 18-02-2013 | spender | ARM | N/A |
| 11 | [* http://0xdabbad00.com/wp-content/uploads... *](http://0xdabbad00.com/wp-content/uploads/2013/11/emet_4_1_uncovered.pdf) | EMET 4.1 Uncovered | 18-11-2013 | 0xdabbad00  | Windows | N/A |
| 12 | [http://blogs.technet.com/b/srd/archive/2...](http://blogs.technet.com/b/srd/archive/2013/12/11/software-defense-mitigating-common-exploitation-techniques.aspx) | Software defense: mitigating common exploitation techniques | 11-12-2013 | swiat | Windows | N/A |
| 13 | [https://labs.mwrinfosecurity.com/blog/20...](https://labs.mwrinfosecurity.com/blog/2014/08/15/windows-8-kernel-memory-protections-bypass/) | Windows 8 Kernel Memory Protections Bypass | 15-08-2014 | Jérémy (__x86) Fetiveau | Windows 8 | N/A |
| 14 | [http://breakingmalware.com/vulnerabiliti...](https://web.archive.org/web/20160323042053/http://breakingmalware.com/vulnerabilities/one-bit-rule-bypassing-windows-10-protections-using-single-bit/) | One-Bit To Rule Them All: Bypassing Windows’ 10 Protections using a Single Bit | 10-02-2015 | Udi Yavo | Windows | [CVE-2015-0057](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2015-0057) |
| 15 | [http://keenlab.tencent.com/en/2016/06/01...](http://keenlab.tencent.com/en/2016/06/01/Emerging-Defense-in-Android-Kernel/) | Emerging Defense in Android Kernel | 01-06-2017 | James Fang | Android | N/A |


### General

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | *http://www.freeinfosociety.com/media/pdf/2708.pdf* | A Buffer Overflow Study - Attacks & Defenses | 2002 | Pierre-Alain FAYOLLE, Vincent GLAUME | Linux | N/A |
| 2 | [* https://static.googleusercontent.com/medi... *](https://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/34913.pdf) | Native Client: A Sandbox for Portable, Untrusted x86 Native Code | 2009 | Bennet Yee, David Sehr, Gregory Dardyk, J. Bradley Chen, Robert Muth, Tavis Ormandy, Shiki Okasaka, Neha Narula, and Nicholas Fullagar | - | N/A |
| 3 | [https://drive.google.com/file/d/0B5pT4hU_...](https://drive.google.com/file/d/0B5pT4hU_yYUWcUtsUWxxcFJjOVU/view) | An Evaluation of the Effectiveness of EMET 5.1 At Protecting Everyday Applications Against Targeted Attacks | 2015 | Grant Willcox | Windows | N/A |
| 4 | [https://github.com/deroko/payloadrestrict...](https://github.com/deroko/payloadrestrictions) | PayloadRestrictions | 05-09-2017 | deroko | Windows 10 | N/A |  


## Hardware-based mitigations

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [https://web.archive.org/web/201201200727...](https://web.archive.org/web/20120120072718/http://falken.tuxfamily.org/?p=115) | Beat SMEP on Linux with Return-Oriented Programming | 09-11-2011 | falk3n | Linux, x86-64 | N/A |
| 2 | [http://forums.grsecurity.net/viewtopic.p...](http://forums.grsecurity.net/viewtopic.php?f=7&t=3046) | Supervisor Mode Access Prevention | 07-09-2012 | Pax Team | - | N/A |
| 3 | [http://blog.ptsecurity.com/2012/09/intel...](http://blog.ptsecurity.com/2012/09/intel-smep-overview-and-partial-bypass.html) | Intel SMEP overview and partial bypass on Windows 8 | 17-09-2012 | Artem Shishkin | Windows 8 | N/A |
| 4 | [http://www.cyvera.com/the-case-for-smep-...](https://web.archive.org/web/20150328004451/http://media.paloaltonetworks.com/lp/endpoint-security/blog/the-case-for-smep-exploiting-a-kernel-vulnerability.html) | THE CASE FOR SMEP – EXPLOITING A KERNEL VULNERABILITY | 20-09-2013 | Gal Badishi | Windowx XP, x86-32 | N/A |
| 5 | [http://hypervsir.blogspot.de/2014/10/i...](http://hypervsir.blogspot.de/2014/10/introduction-on-hardware-security.html?m=1) | Introduction to Processor Hardware Security Features in x86 & ARM Architectures | 06-05-2014 | Anababa | x86, ARM | N/A |
| 6 | [http://atredispartners.blogspot.de/2014/...](http://atredispartners.blogspot.de/2014/08/here-be-dragons-vulnerabilities-in.html) | Here Be Dragons: Vulnerabilities in TrustZone | 15-08-2014 | Nathan Keltner | ARM | N/A |
| 7 | [https://www.nccgroup.com/en/blog/2015/01...](https://www.nccgroup.com/en/blog/2015/01/intel-software-guard-extensions-sgx-a-researchers-primer/) | Intel® Software Guard Extensions (SGX): A Researcher’s Primer | 05-01-2015 | Ollie Whitehouse | - | N/A |
| 8 | [https://www.nccgroup.trust/uk/about-us/n...](https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2015/april/xen-smep-and-smap-bypass/) | Xen SMEP (and SMAP) bypass | 09-04-2015 | Aaron Adams | XEN | N/A |
| 9 | [* http://www.alex-ionescu.com/Enclave%20Su... *](http://www.alex-ionescu.com/Enclave%20Support%20In%20Windows%2010%20Fall%20Update.pdf) | Intel SGX Enclave Support in Windows 10 Fall Update (Threshold 2) | 08-11-2015 | Alex Ionescu | Windows 10 | N/A |
| 10 | [https://blogs.msdn.microsoft.com/vcblog/...](https://blogs.msdn.microsoft.com/vcblog/2016/01/20/visual-studio-2015-update-1-new-experimental-feature-mpx/) | Visual Studio 2015 Update 1: New Experimental Feature – MPX | 20-01-2016 | Jim Hogg | Windows | N/A |


## Specific mitigations

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://blog.ptsecurity.com/2014/09/micro...](http://blog.ptsecurity.com/2014/09/microsoft-windows-81-kernel-patch.html?m=1) | Microsoft Windows 8.1 Kernel Patch Protection Analysis & Attack Vectors | 17-08-2014 | Mark Ermolov, Artem Shishkin | Windows 8.1 | N/A |
| 2 | [http://vrt-blog.snort.org/2014/08/the-wi...](https://web.archive.org/web/20150826061425/http://vrt-blog.snort.org/2014/08/the-windows-81-kernel-patch-protection.html) | The Windows 8.1 Kernel Patch Protection | 24-08-2014 | Andrea Allievi | Windows 8.1 | N/A |
| 3 | [http://scarybeastsecurity.blogspot.de/20...](http://scarybeastsecurity.blogspot.de/2014/09/using-asan-as-protection.html) | Using ASAN as a protection | 25-09-2014 | Chris Evans | - | N/A |
| 4 | [http://blogs.cisco.com/security/mitigati...](http://blogs.cisco.com/security/mitigations-available-for-the-dram-row-hammer-vulnerability) | Mitigations Available for the DRAM Row Hammer Vulnerability | 09-03-2015 | Omar Santos | - | N/A |
| 5 | [http://googleprojectzero.blogspot.de/201...](http://googleprojectzero.blogspot.de/2015/08/three-bypasses-and-fix-for-one-of.html) | Three bypasses and a fix for one of Flash's Vector.<*> mitigations | 19-08-2015 | Chris Evans | - | N/A |
| 6 | [https://forums.grsecurity.net/viewtopic....](https://forums.grsecurity.net/viewtopic.php?f=7&t=4463) | Linux Kernel BPF JIT Spraying | 03-05-2016 | spender | Linux | N/A |
| 7 | [https://bugs.chromium.org/p/project-zero...](https://bugs.chromium.org/p/project-zero/issues/detail?id=856) | PaX: reference count overflow mitigation can be bypassed on x86 by racing | 27-06-2016 | jannh | Linux | N/A |
| 8 | [https://googleprojectzero.blogspot.de/20...](https://googleprojectzero.blogspot.de/2016/11/breaking-chain.html?spref=tw) | Breaking the Chain | 29-11-2016 | James Forshaw | Windows | N/A |


## Other exploitation obstacles

Non-compiler, OS, or hardware enforced exploitation difficulties.

| *Nr* | *URL* | *Description* | *Date* | *Author* | *OS/Arch* | *Info* |
|  -- | -- | -- | -- | -- | -- | -- |
| 1 | [http://www.corelan.be/index.php/200...](http://www.corelan.be/index.php/2009/11/06/exploit-writing-tutorial-part-7-unicode-from-0x00410041-to-calc/) | Exploit writing tutorial part 7 : Unicode – from 0×00410041 to calc | 06-11-2009 | corelanc0d3r | Windows, x86-32 | <a href="http://osvdb.org/show/osvdb/66912" title="View OSVDB-66912 info">OSVDB-66912</a> |
| 2 | [http://grey-corner.blogspot.com/2010/01/...](http://grey-corner.blogspot.com/2010/01/windows-buffer-overflow-tutorial.html) | Windows Buffer Overflow Tutorial: Dealing with Character Translation | 17-01-2010 | Stephen Bradshaw | Windows, x86-32 | <a href="http://osvdb.org/show/osvdb/59772" title="View OSVDB-59772 info">OSVDB-59772</a> |
| 3 | [https://web.archive.org/web/201104170711...](https://web.archive.org/web/20110417071123/http://www.abysssec.com/blog/2010/03/ken-ward-zipper-stack-bof-0day-a-not-so-typical-seh-exploit/) | Ken Ward Zipper Stack BOF 0day – a not so typical SEH exploit | 18-03-2010 | corelanc0d3r | Windows, x86-32 | <a href="http://osvdb.org/show/osvdb/63125" title="View OSVDB-63125 info">OSVDB-63125</a> |
| 4 | [http://www.corelan.be/index.php/201...](http://www.corelan.be/index.php/2010/03/27/exploiting-ken-ward-zipper-taking-advantage-of-payload-conversion/) | Exploiting Ken Ward Zipper : Taking advantage of payload conversion | 27-03-2010 | Tutorial | Windows, x86-32 | N/A |
| 5 | [http://www.corelan.be/index.php/201...](http://www.corelan.be/index.php/2010/03/27/quickzip-stack-bof-0day-a-box-of-chocolates/) | QuickZip Stack BOF 0day: a box of chocolates (2 parts) | 27-03-2010 | corelanc0d3r | Windows, x86-32 | N/A |
| 6 | [* https://docs.google.com/viewer?a=v&pid=e... *](https://docs.google.com/viewer?a=v&pid=explorer&chrome=true&srcid=1U1cGztE8e08ALZuGjSFRemHW5dhZ01YT1ab-ShCKOd5E82X62T82l7eQt2fb&hl=en) | Unicode, the magic of exploiting 0×00410041 | 29-05-2010 | mr_me | Windows, x86-32 | [CVE-2009-2225](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2009-2225) |
| 7 | [http://www.exploit-db.com/winamp-5-58-fr...](http://www.exploit-db.com/winamp-5-58-from-dos-to-code-execution/) | Winamp 5.58 from Denial of Service to Code Execution | 20-10-2010 | muts | Windows, x86-32 | <a href="http://osvdb.org/show/osvdb/68645" title="View OSVDB-68645 info">OSVDB-68645</a> |
| 8 | [http://www.exploit-db.com/winamp-exploit...](http://www.exploit-db.com/winamp-exploit-part-2/) | Winamp 5.58 from Denial of Service to Code Execution Part 2 | 02-11-2010 | muts | Windows, x86-32 | <a href="http://osvdb.org/show/osvdb/68645" title="View OSVDB-68645 info">OSVDB-68645</a> |
| 9 | [https://www.corelan.be/index.php/2011/07...](https://www.corelan.be/index.php/2011/07/27/metasploit-bounty-the-good-the-bad-and-the-ugly/) | Metasploit Bounty – the Good, the Bad and the Ugly | 27-07-2011 | Lincoln | Windows, x86-32 | <a href="http://osvdb.org/show/osvdb/72817" title="View OSVDB-72817 info">OSVDB-72817</a> |
