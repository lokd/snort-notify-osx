Snort Messages in Notification Center
=====================================

`snort-notify` is a simple Mac OS X bash script that monitors a [Snort](https://snort.org/) log file and displays a notification when a new alert is detected.

# Installation

Copy the `snort-notify` script into `/usr/local/bin` and `io.lokd.snort-notify.plist` into your `Library/LaunchAgents/` folder in your home directory, then log off and log in again or reboot to start it.

The script assumes that your Snort alert log is in `/var/log/snort/alert`.

You will have to adjust the `LOGFILE` setting in the script if it is somewhere else.

# License

Copyright © 2015 BeyondVision & Huy Hoang Nguyen.  
Code licensed under [GPLv3](LICENSE).  
Documentation licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

# Contact

[@lokdnet on Twitter](https://twitter.com/lokdnet/)
