# _Keyboard Drum Kit_

#### _{A site that allows the user to make drum sounds using keyboard strokes}, {Dec 2, 2016}_

#### By _**Kyle Lange**_

![screenshot](Screen Shot.png)


## Learnings
 Today's code include new learnings on:

* <kbd> = html5 for keyboard input

* data-key="#" used to save data that is bespoke to the app taht can be manipulated with javascript later

* const = constant. If you declare a value to this (globally or locally), it will stay the same.  Often, const names are ALL CAPS. Ex: const FAV_NUM = 7;  One way to change a const is to use it in a conditional statement.  [That will change the value.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)

* Attribute Selectors: use the [] to hold the attribute you warranty document.querySelector(`audio[data-key="${e.keyCode}"]`)

* Backticks = used to write proper ES6 so that ${e.keyCode} can be used instead of having to write the keyCode each time singularly.

## Setup/Installation Requirements

1. Download this repo using your terminal: git clone repo-name pasted here

2. View the code by drag-and-dropping the file into your [favorite text editor](https://atom.io)

3. run/check-out the program by dropping the index/html file from your folder into your web browser

## Known Bugs

_There are no known bugs as of the last commit. Please send an ISSUE on github in the repository if you see something I have not._

## Support and contact details

For questions or comments, please __email  [Kyle here.](baronsintrees@gmail.com)__

## Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript (my own)

### License

Copyright (c) 2016 **_Kyle Lange_**

This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
