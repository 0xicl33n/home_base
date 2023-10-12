About this fork:

why bother randomizing the mac if youre connecting to your home network? that means it gets a new ip each time and cant get a static ip. seems like unnecessary extra steps that probably are the reason it messes up half the time, so i removed the randomize mac step.




Connects to the network specified in the config whenever it is within range by pausing the Bettercap recon. Once out of range of the specified home network, Bettercap recon is restarted.

## Dependencies
```
apt update; apt install nmap
```
