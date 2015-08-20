# custom-chrome
Adds custom styles for Chrome's devtools

## Installation

- Clone this repo
- Goto chrome://flags/#enable-devtools-experiments and click "Enable" at "Developer Tools experiments".
- Restart Chrome
- Open Devtools settings (click the cogwheel in devtools)
- In the experiments tab, check "Allow custom UI themes"
- Close an reopen devtools.

## Current implementation
![Screenshot of example](/screenshot.png?raw=true "Looking swaggy!")
Currently, all it does is make unmatched selectors half the font-size of matched ones and limited to a single line (overflowing to an ellipsis). It also give a fuchsia text-shadow to the matched selector for easy spotting.

## Todo
- Look into making unmatched selectors expandible

