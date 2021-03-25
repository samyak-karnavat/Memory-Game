# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Samyak Mahavir Karnavat**

Time spent: **3** hours spent in total

Link to project:

https://glitch.com/edit/#!/fancy-holy-worm?path=README.md%3A1%3A0

## Required Functionality

The following **required** functionality is complete:

* Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* "Start" button toggles between "Start" and "Stop" when clicked. 
* Game buttons each light up and play a sound when clicked. 
* Computer plays back sequence of clues including sound and visual cue for each button
* Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* User wins the game after guessing a complete pattern
* User loses the game after an incorrect guess

The following **optional** features are implemented:

* Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* Buttons use a pitch (frequency) other than the ones in the tutorial
* More than 4 functional game buttons
* Playback speeds up on each turn
* Computer picks a different pattern each time the game is played
* Player only loses after 3 mistakes (instead of on the first mistake)

The following **additional** features are implemented:

* None

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![](https://media.giphy.com/media/IyHrT6WuQqFuU8iHVB/giphy.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://www.w3schools.com/css/css3_buttons.asp
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math
https://www.w3schools.com/cssref/css_colors.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The biggest challenge I encountered was changing the style of the buttons to something different that looked good to me. First, I decided that I wanted to make the Start and Stop buttons bigger.
I had to first search for the specific properties that I needed to change to do so. After that, I experimented with different values for the font size, background color, and width of the buttons.
The width was too large at first, but I lowered it slightly each time, until I felt it was right. Then, I changed the font-size, but this also affected the actual width of the button, requiring
me to adjust the width again. Eventually, I was able to get it right. Adding the fifth button required finding a light and dark color to use with it. I decided to use orange as the dark color to
be displayed when the button was pressed or lit. However, there was no recognized color as lightorange. I than began searching for a list of css colors. I found a list, and decided that Mocassin
will be an appropriate color for the light version of orange. However, just typing in Mocassin for the color did not work. I then had to use the hexadecimal value for that color to make it be displayed
appropriately.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

When working on large websites, is the html, css and javascript handled by the same person or team of people? If not, then how do different people or teams efficiently communicate with each other?
Based on this project, it seems like html, css and javascript are closely related. When modifying one of those, we often had to make changes to the other files as well. For example, new html tags like
buttons might require unique css for it. New javascript functions would need to be added to html tags. And javascript functions to find elements by id or class and modify those properties might affect the css
page as well. How is all of this done efficiently so that the same files can be simultaneously worked on without much conflict?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time, I would first implement the rest of the optional features, which are: images in buttons, audio clips or a sequence of tones, and a time limit for answering. I would then change all constants
except the number of buttons to variables and make the program work with different values for these variables. I would also allow for a different length pattern than just eight.
Finally, I would make it so that the user can input values such as the length fo the pattern, the different time delays, and the factor by which the clue hold time decreases each turn. Then, these values
will be used to play the game.



## License

    Copyright Samyak Mahavir Karnavat

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
