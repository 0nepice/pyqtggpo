#Version 0.13
- support custom challenge sound

#Version 0.12
- support filter when picking savestates

#Version 0.11
- option to show timestamp in chat

#Version 0.10
- fix alpha3 rom issue
- auto announce the game that you're playing in unsupported room when new player joins the room
- Remember select save state dialog windows size

#Version 0.09
- display game title etc info when selecting unsupported game savestates
- support cli command `/incoming` to list all challengers

#Version 0.08
- Option to show country flags in chat
- Allow double click on player names to challenge/cancel/spectate
- Show Ping and Country for incoming challenge
- Remove challenge/decline table column

#Version 0.07
- Add smooth networking settings like in official client
- Add a custom scheme url for accept decline challenge.
- Support custom emoticons
- Use green color for links

#Version 0.06
- Support recall chat history with up and down arrow keys
- Fix emoticon button size issue

#Version 0.05
- auto check for savestate changes when you join unsupported game channel

#Version 0.04
- Unsupported game room - Add rom prefix in chat
- More themes and Custom Qt Stylesheet

### Sample stylesheets
[mame ui](http://qmc2.arcadehits.net/wordpress/style-sheets/)
[dark orange](http://tech-artists.org/forum/showthread.php?2359-Release-Qt-dark-orange-stylesheet)
[xp](http://newsgroup.xnview.com/viewtopic.php?t=16181)

### QT stylesheet reference
[reference](http://qt-project.org/doc/qt-4.8/stylesheet-reference.html)
[examples](http://qt-project.org/doc/qt-4.8/stylesheet-examples.html)


## Fixes
- fixes error when someone who challenged you left the room

#Version 0.03
- Support a database of ggpo unsupported game save states in the `Unsupported Games` room
- Keyboard shortcuts for resizing splitter
- Embedded command line interface as chat commands<br/>
Type `/help` to see a list of commands available

    /away - away from keyboard
    /back - become available to play
    /accept [name] - accept incoming challenge
    /decline [name] - decline incoming challenge
    /challenge [name] - challenge player
    /cancel - cancel outgoing challenge
    /watch [name] - spectate a game
    /ignore [name] - ignore a player
    /unignore [name] - unignore a player
    /motd - clear screen and show message of the day
    /help - display help menu

## Fixes
- fixes send / receive challenge in 3s and kof rooms
- disable login button while waiting for response from ggpo.net

#Version 0.02
- Packaged app bundle for OSX and windows

#Version 0.01
Initial alpha source code release
- Support dark theme to reduce eye strain
- Autocomplete in chat
- More accurate GeoIP info
- Simple emoticons support
