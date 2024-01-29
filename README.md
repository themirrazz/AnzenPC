# Welcome to the Anzen PC!
## What is the Anzen PC?
The Anzen PC are designs I'm working on to create the world's safest personal computer in history.
By having the complete bare minimum of an operating system, I believe we can prevent computers from being digitally hacked or getting viruses.

## What can I use the Anzen PC for?
To make it easy for many people to use, we have lots of different apps included, and allow for multi-functionality. We have code editors, web browsers, word processors, calculators, file managers, PDF viewers, basic image and video editors, and even a REAPER-compatible audio editor. That's right - our audio editor lets you export a ZIP file that even contains subdirectories. It can be imported on Windows, MacOS, *and* Linux.

## How does the Anzen PC work?
Let's look at something simple and childish: Snap Circuits. The functionality of the Music IC (U1) is written in stone. It can *only* play Happy Birthday, and it is physically *impossible* to repgroram it to do anything else.
The Anzen PC relies on hardware that cannot be physically re-programmed.
While it does have some software, code is parsed directly via hardware instead of a compiler or operating system with possible exploits.
Let's take a look at the features apps to see how they work.

### Internet - Web Browser
This is our custom, hardware-based web browser. However, this relies on some software.
It runs HTML5, ES6 JavaScript, and CSS3, all using seperate hardware chips.
It actually supports WebGL using our special WebGL+3D Render chips, as well as HTML5 video, images, and audio using our video/audio decoder.
It can also use your location, webcam, and microphone; however, if there is an exploit in this, we've added a security feature by connecting it directly to these chips. These chips tell you which app is using what, and let you block access from the app from using it. We don't expect the browser to go rogue, however.

### Henshu Audio
We have a chip dedicated to the entire functionality of REAPER, including purchasing REAPER. Of course, the evaluation copy will never be crippled because they believe it is not in the best interest of their customers. HOWEVER, you should activate the audio editor; it is at a reasonable price and all money will go to the official REAPER team. You can also purchase an AnzenPC that has REAPER pre-activated. Please make sure while activating REAPER, you are on a secure network - while this laptop does the best to protect you; if you are on an insecure or comprimised network, it cannot stop network attacks.

### Hogosha Scanner
This is a unique, one-of-a-kind malware scanner. It can scan downloaded files, email attachments, and files on removable storage mediums (USB sticks, optical disks, floppy disks, memory cards, etc.) for different kinds of malware. It downloads malware definitions to seperate chips using verification encrypted using strong uncrackable asymetrical encryption. It can scan your devices for malware designed for Windows, macOS, Linux, and Android.

### Explorer - File Manager
You have 576GB of encrypted storage that is encrypted with a secret code unique to the laptop that can only be decoded by a specific chip - 512GB is your "main" storage, and the other 64GB is your "Kinko" - a vault that is AES encrypted. The difference between the encryptions is that your main 512GB of storage don't require a password to access; they just can only be physically accessed on your own laptop. Your Kinko, however, is AES-encrypted with a passkey of your choice, and if you lose this password, you will *permanently* lose access to all data in your Kinko. In addition, the web browser's "filesystem" functionallity cannot physically access your Kinko. You can download files to your Kinko, but you cannot open files from your Kinko.
In addition, the Explorer also has the ability to mount external disks and drives via USB.
Currently, through USB, the Explorer supports mounting unencrypted USB drives that are formatted with FAT16, FAT32, exFAT, ext4, or NTFS.
It also supports mounting USB drives that have been encrypted/formatted with ext4 or the special Kinko KVFS (Kinko Vault FileSystem).
Yes. It literally means "Kinko Kinko Vault Filesystem". Wanna know just how useless this name is?
The name "Kinko" is a shortened version of「金庫室」(or "kinko-shitsu"), which is Japanese for "vault".
So yes, go ahead, laugh at me. I named this special encrypted format "Vault Vault Vault Filesystem".
