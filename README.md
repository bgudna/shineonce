# shineonce
Interactive fiction development using Inform v6.
To be compiled with i6 and run on vintage (or emulated) micro-computers from the 80's.

## Steps
1. Get the latest source for Inform6 (https://github.com/DavidKinder/Inform6) and compile. Place the binary in
   your PATH.
2. Get the latest source for the PunyInform library (https://github.com/johanberntsson/PunyInform) - (clone this into "code/other/")
3. Compile the game with the example below:
```
inform -v3 +../other/PunyInform/lib game.inf
```
4. Test/Run the game with Frotz.


## TODO
 - [x] set up project scaffolding
 - [x] set up build scripts
 - [ ] come up with scenarios
 - [ ] improve structure
 - [ ] add storyline
