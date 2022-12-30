# README #

This is a simple bash script to mount ntfs external drives on Mac Os.   
Once mounted, both **R & W** are allowed.   
Device will be mounted under /Volumes/\[volume_name\]

**volume_name** is referred to the name Mac Os assigns to the external drive when it's automatically mounted.   

## Mounting ##

    sudo mnt_ntfs [volume_name] 

## Unmounting ##

You can just use the **umount** tool.   

    sudo umount /Volumes/[volume_name]
