---
layout: post
published: true
title: How to install Vista Upgrade editions in Parallels
date: '2009-01-18 22:38:42 +0000'
---
Installing MS Windows Vista into Parallels is a bit of a chore if you've only got an upgrade editions of the software. This how-to tells you the steps in order to make it work.

Firstly, make an image of your Vista DVD. This will make the install run much faster, and you'll need to be doing two of those. Insert the vista DVD, then in Disk Utility, select the DVD UDF Volume and press "New Image". Call it Vista, save it to the desktop, and change the image type to "DVD/CD Master".

Once that finishes, it's time to power up Parallels. Make sure you're running at least Release Candidate 1 --- download it from the Parallels website if not. Create a new VM and select "Custom". On the next page, make sure the OS version is set to Windows Vista. Leave the memory, hard disk settings and the network settings alone. Name the Virtual Machine (or again just accept the default).

On the next page, where you're asked to insert the installation CD, open up "More Options", select "ISO Image" and press "Choose" to select the image created earlier - saved to your desktop. Press "Finish" to begin the Vista installation.

Well, actually, your first Vista installation. Because we'll be doing two here. The trick is that we don't enter your licence key the first time around, thus fooling Vista into installing. Unlike XP upgrades, which just needed a look at a CD or a previous installation to proceed, licenced Vista won't install unless it's being installed over the top of a previous OS. Luckily, "previous OS" includes unlicensed Vista!

Start the installation going. The first thing it will ask you is your international settings. Set them as appropriate. Click onto the next page, then click "Install Now". On the following page, it will ask for your product key. Do not type in your product key - instead, press "Next", say "No" to the following dialog box, then on the next page choose the version of Vista you're installing.

(I have no idea what the difference between, say, Business and BusinessN is - can someone enlighten me? I just chose from the non-N ones.)
Tick the box on that page, press Next, accept the licence terms, press Next. On the following screen the type of installation will be set to "Custom". That's fine. Press Next to choose where to install it, the default is fine so press Next again.

At this point the installation of Vista will start. The VM will reboot several times - just let it do so. Installation will run to completion just fine, go away for 30 minutes.

(time passes)

Choose a username and on the next page, a computer name. These aren't vital but you'll need to remember the username for the next 30 minutes. Then, on the security updates page, select "Ask me later" --- one of the current Vista updates breaks Parallels, and we don't want that to happen. Finally, set your timezone, then press "Start".

Vista will then check the VM's performance, then start up. Congratulations, it's installed. Log in, and do not install Parallels Tools right now. It will cause you pain later.

Now we're going to do all of this over again, this time with a licence key.

From the Start Menu, choose Computer, then double-click on the DVD drive. Double-click on Setup. Allow the program to run. Click on "Install now".

On the next screen, don't get the latest updates for installation at this time, because it might crash Parallels. On the next screen, enter your product key. Accept the license, as before.

On the following screen, again click on "Custom" for type of installation. Accept the default for the installation disk, as before, then click "OK" in the dialog box. 
Installation will then start. Another 30 minutes here.

(time passes, again)

This time, when asked for a username and computer name, choose ones you wish to stick with as this is final. Choose "Ask me later" for the security updates, then set the timezone as before.

Vista will again check performance, then start.

That's it. We're done. Just tidy-up to do now.

Firstly, install Parallel Tools from the Mac "Action" menu. This will give proper integration between your Mac and the Vista VM. It'll need a reboot. After that, navigate from "Computer" on the Start Menu to your hard disk, then delete the "windows.old" directory. That was the initial install.

Now, from the Mac's "Action" menu, run the Parallels Disk Compressor, in order to neaten up the VM's hard disk. This takes a while. But once it's done:

Congratulations. You have a perfectly fresh working installed copy of Vista, from a Vista Upgrade CD, in a Parallels VM.

Now go and enjoy before Parallels bring out a new version, forcing this to become incorrect and me to write out a corrected version.

Enjoy!
