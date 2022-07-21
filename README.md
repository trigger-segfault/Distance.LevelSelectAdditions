# Distance Level Select Additions

Distance mod that extends the level selection UI by adding more options.

## Current Features

* Playlist Options menu (`MenuStart` button).
	* Change Display Name
	* Change Display Color
	* Rename Playlist File
	* Delete Playlist File
* Saving a playlist no longer overwrites its display name with the file name. Instead, the display name can be changed with the *Name* button when in Playlist Mode.
* Remember the last-accessed level set/playlist, so that the game will return to your original place after playing a level appearing in multiple playlists.
* Fix scrolling bug in Advanced level select menu where you could only scroll to the very top or bottom entry.

## Current Options

* Exclude levels in personal playlists from the Workshop Level Set.
* Remove or change the limit to levels in the Workshop Level Set (original limit was 100).
* Apply up to 3 layers of sorting to the Workshop Level Set (each method can be reversed).
    * Recently Downloaded (default)
	* Level Name
	* Author Name
	* Difficulty
	* Finish Status
	* Medals Earned
* Show hidden sprint campaign level sets.
* Enable or disable the Playlist Options menu.
* Allow creating playlists when Choosing Main Menu levels.
* Make the *Visit Workshop page* button visible in the Advanced level select menu when Choosing Main Menu levels.
* Re-introduce the *Rate this level* button in the Advanced level select menu.
* Hide unused buttons that appear in the Advanced level select menu when Choosing Main Menu levels.

## Known Bugs

* The Quick Playlist label can sometimes keep the last-used name.
* The file name for the Save Quick Playlist prompt will also sometimes keep the last-used name.

