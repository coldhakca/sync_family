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
1. git clone https://github.com/coldhakca/sync_family.git 
2. Install crontab
	*  Replace path in crontab with path to the sync_family directory
	*  Replace URL in crontab with the URL containing your clearsigned MyFamily line
3. Replace dummy GnuPG fingerprint in sync_family with the fingerprint(s) of the key used to sign the MyFamily file
4. Run check_family in screen/tmux

Important Notice
-----------------
This has had limited testing. If it breaks, you get to keep the pieces.

