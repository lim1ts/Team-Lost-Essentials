**General:**

* [Reversing for beginners](https://beginners.re/): This is the holy grail. 
* [Become a full-stack reverse engineer in 3 years](https://www.youtube.com/watch?v=9vKG8-TnawY)
* [Practical Malware Analysis](https://www.amazon.com/Practical-Malware-Analysis-Hands-Dissecting-ebook/dp/B007ED2XDS): Everything here is user mode
* [Rootkit Arsenal](https://www.amazon.com/Rootkit-Arsenal-Escape-Evasion-Corners-ebook/dp/B007RFXCEW): More on the kernel side of stuff
* For wargames, check the playing CTFs section.

Do try out previous editions of Flare-Ons from FireEye, and try to play in the next coming one if you can.

**Hardware:**

* [The Hardware Hacker](http://index-of.es/Varios-2/The Hardware Hacker.pdf)
* [Hacking the xbox](https://bunniefoo.com/nostarch/HackingTheXbox_Free.pdf): A lot of the first generation xboxes were redesigned largely due to the RE efforts. It will not be easy finding an xbox to follow along this tutorial, but this book is still a gem nonetheless.
* [Embedded Linux Primer](https://www.amazon.com/Embedded-Linux-Primer-Practical-Real-World/dp/0137017839): Similarly, this is very old. Will be relevant should you choose to work on older systems with monolithic operating systems.
* [\[Presentation Slides\] Intro to hardware reversing embedded devices](http://hexblog.com/files/recon 2010 Skochinsky.pdf): This looks old, but really isn't. The techniques are basic enough to apply to a wide range of embedded devices you might find lying around.
* \[OWASP Embedded Application Security
  \]\([https://www.owasp.org/index.php/OWASP\_Embedded\_Application\_Security](https://www.owasp.org/index.php/OWASP_Embedded_Application_Security)\): Learn about best practices here, and what to audit for.
* A few stackoverflow posts that are very useful when analyzing unknown firmware formats: [1](https://reverseengineering.stackexchange.com/questions/17262/binwalk-alternative),[2](https://reverseengineering.stackexchange.com/questions/15088/lzma-file-format-not-recognized-details-enclosed/15116#15116),[3](https://reverseengineering.stackexchange.com/questions/15006/approach-to-extract-useful-information-from-binary-file/15025#15025)

**Tools:**

* [Binwalk](https://github.com/devttys0/binwalk): A fast, easy to use tool for analyzing, reverse engineering, and extracting firmware images.

* [Pip3line, the Swiss army knife of byte manipulation](https://nccgroup.github.io/pip3line/index.html): Pip3line is a raw bytes manipulation utility, able to apply well known and less well known transformations from anywhere to anywhere \(almost\).
* [Frida](http://www.frida.re/docs/home/): Inject JS into native apps

**Emulators**

* [Unicorn-Engine](http://www.unicorn-engine.org/)
  * Unicorn is a lightweight multi-platform, multi-architecture CPU emulator framework.
* [pegasus - Windbg extension DLL for emulation](https://github.com/0a777h/pegasus)
  * Windbg emulation plugin

**ELF/Related Tools**

* [Rdis](https://github.com/endeav0r/rdis)
  * Rdis is a Binary Analysis Tool for Linux.
* [readelf](https://sourceware.org/binutils/docs/binutils/readelf.html)
  * Unix Tool

**References**

* [FCC ID Lookup](http://transition.fcc.gov/oet/ea/fccid/): Lookup devices according to FCC ID

//embedded devices should deserve their own section...

