
# Slideshow

A simple bare-bones in-browser slideshow built by someone who doesn't feel comfortable in tools like Powerpoint or Keynote. This was built to be used as a presentation tool, not actually posted online; as such accessibility considerations haven't been taken. 

## Installation

Nothing to do! Any dependency is in the repo. Some shortcomings to this, but on the plus side I often want zero steps for a quick presentation.


## Usage

- Contents in the `section` tags in index.html. Leaving a few examples to reverse engineer. 
- View in the browser. Use arrow keys to navigate
- Type `/` + a number + `enter` to jump to a slide by number (see URL for reference)
- For my convenience this includes (Prism)[http://prismjs.com] to style code blocks, (Mousetrap)[https://craig.is/killing/mice] for the keyboard commands, and jQuery.
- Slide background gradients are set by nth-of-type selector, but can be overridden by class.


## To Do
- Make JS add ids to the slides to prevent human error
- Make the Slides coloring clearer
