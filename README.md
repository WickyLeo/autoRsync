# autoRsync
Auto Deploy local Source to Remote Server by Increase.

## Use
 Need install fswatch & rsync first:
 
``` 
 	brew install fswatch
 	brew install rsync
```

ignore.txt record the folder list dont't need sync.

add the script to /usr/local/bin:

```
   ln -s auto-depoy /usr/local/bin/
```
run like this:

```
	auto-deploy LOCAL_PATH REMOTE_ADDR
``` 
