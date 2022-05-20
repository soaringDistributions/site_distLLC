
_ Soaring Distributions LLC _
 '_picture' './logo_distLLC.png'
_r '
<a href="https://bit.ly/distllc">https://bit.ly/distllc</a> &lpar; <a href="https://soaringdistributions.github.io/site_distLLC/">https://soaringdistributions.github.io/site_distLLC/</a> &rpar;
'

__ Markings __

Please mark physical copies of Linux.
Do NOT run NVIDIA hardware with Linux and then redistribute that copy.

__ Authentic Software __
Official publicly accessible locations of Soaring Distributions LLC are normally HTTPS or similarly provable sites controlled by Soaring Distributions LLC.

https://u298813-sub*.your-storagebox.de
https://u298813-sub7.your-storagebox.de
(hosted by Hetzner)

https://github.com/soaringDistributions
https://soaringDistributions.github.io/site_distLLC
(hosted by GitHub)

Unless officially and provably directed to do so by authorized personnel of Soaring Distributions LLC (ie. manager of Soaring Distributions LLC, mirage335), or unless the products are provably identical, Soaring Distributions LLC cannot reasonably guarantee similar expectations for products obtained from other locations.

__ Products - End User __

Username   u298813-sub7
Password   wnEtWtT9UDyJiCGw

_r '
<a href="https://u298813-sub7.your-storagebox.de/mirage335KernelBuild/linux-lts-amd64-debian.tar.gz">https://u298813-sub7.your-storagebox.de/mirage335KernelBuild/linux-lts-amd64-debian.tar.gz</a>
'
 
_r '
<a href="https://u298813-sub7.your-storagebox.de/mirage335KernelBuild/linux-mainline-amd64-debian.tar.gz">https://u298813-sub7.your-storagebox.de/mirage335KernelBuild/linux-mainline-amd64-debian.tar.gz</a>
'
 
 
_r '
<a href="https://u298813-sub7.your-storagebox.de/ubcp/package_ubiquitous_bash-msw.7z">https://u298813-sub7.your-storagebox.de/ubcp/package_ubiquitous_bash-msw.7z</a>
'
 
 
_r '
<a href="https://github.com/soaringDistributions/ubDistBuild/raw/main/_lib/custom/package_kde.tar.xz">https://github.com/soaringDistributions/ubDistBuild/raw/main/_lib/custom/package_kde.tar.xz</a>
'
 
 
_r '
<a href="https://u298813-sub7.your-storagebox.de/ubDistFetch/core.tar.xz">https://u298813-sub7.your-storagebox.de/ubDistFetch/core.tar.xz</a>
'
 
_r '
<a href="https://u298813-sub7.your-storagebox.de/ubDistBuild/package_image.tar.xz">https://u298813-sub7.your-storagebox.de/ubDistBuild/package_image.tar.xz</a>
'


Installing some of these products correctly may require &#39;Run as Administrator&#39;, &#39;sudo&#39;, or similar.

__ Products - Developer __
_r '
<a href="https://xkcd.com/949/">
'
 '_picture' 'https://imgs.xkcd.com/comics/file_transfer.png' '240px'
_r '
</a>
'

Username   u298813-sub7
Password   wnEtWtT9UDyJiCGw

_r '
<a href="https://u298813-sub7.your-storagebox.de/">https://u298813-sub7.your-storagebox.de/</a>
'
 
_r '
<a href="https://github.com/soaringDistributions">https://github.com/soaringDistributions</a>
'
 
 
_r '
<a href="https://u298813-sub7.your-storagebox.de/mirage335TechArchive_discImages/">https://u298813-sub7.your-storagebox.de/mirage335TechArchive_discImages/</a>
'
 
 

https://u298813-sub7.your-storagebox.de/mirage335KernelBuild/linux-lts-amd64-debian.tar.gz

https://u298813-sub7.your-storagebox.de/mirage335KernelBuild/linux-mainline-amd64-debian.tar.gz
 

