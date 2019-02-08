# Team Lost's Guide to Trying Harder

###### 

###### **Recommended reading:**

* **Hacking, the Art of Exploitation:** Introduces fundamentals to exploit writing. You don't need to know all of it for OSCP, but this helps you appreciate things.
* **Penetration Testing: A Hands-on Introduction to Hacking: **This book by Georgia Weidman follows closely to the OSCP course material. She also has online video tutorials if that's your thing.
* [**OWASP Juice Shop: **](https://github.com/bkimminich/juice-shop)Self hosted lab catering to the fundamentals of web application testing.
* [**A llama's guide to OSCP**](https://legacy.gitbook.com/book/lim1ts/team-lost-essentials/edit#)**: **Abatchy is a pretty cool dude.

###### 

###### Quick guides:

* [FuzzySecurity's Windows privilege escalation walkthrough](http://www.fuzzysecurity.com/tutorials/16.html)
* [Guide to Linux privilege escalatio](https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/)n
* [NMap script list ](https://nmap.org/nsedoc/)\(Learn how to use this, seriously\)
* [Enumeration guide](http://www.0daysecurity.com/penetration-testing/enumeration.html) \(Beginners will suck at this, so look through it\)
* [Simple tests for SQL servers](https://www.owasp.org/index.php/Testing_for_SQL_Server)
* [Getting shell from SQL injection](http://resources.infosecinstitute.com/anatomy-of-an-attack-gaining-reverse-shell-from-sql-injection/)
* [From LFI to RCE](https://www.exploit-db.com/papers/12992)
* [Stackexchange: How to interpret nmblookup?](https://superuser.com/questions/710304/how-to-interpret-output-of-nmblookup-a)

###### 

###### **Useful cheatsheets and references:**

* [Linuxprivchecker](https://github.com/sleventyeleven/linuxprivchecker/blob/master/linuxprivchecker.py)
* [windows-privesc-check](https://github.com/pentestmonkey/windows-privesc-check)
* [Shellstorm shellcodes](http://shell-storm.org/shellcode/) \(for when you are too lazy to even use msfvenom\)
* [Tty shell spawning](http://netsec.ws/?p=337), most often you will get a limited shell; no tab completion, Crtl-C to end process ends the session,etc. Does the victim machine have `socat` installed? Or `gcc` and `make`? [Try this.](https://github.com/cornerpirate/socat-shell)
* Limited commands? Jailed in a chroot? Escape with unix binaries - [GTFObins](https://gtfobins.github.io/).

##### 

##### Personal Opinions

> ##### **Who should take the OSCP certification?**

OSCP is not for everyone in the security field, but it's a pretty good cert for a relatively affordable price. The techniques taught are pretty basic, but it's a "door-opener" for pentesting firms and shows that the student is a motivated learner.

> **How difficult is OSCP?**

At the time of writing, I have only ever studied at the National University of Singapore\(NUS\). The OSCP course material is equivalent to a level 4-5000 module in both difficulty as well as depth of content. Meaning that a level of competence in general programming concepts, unix command line and ability to google is heavily recommended prior to taking the course. However, OSCP's labs are available at 30, 60 and 90 day packages. The less lab time you purchase, the more time you should expect to spend in the labs per day. I had 30 days, and passed on my first attempt after spending 8-10 hours per day on average.

> **What was the exam like?**

The exam is much easier than the labs, given that you have practiced enough. I only took about 18 machines in my 30 days, and 2 of the big 4. Don't rely on Metasploit, always try to understand why an exploit works or why it doesn't. Try to remain calm and don't get tilted during your exam. Also keep yourself hydrated, take frequent breaks and eat your meals. Take a nap if you can afford to.

