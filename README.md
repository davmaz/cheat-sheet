cheat-sheet
===========

Python PyQt cheat sheet program
This is a trivial program, but I wanted something I could add python information to for 'reminders'.
It uses _info files that are loaded when the corresponding button in pressed in the PyQt gui.
For example, the gui right now (easiest version) puts up buttons for, say, Lists.
When I press the Lists button, the program opens a lists_info file (in the same directory) and 
appends the contents to a browser window below the buttons. This browser window is appended to as each button is pressed. There is a search lineedit box that will search for a word in the browser. It will cycle through all the occurences of the word and wrap around to the beginning. A clear button clears out the contents of the browser window.

