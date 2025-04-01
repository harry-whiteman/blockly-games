![Blockly Games](https://raw.githubusercontent.com/wiki/google/blockly-games/title.png)

Google's Blockly Games is a series of educational games that teach programming.
It is based on the [Blockly](https://developers.google.com/blockly/) library.
All code is free and open source.

**The games are available at https://blockly.games/**

**The developer's site is at https://github.com/google/blockly-games/wiki**

To build and run:
- Run `make deps` to install dependencies
- Install any python/java etc that required to install the dependences
- Run `make games` to build the games
- Run `cd appengine && python3 -m http.server 8000` to start the local server
- Go to http://localhost:8000/admin.html and select `Use slow compressed mode` to allow for local code changes (still needs refresh).
- Go to http://localhost:8000/maze.html to play the game
