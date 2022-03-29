# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Nhi Nguyen**

Time spent: **10** hours spent in total

Link to project: https://glitch.com/edit/#!/noiseless-wool-napkin

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/sS2V8FK.gif)(gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
https://www.w3schools.com/html/html_colors.asp
https://www.w3schools.com/howto/howto_google_fonts.asp


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

Completing the game’s logic, which was a guess function, was the most difficult aspect of this submission for me. I overcame this difficulty by reviewing earlier Java courses that included conditional statements. The first two if-else conditions are set up so that if the guess is correct, the user wins the game; otherwise, the user loses. When I first started coding, a flow chart was quite useful. Despite the fact that I have used a flow chart before and understand how the game operates. It took me a long time to finish the game's coding. I was able to complete the most of the code, however I did make a few errors. One of the mistakes I made was forgetting to minus one, which indicated whether or not it was the last turn. If it is the last turn, the user wins; else, the game continues. Because the logic was incorrect, the game was stopped after the first guess. In the end, I decided to look at the answer that was provided in the instruction. I still have a lot to learn and practice with logic, and I've discovered that flowcharts are really useful when dealing with logic difficulties such as games.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

What should I do to make the website load faster? 
What are other languages to design websites other than HTML, CSS and JS? 
What's the difference between a desktop version and a mobile version of a website? 
What is the difference between web design and web development? 
What are some helpful suggestions for making websites more accessible and enjoyable for users? 
Many websites use cookies, and I'm not sure what they're for. Is it necessary to have a cookie with a website all the time? 
How much knowledge of networks do I need to have? 
What is the most efficient way to learn full stack web development? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to spend on this project, I would try to complete the optional feature of adding a ticking clock. I searched for resources to assist me with this problem, but I didn't have enough time to complete it. I understand there are some basic requirements, such as setting a time for 1 minute and having the clock disappear after the timer runs out. Even though I haven't been able to write the code or create a pseudocode, I believe I could finish this ticking clock feature if I had a few more hours and did more research.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/dbc8d574bcc348c299b69669d2110ec4)


## License

    Copyright Nhi Nguyen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
