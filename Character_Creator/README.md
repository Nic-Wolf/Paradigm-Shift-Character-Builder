# Character Creator


By [Nic Wolf](https://github.com/Nic-Wolf).


## Description
**Character_Creator.html** as it's name implies, is an interface for creating a character in [Paradigm Shift](http://redskygames.net). Math can be hard sometimes, and for new players, this really cuts down the time it takes to get their characters ready.


## Configuration & Usage

Everything you need is right there in the file. simply open it in a browser, and start building your new character!


## Contributing

**First Off**, Please ask me first if you wish to contribute to this project. Also, please credit me if you decide to use this elsewhere. It took a lot of time to get all this figured out!

Other than that, feel free to use as you so desire!


## Update Notes
*********************************************************
**4/20/14**
- Added racial descriptions
- Added tooltips for Stats

*********************************************************
**3/30/14**
Everything is finally operational! It's not complete, but the main functionality works without error, so I'm officially calling this release the 1.0 version.

As a note to myself, I'd like to see the stat points maintain their used values, so the classes and races can be evaluated by the players on the fly, but that's apparenly WAAAAY more work than I first thought.

- Fixed bug where roll mod wouldn't update on class change. Now resets like everything else.
- Fixed bug where font color for the stat values weren't updating or changing appropriately.
- Fixed emerging bug where stat minus buttons weren't working after a value was greater than 10

*********************************************************
**3/20/14**
- Added data structures for races and classes
- refactored arithmetic and logic
- Added roll modifiers
- Added changable number coloration for minimum stats

**KNOWN BUGS:** 
- Roll mod doesn't reset with class change, which is fine, but the current setup has all stats resetting.
	ideally, only the class stats reset, and not everything else.
- only DEX and AGI stat buttons work with color change
- btnMinusStat doesn't lower value if greater than 9 ??? $%!#$*!

*********************************************************
**3/15/14**
- Updated HTML
- Added CSS
- Fixed plus/minus buttons (i think)

*********************************************************
**3/12/14**
- Added stat point pool
- level-up system now (mostly) error free
- Added plus/ minus buttons to add from the stat point pool to each individual stat... has errors

*********************************************************
**3/09/14**
- Added racial bonuses
- Added class bonuses
- Added level-up system... has errors
- Created HTML markup... needs reorganization