https://u298813-sub7.your-storagebox.de/ubcp/

https://u298813-sub7.your-storagebox.de/ubcp/package_ubiquitous_bash-msw-rotten.7z

https://u298813-sub7.your-storagebox.de/ubcp/package_ubcp-core.7z
 

https://github.com/soaringDistributions/ubDistBuild/raw/main/_lib/custom/package_kde.tar.xz

 '_page'PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak


__ Other __

Username   u298813-sub10
Password   OJgZTe0yNilixhRy

_r '
<a href="https://u298813-sub10.your-storagebox.de/">https://u298813-sub10.your-storagebox.de/</a>
'


Public files not officially at a &#39;release&#39; directory may be automatically generated, mostly for diagnostics. Usually, not expected useful for developer or end user. Completeness and notability may not be expected.

__ Usage __

Files may be downloaded from command-line.
[0;37;100m[0;34m rm package_image.tar.xz* ; wget --user u298813-sub7 --password wnEtWtT9UDyJiCGw &#39;https://bit.ly/ubDistBuildImg&#39; [0m[0m
[0;37;100m[0;34m rm package_image.tar.xz* ; axel -n 12 -H "Authorization: Basic "$(echo -n "u298813-sub7:wnEtWtT9UDyJiCGw" | openssl base64) &#39;https://u298813-sub7.your-storagebox.de/ubDistBuild/package_image.tar.xz&#39; [0m[0m


Please use &#39;wget&#39; . Beware &#39;axel&#39; is STRONGLY DISCOURAGED for shell scripts - may not be available, may overwhelm servers with parallel downloads, and may severely degrade network latency backoff algorithms.

___ ubDistBuild ___

May be written to disk. For servers, beware, cloud-init data source may not be configured, SSH may not be installed/enabled by default, SSH password login may be disabled, SSH public keys may not be installed/enabled, and &#39;rootGrab&#39; may be an undesired default.

[0;37;100m[0;34mapt-get update -y[0m
[0;37;100mapt-get install -y sudo gparted xinit[0m
[0;37;100mapt-get install -y x11vnc tigervnc-viewer[0m
[0;37;100mapt-get install -y tigervnc-*[0m
[0;37;100mapt-get install -y xz-utils[0m
[0;37;100mecho &#39;xterm -geometry +1+1 -n login -display :0&#39; > ~/.xinitrc[0m

[0;37;100mmkdir -p /mnt/temp[0m
[0;37;100mmount /dev/sda1 /mnt/temp[0m

[0;37;100mmkdir ./cloud.cfg.d[0m
[0;37;100mcp /mnt/temp/etc/cloud/cloud.cfg.d/*hetzner* ./cloud.cfg.d/[0m
[0;37;100mcp /mnt/temp/root/.ssh/authorized_keys ./[0m


[0;37;100mumount /mnt/temp[0m

[0;37;100mwget -qO- --user u298813-sub7 --password wnEtWtT9UDyJiCGw &#39;https://bit.ly/ubDistBuildImg&#39; | xz -d | tar -xv --occurrence ./vm.img -O | dd of=/dev/sda bs=1M status=progress[0m


[0;37;100mprintf "fix
" | parted ---pretend-input-tty /dev/sda print[0m
[0;37;100mparted -s -a opt /dev/sda "print free" "resizepart 5 100%" "print free"[0m
[0;37;100mmount /dev/sda5 /mnt/temp[0m
[0;37;100mdf -h /mnt/temp[0m
[0;37;100mbtrfs filesystem resize max /mnt/temp[0m
[0;37;100mdf -h /mnt/temp[0m

[0;37;100mmkdir -p /mnt/temp/etc/cloud/cloud.cfg.d[0m
[0;37;100mcp ./cloud.cfg.d/* /mnt/temp/etc/cloud/cloud.cfg.d/[0m
[0;37;100mcp ./authorized_keys  /mnt/temp/root/.ssh/authorized_keys[0m
[0;37;100mchmod ugoa-x /mnt/temp/root/_rootGrab.sh[0m

[0;37;100mumount /mnt/temp[0m

[0;37;100mstartx[0m
[0;37;100m# ...[0m
[0;37;100mvncf &lt;ip.addr&gt;[0m
[0;37;100m# ...[0m
[0;37;100msudo -n gparted [0m[0m

 '_page'PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak


__ Instructions (Similar Near Equivalent), Ingredients __

Soaring Distributions LLC products may include other products of Soaring Distributions LLC, or other information from others (eg. &#39;ubiquitous_bash&#39; by manager mirage335. Mostly, but not necessarily entirely, as briefly described here.

___ ubDistBuild ___

____ Instructions ____

Similar near equivalent usually installable within a dist/OS . Beware swap may be enabled by default (especially if <3GB RAM detected), and reboot may be necessary to enable all features as expected. Virtual Terminal (ie. &#39;chvt 2&#39; or &#39;Ctrl+Alt+F2&#39; if usable) or SSH session may be required, as the display manager (eg. sddm) may be stopped as necessary.
[0;37;100m[0;34mapt-get install -y sudo[0m
[0;37;100mapt-get install -y build-essential[0m
[0;37;100mapt-get install -y linux-headers-$(uname -r)[0m

[0;37;100mwget https://bit.ly/getNvSh[0m
[0;37;100mchmod u+x getNvSh[0m
[0;37;100m./getNvSh _install[0m

[0;37;100mwget https://bit.ly/rotInsSh[0m
[0;37;100mchmod u+x rotInsSh[0m
[0;37;100m./rotInsSh _custom_kernel[0m
[0;37;100m./rotInsSh _install_and_run[0m

[0;37;100m# optional[0m
[0;37;100m./rotInsSh _custom_core_drop[0m



[0;37;100m#_mustBeRoot[0m
[0;37;100m#cd /root[0m

[0;37;100mwget https://bit.ly/rootGrabSh[0m
[0;37;100mmv rootGrabSh _rootGrab.sh[0m
[0;37;100mchmod u+x _rootGrab.sh[0m
[0;37;100m./_rootGrab.sh _hook[0m
[0;37;100mecho > /regenerate_rootGrab[0m
[0;37;100m./_rootGrab.sh __grab_hook[0m



[0;37;100mecho > /regenerate[0m
[0;37;100mreboot [0m[0m



Cloud-Init scripts may exist to automatically effect similar near equivalent results on top of cloud providers (eg. Hetzner, Vultr, DigitalOcean, etc) dist/OS, custom, etc. Some may be specialized (eg. to quickly create a &#39;croc&#39; relay). Beware some cloud providers (eg. Azure) may significantly price bandwidth/usage.
 
_r '
<a href="https://github.com/mirage335/ubiquitous_bash/tree/master/_lib/kit/install/cloud/cloud-init/zRotten">https://github.com/mirage335/ubiquitous_bash/tree/master/_lib/kit/install/cloud/cloud-init/zRotten</a>
'

____ Ingredients ____

Image created with dd, parted, chroot, debootstrap, qemu, etc .
 
_r '
<a href="https://github.com/soaringDistributions/ubDistBuild/blob/main/_prog/core.sh#L119">https://github.com/soaringDistributions/ubDistBuild/blob/main/_prog/core.sh#L119</a>
'
 
_r '
<a href="https://github.com/mirage335/ubiquitous_bash/blob/master/virtualization/bios/createvm.sh">https://github.com/mirage335/ubiquitous_bash/blob/master/virtualization/bios/createvm.sh</a>
'
 
_r '
<a href="https://github.com/mirage335/ubiquitous_bash/blob/master/virtualization/bios/live.sh">https://github.com/mirage335/ubiquitous_bash/blob/master/virtualization/bios/live.sh</a>
'



Software installed by scripts.
 
_r '
<a href="https://github.com/mirage335/ubiquitous_bash/blob/master/_lib/kit/install/cloud/cloud-init/zRotten/zMinimal/rotten_install.sh#L872">https://github.com/mirage335/ubiquitous_bash/blob/master/_lib/kit/install/cloud/cloud-init/zRotten/zMinimal/rotten_install.sh#L872</a>
'
 
_r '
<a href="https://github.com/soaringDistributions/ubDistBuild/tree/main/_lib/setup/nvidia">https://github.com/soaringDistributions/ubDistBuild/tree/main/_lib/setup/nvidia</a>
'
 
_r '
<a href="https://github.com/soaringDistributions/ubDistBuild/tree/main/_lib/setup/rootGrab">https://github.com/soaringDistributions/ubDistBuild/tree/main/_lib/setup/rootGrab</a>
'

 '_page'PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak


__ Plain Text __
An essentially plain text copy of this document is normally available as &#39;README.sh.out.txt&#39; , generated by &#39;scriptedIllustrator&#39;.

Assistive technologies may be able to more usefully parse this.

__ Free/Libre and Open Source Software (FLOSS) __
Most if not all software from Soaring Distributions LLC is Free/Libre and Open Source Software.

Please see included software licenses.

Distributing individual files or pieces of files without other relevant information (ie. without corresponding source code) may not be possible.

Some software may be created by Soaring Distributions LLC manager, mirage335, for and on behalf of Soaring Distributions LLC.

__ Sponsoring __

Soaring Distributions LLC may not have much to give, but those who ease moving virtual machine disk images and such, or reduce to need to do so, are very greatly appreciated, and very relevant to the purpose of Soaring Distributions LLC as well as to users of its products. Soaring Distributions LLC normally regards such as charitable contributions that are expected to reduce its own risks from fewer than desired affordable (ie. $$$/GB transferred and $$$/GB stored) file transfer resources. Soaring Distributions LLC is also concerned about end-users having sufficiently usable file transfer resources for their own use and modification of products. Soaring Distributions LLC recoginzes it is part of a technology ecosystem, which must remain healthy.

_r '
<a href="https://github.com/orgs/soaringDistributions/sponsoring">https://github.com/orgs/soaringDistributions/sponsoring</a>
'


*) Croc ( https://github.com/schollz ) is especially appreciated for the ability to immediately transfer such things as shell scripts, installers, or maybe even occasional compressed VirtualMachine images.

 '_page'PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak


__ Script Consumers __
Some scripts may download products of Soaring Distributions LLC for internal use, developers, end users, etc. If public services of Soaring Distributions LLC change, adding such new upstream information may be necessary. Some of these may be known to and/or used by Soaring Distributions LLC internally.

*) ubiquitous_bash - ubiquitous_bash/_lib/kit/install/cloud/cloud-init/zRotten/zMinimal
*) https://github.com/soaringDistributions/ubDistFetch
*) https://github.com/soaringDistributions/ubDistBuild

__ Safety __
Pre-built disk images are a last resort, mostly for diagnostics with physical access and for embedded. If your cloud provider has &#39;cloud-init&#39; or similar, prefer that, instead of pre-built desktop/VM disk images.

Passwords, SSH identity, OpenSSL self-signed certificates, etc, may not be different for copies of pre-built images, in spite of some efforts by Soaring Distributions LLC to remove such. Change if this may be an issue (ie. if network login may be possible through SSH, CUPS, SAMBA, etc). Scripts (ie. &#39;rotten_install.sh&#39; by manager &#39;mirage335&#39;) may be able to set these randomly.

Passwords may be set randomly, to disable login except by autologin or cloud provider. Locking a desktop session (eg. with "Ctrl+Alt+L") may not be easily reversible.

Copy-On-Write nesting performance issues and log tree corruption issues with btrfs root filesystem, while expected not substantially consequential (ie. still on par with ext4), may be possible. At some risk, &#39; btrfs rescue zero-log /dev/sdX &#39; or similar may force continued booting of a btrfs filesystem with log tree corruption.

 '_page'PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak -H-H-H-H- PageBreak


__ NVIDIA __
Users of NVIDIA hardware may require an internet connection or similar convenience to download software, may have to run software theirselves, and by running that software, may create resulting software that is not distributable. Whether any recent announcements of supposed offical open-source NVIDIA kernel drivers may result in distributable relevant software may not be yet known.


A syscall exception may be what allows distribution of NVIDIA proprietary binary Linux modules at all. Or, so long as NVIDIA can dubiously claim their proprietary binary driver for Linux may not be a derived work of a GPLv2 licensed Linux kernel, NVIDIA may argue that an &#39;attempt otherwise to&#39; &#39;sublicense&#39; the Linux kernel has not occurred, and thus NVIDIA may claim their rights did not yet &#39;automatically terminate&#39;. Supplementing that, NVIDIA may claim the structure of their proprietary binary driver for Linux makes only the compiled combination of Linux kernel, &#39;glue layer&#39;, and proprietary binary blob a derived work of Linux and not distributable.

A United States court might usefully settle this continuing derived work GPLv2 copyright issue, which apparently has not been raised as of 2022.

Apparent absence of distribution of LiveCD/LiveUSB images with NVIDIA drivers precompiled is strong evidence of a consensus demonstrating obviousness the compiled combination of Linux kernel, &#39;glue layer&#39;, and proprietary binary blob, is definitely a derived work of Linux and is definitely NOT distributable.


Meanwhile, Soaring Distributions LLC attempts to at least follow best usual (eg. commercial) practices, or better.

Soaring Distributions LLC is at least reluctant if not unwilling to itself distribute software which includes what may be found derived works that create binary Linux kernel modules. Soaring Distributions LLC does NOT expect to ever have itself distributed a compiled combination of Linux kernel, &#39;glue layer&#39;, proprietary binary blob, etc.

COMPLAINTS should NOT be directed to Soaring Distributions LLC. Neither Soaring Distributions LLC nor manager mirage335, caused or intended to cause, any &#39;attempt otherwise to&#39; &#39;sublicense&#39; the Linux kernel. Instead, send such complaints to responsible parties who may have made the &#39;attempt otherwise to&#39; &#39;sublicense&#39; the Linux kernel in violation of the GPLv2 copyright license, or may have knowingly caused others to do so (eg. at least NVIDIA, complicit distributors including Debian, Ubuntu, OEMs, etc).

To the extent legally possible, Soaring Distributions LLC should be reasonably expected to publish, and specifically make relevant third-parties aware of, any such notices.


Soaring Distributions LLC may not yet on its own have sufficient information, understanding, knowledge of precedent, or representation, to prove, but does not discount, that responsible parties (eg. at least NVIDIA, complicit distributors including Debian, Ubuntu, OEMs, etc) committed or knowingly caused coercive, flagrant, willful, commercially gainful to the extent of many years and multiple billions of dollars, violation of the GPLv2 copyright license of the Linux kernel. Soaring Distributions LLC however, far downstream of those originating distributors, itself benefiting from and using the protections of GPL/AGPL copyright license, having no expected interest in weakening those protections, is at most a victim, not in any way a knowing cause of GPLv2 copyright violation.


If Soaring Distributions LLC distributes software which users may run to receive and run software from third-party distributors, which may create not distributable software, and if this is perceived as some issue, any &#39;cease-and-desist&#39; should then in that case be sent directly to relevant third-party distributors (ie. NVIDIA, Debian, Ubuntu, OEMs, etc), NOT to Soaring Distributions LLC itself.

__ Reference __
https://en.wikipedia.org/wiki/Series_of_tubes

https://xkcd.com/949/
	&#39;I like how we&#39;ve had the internet for decades, yet &quot;sending files&quot; is something early adopters are still figuring out how to do.&#39;
		Still very much an issue in 2022. Is there really a good reason for that?

https://xkcd.com/license.html
	&#39;Creative Commons Attribution-NonCommercial 2.5 License.&#39;

https://github.com/dutchcoders/transfer.sh/issues/181
	Apparently the limit was reduced from unlimited, to 10GB, to 1GB, to <<1GB, specifically to prevent &quot;sending files&quot; . Does the absence of such basic internet functionality for developers really benefit anyone?

https://github.com/schollz/croc/issues/437
	&#39;Croc freezes/stalls during large file transfer&#39;

https://github.com/schollz/croc/issues/453



http://ipw2100.sourceforge.net/firmware_faq.php


https://en.wikipedia.org/wiki/Open_source_license_litigation
https://slashdot.org/story/06/05/14/2059242/kororaa-accused-of-violating-gpl
	&#39;When someone takes that same compiled glue plus binary module and distributes them, they&#39;re distributing a derived work of Linux, without complying with the terms of the GPL, and therefore without permission to distribute under copyright law. &#39;

https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
https://www.quora.com/Are-lifetime-contracts-legal
	&#39;lifetime contracts&#39; &#39;unconscionable&#39;

https://en.wikipedia.org/wiki/Free_and_open-source_graphics_device_driver#ATI_and_AMD
https://en.wikipedia.org/wiki/GNU_General_Public_License#Linking_and_derived_works
https://tldp.org/HOWTO/Module-HOWTO/copyright.html
https://arstechnica.com/information-technology/2006/12/8428/

https://gitweb.gentoo.org/repo/gentoo.git/tree/x11-drivers/nvidia-drivers/nvidia-drivers-510.60.02.ebuild
http://gpo.zugaina.org/AJAX/Ebuild/53561524/View
	&#39;SRC_URI&#39; &#39;https://us.download.nvidia.com/XFree86/Linux-x86_64/${PV}/NVIDIA-Linux-x86_64-${PV}.run&#39;
		ie. https://us.download.nvidia.com/XFree86/Linux-x86_64/510.60.02/NVIDIA-Linux-x86_64-510.60.02.run

https://wiki.gentoo.org/wiki/NVIDIA/nvidia-drivers
	&#39;wrapper functions that will compile against the Linux kernel&#39;

https://opensource.stackexchange.com/questions/1477/do-i-have-to-disclose-the-source-code-of-a-linux-driver-i-have-not-developed
	&#39;But, if the driver doesn&#39;t directly link to the kernel, that may not apply. I remember in the past some graphics drivers (I think NVidia, but aren&#39;t sure) had two parts. One GPL-part included in the kernel and offering an interface for the second part, that was proprietary. I don&#39;t know how legally stable this construct is, but it may work.&#39;

https://www.kernel.org/doc/html/latest/process/license-rules.html
	&#39;GPL-2.0, with an explicit syscall exception&#39;

https://www.nvidia.com/en-us/drivers/geforce-license/
	&#39;Linux/FreeBSD Exception. Notwithstanding the foregoing terms of Section 2.1.1, SOFTWARE designed exclusively for use on the Linux or FreeBSD operating systems, or other operating systems derived from the source code to these operating systems, may be copied and redistributed, provided that the binary files thereof are not modified in any way (except for unzipping of compressed files).&#39;

https://packages.debian.org/es/bullseye/firmware-ipw2x00
https://packages.debian.org/es/bullseye/arm/firmware-ivtv



https://unix.stackexchange.com/questions/61461/how-to-extract-specific-files-from-tar-gz
https://superuser.com/questions/655739/extract-single-file-from-huge-tgz-file
https://serverfault.com/questions/870594/resize-partition-to-maximum-using-parted-in-non-interactive-mode
https://www.thegeekdiary.com/how-to-resize-expand-a-btrfs-volume-filesystem/

https://stackoverflow.com/questions/57496500/how-to-script-automatic-task-with-parted-update-gpt-table

__ Copyright __

This file is part of site_distLLC

site_distLLC is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

site_distLLC is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with site_distLLC  If not, see &lt;http://www.gnu.org/licenses/&gt;.



