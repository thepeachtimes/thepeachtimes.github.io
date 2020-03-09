---
layout: post
title: "wireguard: a new type of vpn"
---

![](https://www.wireguard.com/img/wg-tool.png)

If you keep up-to-date with the Linux mailinglist, you might have heard that Wireguard is going to be included in the Linux Kernel some time soon. But what is wireguard?

Wireguard is a new type of vpn protocol that works on the kernel level. Traditional vpn protocols like OpenVPN are out of date and inefficent, but since Wireguard is on the Kernel level, it can be heavily optimized. There are, however, problems with it running on the kernel level. First off, to run on the Kernel level, it needs to run as a Kernel module, and that would require you to re-compile your kernel to install it. Another problem is that it can be difficult to update since its running on a lower level than package managers. These both can be solved by integrating it into the Linux kernel, since it would be already compiled and updated fairly often.


