## PoC that fixes two GTA Online bugs and drastically improves load times for CPU-bound systems

Original work by tostercx, massive thanks to them

All addresses are found at run time so that it works on all platforms

While chances are low, modifying your game while in online mode might get your account suspended, use at your own risk!

Inject the dll found in [releases](https://github.com/QuickNET-Tech/GTAO_Booster_PoC/releases) with a DLL injector of your choice and then just head online
NOTE : You can inject whenever you want as long as GTA5.exe is running and before you've started to head online

## How to

* `git clone --recurse-submodules https://github.com/QuickNET-Tech/GTAO_Booster_PoC`
* build the project with MSVC
* inject the DLL with your favorite injector while the game is starting up

or

* in visual studio start a new project and provide a link to this repository

## More details

[Writeup](https://nee.lv/2021/02/28/How-I-cut-GTA-Online-loading-times-by-70/)
