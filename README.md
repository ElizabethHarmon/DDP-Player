# DDP-Player
Simple CLI tool to play DDP files in Linux.  

Requirements: ddpinfo from http://ddp.andreasruge.de/ 

Usage: 
```shell
playddp [ddpfolder] [tracknumber]
```
For example:
```shell
playddp audio/ddp/BachCD 5 
```
This will find the .DAT file in the BachCD DDP folder and begin at track 5. Without a track number supplied, the script will simply start playback at the beginning of the file.

Acknowledgements: Thanks to Andreas Ruge for the Sox play syntax for supplying bit-rate etc. 
