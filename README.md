sublime-text-utils
==================

Utilities for Sublime(right now just copying the file path from the root of the current project)

Current commands
  - Copy file path from root of current sublime project.
  - Copy [Testify](https://github.com/Yelp/Testify) command for the current file(based on the root path). Highlight test class to run the specific test.
  - Copy import statement for current file("from dotted.file.name.from.root import "). Highlight something to specifically import it.
  - Copy dotted path for current file.
  - Copy path for js-tester(Mocha utility) of current js file
  - Open list of files from clipboard

Installation

NOTE: You may have to cd into your "Sublime Text 2" directory, instead of "Sublime Text 3" depending on your version.

OS X:

`$ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/ && git clone git://github.com/anthonymayer/sublime-text-utils`

Ubuntu:

`$ cd ~/.config/sublime-text-3/Packages && git clone git://github.com/anthonymayer/sublime-text-utils`
