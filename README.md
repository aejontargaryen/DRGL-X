![The Long Night Is Coming](https://raw.githubusercontent.com/ZirtysPerzys/DRGL-X/master/12164.png)

# DRGL Blockchain & logo/images

First time users can now download this file for faster sync times or more importantly for any issues regarding initial blockchain syncing.
Some users have reported issues syncing getting stuck at block 63312 -As we enforced a "mixin" limit (18) for transactions in a recent upgrade release, we found out this early network block contains a transaction with a mixin-count of 101....yes thats one hundred and one..  certainly a private transaction ;)   

Even still, most CLI versions are able to sync beyond it without any problem.

However some GUI wallet nodes hang at this block during their maiden chain sync..If this scenario is upon you- or if for only reasons of speed / convenience - use [this download of the DRGL blockchain...](https://github.com/ZirtysPerzys/DRGL-X/releases)

---------------------------
### To bootstrap blockchain:
Just extract the contents of this folder into your .dragonglass folder- a 'hidden' folder in your user home base directory.  
(Access hidden files and folders by pressing "Alt + h" )

For Windows users the location will be C:\Users\USERNAME\AppData\Roaming\dragonglass
