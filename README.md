# DDP-Player
Simple CLI tool to play DDP files in Linux.  

Requirements: ddpinfo from http://ddp.andreasruge.de/

Usage: 
```shell
playddp [ddpfolder] [tracknumber]
```
It uses ddpinfo to figure out track start times from the supplied track number as necessary otherwise it simply begins playback at 0:00. The basic play command was suggested by Andreas Ruge in a forum and I adapted it to play any .DAT file contained within the folder (given that it doesn’t necessarily need to be named the default IMAGE.DAT) as well as starting from a particular track without needing to know the start time. 
