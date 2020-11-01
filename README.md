# Anki Flashcard Setup

HTML/CSS code used to generate my Anki setup.

## Demo

This shows how the keywords can be highlighted by italicising the text in the editor and important text can be emphasised by making it bold. 

![Basic view](https://github.com/PuneetMatharu/AnkiSetup/blob/main/images/demo_basic.png)

The highlighting colour is set to the trim of the card itself.

![Bold coloured](https://github.com/PuneetMatharu/AnkiSetup/blob/main/images/demo_bold_coloured.png)

Text in the terminal can be rendered by placing text in the fields associated with the terminal (see Instructions below). To make text look like a comment (i.e. grey) underline it in the editor and, to make text in the terminal red, italicise it.

![Double terminal](https://github.com/PuneetMatharu/AnkiSetup/blob/main/images/demo_double_terminal.png)

## Front/Back/Styling

The front, back and CSS can be found [here](https://github.com/PuneetMatharu/AnkiSetup/blob/main/styles/light_mode_front.html), [here](https://github.com/PuneetMatharu/AnkiSetup/blob/main/styles/light_mode_back.html) and [here](https://github.com/PuneetMatharu/AnkiSetup/blob/main/styles/light_mode_style.css), respectively.

## Syntax highlighting

For syntax highlighting I used the [Syntax Highlighting FORK (night mode fix, gui config, etc.)](https://ankiweb.net/shared/info/1972239816) add-on. 

The styling for my version of Monokai can be found [here](_styles_for_syntax_highlighting.css). I have updated the styling so that long comments do not automatically go off the card/page, and instead wrap onto the next line. 

## Instructions

To see the terminal shown in the screenshots above, you need to do the following three things:
1. Edit the card fields so that they are called **Question**, **Terminal (Question)**, **Answer**, and **Terminal (Answer)**;
1. Go to the config for the 
For syntax highlighting I used the [Syntax Highlighting FORK (night mode fix, gui config, etc.)](https://ankiweb.net/shared/info/1972239816) add-on and click "Select Templates to update" and click "Yes". This will allow you to provide your own customised styling for the syntax highlighting, and;
1. Copy the image [here](https://github.com/PuneetMatharu/AnkiSetup/tree/main/images/terminal-bar.png) and the syntax highlighting CSS [here](_styles_for_syntax_highlighting.css) into your `collection.media/` folder.
