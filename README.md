# toys

A directory holding small javascript webapps within single html files.

* [15-puzzle.html](http://dmolinarius.github.io/toys/15-puzzle.html) - An application to play 15-puzzle

  Click on 'randomize' to shuffle cells.
  Click on 'Show / Hide ids' to toggle cell number display.
  Select a local image to use as a background (warning big images may considerably slow down your browser).
  Play by clicking on an empty cell neighbour to move it.

* [crossword.html](http://dmolinarius.github.io/toys/crossword.html) - Create and solve crosswords. Save your creations, and solutions, even if partially completed !

  "load" button allows to load a crossword json file from your disk or network, with a puzzle to solve.
  Some of them are available in the data/crossword directory (in french, sorry for that).
  Use "save" button to generate a json crossword file from your work.

  In solve mode, definitions popup while hovering cells.
    Clicking a cell allows to enter text. Clicking twice toggles between horizontal and vertical text.
    Also supported are backspace, delete, and arrow keys.
    "print" button adds definitions below visible viewport (scroll to see them),
      allowing to print puzzle including definitions using your browser print facility.
    "check" button compares the text you filled-in to solution, and highlights errors in red.

  You may also reload the html file with hashtag #create to enter create mode.
  In create mode, arrow buttons in the corners of the board allow adding more lines or columns.
    The space key creates a black cell.
    "new" button starts from scratch (beware : no safeguard unless you saved previous edits). 
    Once puzzle fully created, "lock" button enters solve mode. Use "lock" before "save" to create a json file. For now, the definitions need to be entered manually, using your favorite editor, and that's it ! Your may now load your file to solve the puzzle.  
  

* [css-properties.html](http://dmolinarius.github.io/toys/css-properties.html) - Interactively play with an HTML span element CSS properties

  Update properties at will, and export obtained CSS or locally save work in a JSON file. Work may be retrieved by reloading the JSON file. Try for example to load
[parents.json](http://dmolinarius.github.io/demofiles/toys/parents.json),
[caesar.json](http://dmolinarius.github.io/demofiles/toys/caesar.json), or
[pioupiou.json](http://dmolinarius.github.io/demofiles/toys/pioupiou.json). (last example background image is based on
[Erithacus_rubecula_with_cocked_head.jpg](https://commons.wikimedia.org/wiki/File:Erithacus_rubecula_with_cocked_head.jpg) with © Francis C. Franklin / CC-BY-SA-3.0)

* [multiball.html](http://dmolinarius.github.io/toys/multiball.html) - Yet another application to throw balls on obstacles.

  Click an drag to shoot, then release mouse button to fire. Warning : addictive.

* [radar.html](http://dmolinarius.github.io/toys/radar.html) - An application to draw radar graphs based on angularjs and SVG.

  Click on labels to modify the text, and drag labels around.
  Click on graph nodes to draw the graph.
  A graph can be saved on - and retrieved from - your local disk,
  and exported in SVG format.
  Just play with it and have fun !
  
* [telecran.html](http://dmolinarius.github.io/toys/telecran.html) - A toy popular in the sixties.

  Known as [télécran](https://fr.wikipedia.org/wiki/%C3%89cran_magique) in french or [Etch A Sketch](https://en.wikipedia.org/wiki/Etch_A_Sketch) in english.
  Draw using keypad arrows, or by clicking on the left (up/down) or right (left/right) black buttons.
  To erase, turn it upside down and shake. Sorry, I'm joking. Please click on label.
