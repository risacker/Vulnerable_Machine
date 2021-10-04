# De-COW(Vuln_Machine)

Name of vulnerable machine: <b>De_COW</b>.

#### What is De-COW:

De-COW is a vulnerable machine made for a CTF. In this vulnerable machine Dirty COW vulnerability is established. Dirty COW vulnerability is a type of privilege escalation exploit, which essentially means that it can be used to gain <b>root-user access</b> on any Linux-based system.  While security experts claim that such kinds of exploits are not uncommon, its easy-to-exploit nature and the fact that it has been around for more than 11 years is pretty worrisome. Dirty COW gets its name from the <b>copy-on-write (COW)</b> mechanism in the kernel's memory management system. Malicious programs can potentially set up a race condition to turn a read-only mapping of a file into a writable mapping. Thus, an underprivileged user could utilize this flaw to elevate their privileges on the system. By gaining root privileges, malicious programs obtain unrestricted access to the system. From there on, it can modify system files, deploy keyloggers, access personal data stored on your device, etc.

#### What Systems are affected:

Dirty COW vulnerability affects all versions of the Linux Kernel since version 2.6.22, which was released in 2007. According to Wikipedia, the vulnerability has been patched in kernel versions 4.8.3, 4.7.9, 4.4.26 and newer. A patch was released in 2016 initially, but it didn't address the issue fully, so a subsequent patch was released in November 2017. Major Linux distros like Ubuntu, Debian and ArchLinux have all released the appropriate fixes. So if you haven't already, make sure to update your Linux kernel.

<b><i>Since most of the systems are now patched, the risk is mitigated, right? Well, not exactly.</b></i>

While most of the mainstream systems have been patched, there are several other Linux-based embedded devices like IoT devices that are still vulnerable. Since Android is based on the Linux kernel, a majority of Android devices are also affected.
























#### Link for De-COW(Vuln_Machine):

https://drive.google.com/file/d/1Wr4Q3rI9elqvRNQpk32TDMVlKtSxAxqN/view?usp=sharing


