sync_family
===========
Scripts for syncing tor family information across multiple relays

Dependencies
------------
```
apt-get install wget inotify-tools 
```

Running
-------
* git clone https://github.com/coldhakca/sync_family.git 
* Install crontab
* Replace path in crontab with the path to the sync_family directory
* Replace URL in crontab with the URL containing your clearsigned MyFamily line
* Replace dummy GnuPG fingerprint in sync_family with the fingerprint(s) of the key used to sign the MyFamily file
* Run check_family in screen/tmux

Important Notice
-----------------
This has had limited testing. If it breaks, you get to keep the pieces.

