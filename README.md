```
                          _        ___  ___
 ___  ___ _ _  ___  ___ _| |_ _ _ | | '| | '
/ . \<_-<| | ||___|<_-<  | | | | || |- | |-
\___//__/`___|     /__/  |_| `___||_|  |_|

  ▓▓▓▓▓▓▓▓▓▓
 ░▓ about  ▓ script I made for osu!
 ░▓ author ▓ yurisuki <yurisuki@waifu.club>
 ░▓▓▓▓▓▓▓▓▓▓
 ░░░░░░░░░░
```

## table of contents
 - [introduction](#introduction)
 - [what does it include?](#what-does-it-include)
 - [installation](#installation)

# introduction
Shell scripts I made for osu! and I use these on Linux.

# what does it include?
| FILE      	| LANGUAGE 	| DESCRIPTION                                                                                         	| DEPENDENCIES 	|
|-----------	|----------	|-----------------------------------------------------------------------------------------------------	|--------------	|
| osu       	| shell    	| This script runs osu! using 'lutris' and kills 'lutris' after osu! is opened.                       	| lutris       	|
| osu.png   	| png      	| osu! logo                                                                                           	| -            	|
| osuauto   	| shell    	| This script will download beatmaps from given link.                                                 	| curl, xclip  	|
| osumove   	| shell    	| This script moves all maps in ~/Downloads to osu! songs directory.                                  	| -            	|
| osu-i     	| shell    	| This script will clone osu-stuff repo and export it to the path.                                    	| git          	|
| osudir    	| shell    	| This file includes your osu! directory used by scripts.                                             	| -            	|
| osunew    	| shell    	| This script will download about ~40 new ranked maps.                                                	| curl         	|
| osusearch 	| shell    	| Gives a dmenu prompt to search osu.ppy.sh for downloading map. Without input, will open osu.ppy.sh. 	| dmenu, curl  	|

## installation
Install this script using:
```shell
curl https://raw.githubusercontent.com/yurisuki/osu-stuff/master/osu-i | bash
```
Or install [osu-install](https://github.com/yurisuki/osu-install) (it installs this script automatically)
