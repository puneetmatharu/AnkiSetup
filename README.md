# Anki Flashcard Setup

HTML/CSS code used to generate my Anki setup.

## Demo

Make the text bold in the Anki editor to get coloured bold text. Underline code to make text coloured, bold, and underlined. The highlighting colour is set to the trim of the card.

![Bold coloured](https://github.com/PuneetMatharu/AnkiSetup/blob/main/images/demo_fill_in_the_blank_template.png)

Italicising text to generate inline code, and write code in the "Terminal" fields to display blocks of code in a mini-Terminal (see Instructions below).

![Terminal and inline code](https://github.com/PuneetMatharu/AnkiSetup/blob/main/images/demo_terminal_and_inline_code.png)

Italicise text in the Terminal field to make it stand out -- useful for highlighting errors in code.

![Terminal with errors](https://github.com/PuneetMatharu/AnkiSetup/blob/main/images/demo_double_terminal_with_errors.png)

## Front/Back/Styling

The front, back and CSS can be found [here](https://github.com/PuneetMatharu/AnkiSetup/blob/main/styles/light_mode_front.html), [here](https://github.com/PuneetMatharu/AnkiSetup/blob/main/styles/light_mode_back.html) and [here](https://github.com/PuneetMatharu/AnkiSetup/blob/main/styles/light_mode_style.css), respectively. The fonts used by the CSS file are stored [here](https://github.com/PuneetMatharu/AnkiSetup/blob/main/fonts).

Note: fonts can also be incorporated by adding a `<head>` block in the front and back cards and inserting a link to the relevant font family but this does not work without an internet connection. To allow offline use, the fonts have been downloaded.

## Enabling syntax highlighting

For syntax highlighting I used the [Syntax Highlighting FORK (night mode fix, gui config, etc.)](https://ankiweb.net/shared/info/1972239816) add-on.

The styling for my version of Monokai can be found [here](_styles_for_syntax_highlighting.css). I have updated the styling so that long comments do not automatically go off the card/page, and instead wrap onto the next line.

## Instructions

To see the terminal shown in the screenshots above, you need to do the following three things:
1. Edit the card fields so that they are called **Question**, **Terminal (Question)**, **Answer**, and **Terminal (Answer)**;
1. Go to the config for the syntax highlighting add-on (I used the [Syntax Highlighting FORK (night mode fix, gui config, etc.)](https://ankiweb.net/shared/info/1972239816) add-on) and click "Select Templates to update" and click "Yes". This will allow you to provide your own customised styling for the syntax highlighting, then;
1. Copy the image [here](https://github.com/PuneetMatharu/AnkiSetup/tree/main/images/terminal-bar.png), the fonts folder [here](https://github.com/PuneetMatharu/AnkiSetup/blob/main/fonts) and the syntax highlighting CSS [here](_styles_for_syntax_highlighting.css) into your `collection.media/` folder.
