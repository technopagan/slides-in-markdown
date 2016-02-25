# Slides in MarkDown

This is a slide deck tool for giving presentations written in MarkDown. It is based on [Remark.js](https://github.com/gnab/remark/) and written in plain HTML, CSS &amp; JS, making it compatible with all operating systems. It features a presenter console with speaker notes, timer, screen blanking and more.

**[Live Demo](https://technopagan.github.io/slides-in-markdown/)**

## Writing 

To start writing your own slide deck in MarkDown, simply open the HTML file in your editor of choice and make changes as you wish. You can find all the places that you should edit by searching for the '#ToDo' hashtag inside the HTML file. Here are the different places in detail: 

1. Write your presentation's title in the 'title' tag of the 'head' section
2. Set '16:9' or '4:3' dimensions in the body.onload JavaScript
3. Write your slides in MarkDown as shown in the examples
4. Be inspiring!

## Presenting

1. Open the HTML file in a browser (via 'file://' or local webserver)
2. Press 'c' to clone the current view into a new, synced window
3. Press 'p' in the original window to enter Presenter Console
4. Move the cloned window to projector / screen display
5. Press 'f' to make the cloned window fullscreen
6. Enjoy!

Hint: You can always press 'h' to see an overview of all available key commands.

## Exporting to PDF

1. Install [DeckTape](https://github.com/astefanutti/decktape)
2. Start a local webserver inside slide deck directory (e.g. with 'python -m http.server')
2. Go to your local DeckTape repository using the terminal
3. Run: './bin/phantomjs decktape.js http://127.0.0.1:8080/slidedeck.html slidedeck.pdf
4. Be proud of your beautiful slidedeck.pdf file!

## Theming

If you want, you can customize the looks of your slide deck by simply editing the CSS file with your favorite code editor. Colors, fonts and layout are completely customizable as if you were editing a regular website.

## Inspiration

The need for me to create this tool arose from using & loving the wonderful [DeckSetApp](http://decksetapp.com/) for Mac. Sadly, DeckSetApp is an OSX-only app, so when switching operating systems, I could not rely on it anymore. I tried many alternatives & frameworks, but the difficulty of use or lack of documentation made them unbearable. With this tool I intend to lower the bar for creating all-OS, MarkDown-based slide decks with presenter console, speaker notes, PDF export that run in the browser.
