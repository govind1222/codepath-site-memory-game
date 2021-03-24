# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Govind Pillai**

Time spent: **2** hour spent in total

Link to project: https://glitch.com/edit/#!/govind-pillai-memory?path=README.md%3A1%3A0

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [x] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn


## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://cdn.glitch.com/b295a5bc-c9f6-40b6-9e2e-d35c8f0148fa%2Fezgif.com-gif-maker.gif?v=1616601735131)
![](<https://cdn.glitch.com/b295a5bc-c9f6-40b6-9e2e-d35c8f0148fa%2Fezgif.com-gif-maker%20(1).gif?v=1616602219157>)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   
   [https://www.w3schools.com/cssref/css_colors.asp - used to select colors for buttons]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   
   [A challenge I encountered was figuring out how all the JavaScript tied together with the HTML and CSS files. I usually don't work with vanilla JavaScript so I had to look at each section of the code and made
   sure I understood everything it did. I also looked at the background information provided by CodePath. Furthermore, adding the optional items was a challenge for me as I had to apply what I learned. Through a 
   little bit of trial and error, I was able to figure out how most of the optional elements worked and implement them. I also had to to track down some bugs with my application and sort that out. This involved me
   tracing the code as it would execute, something which required me to understand how the code all tied together. This allowed to fix any issues I could find with the game.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   
   [I know that JavaScript is one of the most widely used scripting languages for web development but I'm curious about how others like PHP are prevalent and what the pros/cons of using other languages over JavaScript
   are. Another question I have is how is good security maintained when developing a web application? Especially when you realize an app to the public, how do web developers ensure that the site isn't prone to 
   cyber attacks, or is that the responsibility of an entirely seperate team? ]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   
   [If I had a little more time, I might look into added difficulty levels so that the user can choose how quickly the clues play out. For example, clues playing out for those on hard mode would be much quicker 
   than in easy mode and user would also have less time to enter a clue sequence before time was up. Something else I could do is add controls for the user so they could choose
   how many turns they had until the game was won. The current default is 8 but if users want to play a shorter game, they could set that number to 4 for example. They could also choose to make the game last longer
   by having more than 8 turns. Lastly, I might've looked into added a backend component or database so that users could save their progress and keep track of the max score in the game. This way they could save the game
   and then come back later, reload the previous game state and continue playing from that point on.]

## License

    Copyright [Govind Pillai]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
