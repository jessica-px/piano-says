# Piano Says
[Live Demo](https://piano-says.netlify.com/)

A Simon-like musical memory game that challenges players to repeat up to 20 notes forming a randomized song. This project was based on freecodecamp's [Simon assignment](https://learn.freecodecamp.org/coding-interview-prep/take-home-projects/build-a-simon-game/).

#### Project Goals:
- User Story: I am presented with a random series of button presses.
- User Story: Each time I input a series of button presses correctly, I see the same series of button presses but with an additional step.
- User Story: I hear a sound that corresponds to each button both when the series of button presses plays, and when I personally press a button.
- User Story: If I press the wrong button, I am notified that I have done so, and that series of button presses starts again to remind me of the pattern so I can try again.
- User Story: I can see how many steps are in the current series of button presses.
- User Story: If I want to restart, I can hit a button to do so, and the game will return to a single step.
- User Story: I can play in strict mode where if I get a button press wrong, it notifies me that I have done so, and the game restarts at a new random series of button presses.
- User Story: I can win the game by getting a series of 20 steps correct. I am notified of my victory, then the game starts over.

#### Additional Features:
- the Tone.js library is used to programmtically produce audio, rather than importing an audio file for each note
- the user can select which key the randomized song will play in
- buttons change color on hover, to help the user differentiate them
- responsive layout using CSS Grid


#### Known Issues:
- current layout is too cramped with phone-sized screens
- inconsistent input on touch devices

__Libraries Used:__ [Tone.js](https://github.com/Tonejs/Tone.js)