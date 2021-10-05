# De-COW(Vuln_Machine)

Name of vulnerable machine: <b>De-COW</b>.

#### What is De-COW:

De-COW is a vulnerable machine made for a CTF. In this vulnerable machine Dirty COW vulnerability is established. Dirty COW vulnerability is a type of privilege escalation exploit, which essentially means that it can be used to gain <b>root-user access</b> on any Linux-based system.  While security experts claim that such kinds of exploits are not uncommon, its easy-to-exploit nature and the fact that it has been around for more than 11 years is pretty worrisome. Dirty COW gets its name from the <b>copy-on-write (COW)</b> mechanism in the kernel's memory management system. Malicious programs can potentially set up a race condition to turn a read-only mapping of a file into a writable mapping. Thus, an underprivileged user could utilize this flaw to elevate their privileges on the system. By gaining root privileges, malicious programs obtain unrestricted access to the system. From there on, it can modify system files, deploy keyloggers, access personal data stored on your device, etc.

#### What Systems are affected:

Dirty COW vulnerability affects all versions of the Linux Kernel since version 2.6.22, which was released in 2007. According to Wikipedia, the vulnerability has been patched in kernel versions 4.8.3, 4.7.9, 4.4.26 and newer. A patch was released in 2016 initially, but it didn't address the issue fully, so a subsequent patch was released in November 2017. Major Linux distros like Ubuntu, Debian and ArchLinux have all released the appropriate fixes. So if you haven't already, make sure to update your Linux kernel.

<b><i>Since most of the systems are now patched, the risk is mitigated, right? Well, not exactly.</b></i>

While most of the mainstream systems have been patched, there are several other Linux-based embedded devices like IoT devices that are still vulnerable. Since Android is based on the Linux kernel, a majority of Android devices are also affected.


#### How can you protect yourself from malware(ZNIU) attacks:

<b>ZNIU</b> is the first malware for Android based on the Dirty COW vulnerability. It can be utilized to root any Android devices up to <b>Android 7.0 Nougat</b>. While the vulnerability itself affects all versions of Android, ZNIU specifically affects Android devices with the <b>ARM/X86 64-bit architecture</b>. The ZNIU-affected app often appears as a soft-porn app on malicious websites, where users are tricked into downloading it. Since Android makes it easy to sideload apps, a lot of novice users fall into this trap and download it. If your device is running Android 4.4 KitKat and above, make sure that you have the latest security patch installed. To check this, open <b>Settings > About phone</b>. Scroll to the bottom and check <b>Android security patch level</b>. If the installed security patch is newer than December 2016, you should be protected from this vulnerability. While <b>Android antivirus apps</b> can detect such elevated-permission attacks, they cannot prevent it. Anti-virus apps may be useful for other features such as anti-theft, but they certainly aren't much use in this case. As a final precaution, you should be mindful when it comes to installing apps from unknown sources. <b>Android 8.0 Oreo</b> makes installing apps from unknown sources a little bit safer, but you should still proceed with caution.

#### Steps to be Followed in making of Vulnerable Machine:

Step 1: Download old releases of Ubuntu.

     Visit http://old-releases.ubuntu.com/releases/ if you want to download old releases of ubuntu.
     
I have downloaded <b>16.04.1/ version</b> for making this vulnerable machine.

Step 2: Use virtual box to install this as it is easy to export the <b>OVA file</b> that you later will upload on some CTF platforms.









### Link for De-COW(Vuln_Machine):

https://drive.google.com/file/d/1Wr4Q3rI9elqvRNQpk32TDMVlKtSxAxqN/view?usp=sharing


