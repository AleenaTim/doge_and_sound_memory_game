# Pre-work - *Memory Game*

**Doge Sound and Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Aleena Tim**

Time spent: **16** hours spent in total

Link to project: https://doge-and-sound-memory-game.glitch.me
Link to code: https://glitch.com/edit/#!/doge-and-sound-memory-game

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up/slows down depending on difficulty user has clicked
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Added difficulty modes (easy, medium, hard) Easy = 5 turns, Medium = 10 turns, Hard = 15 turns
      By default, easy difficulty is selected. When user changes difficulty, the number of turns variable, text
      and array size is updated as well. When the array size is updated, the pattern/# of turns is increased.

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
* [x]https://recordit.co/pyxMJkQe3f
* [x]https://recordit.co/LTyvcQ2RkR
* [x]https://recordit.co/G3qfTsi5pN

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://www.w3schools.com/]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[The biggest challenge I had was implementing the different difficulties because I had to reinitialize the array size for pattern and
reflect the difficulty on the console. I also had to hide the buttons when the user starts the game to avoid errors.
For example, when the user clicks the hard button -- number of turns changes to 15 and I also wanted to display the difficulty and
number of turns on the console. I used the span HTML element because I was able to output and update the variable from my JS file.
Initially, I stored the number of turns into a variable and passed it as an argument like this: pattern = new Array(numTurns). This didn't 
work and no matter what difficulty I switched it to, it always resulted into only 1 turn. Apparently, the syntax I wrote to reinitialize 
an array size was incorrect so instead I changed it to pattern.length = numTurns. Fortunately, this changed the length and I was able to 
paste the code into rest of the other game modes. I assume it was incorrect because I've already created the pattern Array object and 
passing it involves creating a new object and the constructor uses the argument for the size of the array.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[Initially, I was trying to add dog barks to the button clicks but didn't have enough time. I would also "prettify" the buttons, add a timer
and more game mode features (example: endless mode to achieve the highest score)]



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Aleena Tim]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
