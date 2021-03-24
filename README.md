# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Aditi Sharma**

Time spent: **4** hours spent in total

Link to project: (https://glitch.com/edit/#!/neighborly-alabaster-nitrogen)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [X] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:


![](https://media.giphy.com/media/cOYYF5cTr9zgAqVRIP/giphy.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I looked at the w3schools tutorials relating to the timer function.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The largest challenge I encountered while working on this project was with the timer function. It was difficult to position
the start and stop functions in such a way that the timer paused when the player finished entering pressing all the buttons, 
as well as when they got an incorrect answer. In order to fix these problems, I wrote out a skeleton flowchart in the same format
as the one provided for the game logic and then coded according to that. I find that writing down my thoughts while coding
is a very efficient way to keep my thoughts in order, instead of trying to keep the whole framework in my brain. After
looking at my written chart and some w3schools pages, I was able to correct the function calls.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing this project, I am most curious about how dynamic websites are built, especially including the use of other functionalities.
I would like to learn how to use APIs to allow expanded functions, and how to build databases behind these websites. I've experimented with
these concepts on my own, but would like to learn how to use them efficiently and on a larger scale.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on the project, I would firstly add levels with a longer sequence and more buttons. Secondly,
I'd include a log-in function so players could track their progress, and finally, I'd add a leaderboard with players who can 
memorize the longest sequences, to encourage competition and sustained playership. 



## License

    Copyright Aditi Sharma

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.