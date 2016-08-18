# vscode-htmltagwrap
[![Build Status](https://travis-ci.org/Microsoft/vscode-htmltagwrap.svg?branch=master)](https://travis-ci.org/Microsoft/vscode-htmltagwrap)

## What is it
Wraps your selection in HTML tags.  Can wrap an inline selection or a selection of multiple lines.

To use, select a chunk of code, **press "Alt + W" ("Option + W" for Mac).**

![Wrap text in your images](images/screenshot.gif)

Download it now https://marketplace.visualstudio.com/items/bradgashler.htmltagwrap

## How to Use It
Select a block of text or a string of text.  Press <kbd>Alt</kbd> + <kbd>W</kbd> or <kbd>Option</kbd> + <kbd>W</kbd> for Mac.  Type the tag name you want, and it will populate the beginning and end tag automatically.

This extension works best in files that either use tabs or spaces for indentation.  It may not work as well with mixed tabs/spaces.

## Report Issues
I welcome pull requests.  Please report an issue on GitHub if you have trouble.

## Future features being explored
- #5 Once a user hits spacebar, then the second multi-cursor is lost so the user can write attributes like classes or styles. (Idea courtesy of Ruben Rios)
- Should we support `getSelections()` allowing multiple selections to be wrapped?
