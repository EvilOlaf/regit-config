Old configs from fork  
`config-3.19-vbox` - untested  
`config-3.5-vbox` - untested  
`config-3.5-vbox-no-netfilter` - untested  


Ubuntu linux source has been used. Install it from `linux-source-4.15.0` package.  
`linux-4.15.x-desktop.config` - tested with Linuxmint, working decent  
`linux-4.15.x-server.config` - booting, nothing else tested   



`linux-4.19-x-desktop.config` - ~~Virtualbox guest additions broken~~ Build fix: https://forums.gentoo.org/viewtopic-p-8276934.html#8276934 The build process has probably been fixed in Virtualbox release 5.1.22


Current linux built from 4.19.1 working decent inside Virtualbox and booting quite fast out of the box. So speed is not a benefit from having a custom kernel.  
http://kernel.ubuntu.com/~kernel-ppa/mainline/v4.19.1/
