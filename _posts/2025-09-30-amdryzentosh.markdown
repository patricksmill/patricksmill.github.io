---
layout: post
title:  "AMD Ryzentosh: It's the Journey..."
date:   2025-09-30 12:35:19 -0400
categories: software
---

In the summer of 2024, I became interested in building my own [Hackintosh](https://en.wikipedia.org/wiki/Hackintosh). I had not used MacOS since 3rd grade at my elementary school, and since then had used primarily Windows with the occassional linux distro attempted every other month. I was so interested that when it was time to upgrade my graphics card, I dropped the NVIDIA 1650 Super for an AMD RX 6600 for better compatability with MacOS, per the [Dortania OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/). This guide can be a little overwhelming and is not completely up-to-date, but it is a good starting point for anyone wondering if it is even possible to Hackintosh their system.

Within 24 hours, I had a working MacOS Sonoma install on my desktop, dual booting with windows 11. I made my EFI "by hand" per the guidance of Dortania, so that I could learn the basic workings of OpenCore in case of troubleshooting (which there was). Currently, I use [OCAT](https://github.com/ic005k/OCAuxiliaryTools) in order to update the EFI in a less time-consuming manner.

After a few hours of tinkering around in this new (to me) MacOS world, one question remained in my mind: "What now?" I hadn't put much thought into what I would actually **do** with it. Gaming was pretty quickly ruled out. Using MacOS for gaming while having a perfectly good Windows setup is like converting your car into a unicycle for commuting to work. For productivity apps, MacOS can be beneficial over Windows. Thing is, Photoshop worked fine on Windows, and I didn't see myself deciding to pick up Final Cut Pro on a whim.

What I **finally** ended up utilizing this partition for (after 6 months), in March of 2025, was iOS app development using XCode. I could develop apps and test them on my actual phone. This was in contrast to the app development I was doing in my Software Design class using Android Studio, relying on only the virtual device to test the feel of my app. Actually being able to swipe and **feel** how an app would in my hands was very addictive.

I think even if I didn't find something of value to do with the MacOS partition, the lessons I learned while troubleshooting made the experience eboth ducational and gratifying.

[My EFI can be found here.](https://github.com/patricksmill/AMDRyzentoshEFI)

**Skills learned/practiced:**

* EFI bootloader configuration and troubleshooting
* Understanding of OpenCore and Hackintosh architecture
* Dual-boot setup and partition management
* Problem-solving and research using forums and guides
* Patience and persistence in debugging hardware/software compatibility
* Using tools like OCAT for EFI management
* Documentation and sharing solutions with the community
