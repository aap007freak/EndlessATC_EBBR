# Brussels Airport For Endless ATC
This is a file to add EBBR (Brussels Airport) to the [Endless ATC](https://steamcommunity.com/app/666610) game.
## Installation
### Steam
* Download EBBR.txt
* Put it in `Steam/steamapps/common/endless ATC/locations` 
### Android
* Download EBBR.txt
* Put it in `Android/data/com.dirgtrats.endlessatc/files`
## Features
### Implemented
* Arrivals and departures at EBBR
* (Semi-)Realistic arrival- and departure paths
### Planned
* Multiple runway configurations. (right now only the westerly config (25's) is working).
* Secondary airports: EBCI, EBAW
* Realistic airspace
* Realistic airline schedules. The variety of airlines is quite limited at this time.
## Issues
Endless ATC is a **simple** game. Compromises were made to make the game as realistic and as playable as possible.
* Arrivals call at FL80 everywhere, instead of FL60 at FLO, FL110 at KERKY, etc. this is a limitation of the game, that can't be fixed. 
* Departures need to be climbed higher than FL70. This is (afaik) a bug in the game, and should be fixed soon.
* When reaching higher skill levels, arrivals spawn really close to eachother and clog up the airspace around ANT and FLO. In Endless ATC, there is no "radar controller" that sequences the arrivals before entering you airspace. This is how the game is coded.

Notice other bugs or issues? Please open an issue on [issue on github](https://github.com/aap007freak/EndlessATC_EBBR/issues).
## Credits
All coordinates and other information with respect to EBBR where directly taken from the [eAIP](https://ops.skeyes.be/html/belgocontrol_static/eaip/eAIP_Main/html/index-en-GB.html).
