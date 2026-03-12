i have remote access to a server whitout active power management and when i want to shut down the server someone needs to push a button to shut it down completely... i keep shutting it down remotely whitout realizing this.
this is my solution; a bash script asks me if i really want to shut the server down and reminds me that someone needs to push a button too.

+--------------------------------------------------------------------+
| use the following aliases:                                         |
| alias sudo="sudo "                                                 |
| alias shutdown="/home/user1/shutdownconfirm.sh /usr/sbin/shutdown" |
+--------------------------------------------------------------------+
