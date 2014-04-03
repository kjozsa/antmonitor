antmonitor
==========

A generic web app (aka Chrome packaged app/Windows Store app) that listen to ANT+ broadcasts from sensors (e.g heart rate) with visualization in a chart

Open for non-commercial/personal use : https://creativecommons.org/licenses/by-nc-nd/3.0/

Ubuntu 13.10 or later:

    * Listing of processes that owns USB devices
        'sudo lsof +D /dev/bus/usb'

    * suunto kernel driver attaches automatically to ANT USB in latest linux kernels
        fixed by blacklisting it in /etc/modprobe.d/blacklist.conf, or dynamically by 'sudo rmmod suunto'

Tested platforms:

    Ubuntu 13.10 - Linux kernel 3.11.0-19-generic
    Chrome (unstable) v 35.0.1916.6 dev aura/Chrome v. 33
