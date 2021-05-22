# Pomodoro Timer Project

## App deployed via Vercel
https://project-pomodoro-timer-qualified-1-gray.vercel.app/

## Context
This React app is a replicated Pomodoro Timer from Thinkful's course. I collaborated with two others for this project. This taught me the importance of teamwork, what pair programming is about (our case was one driver, 2 navigators), and was a reason to showcase our knowledge of the coursework so far. We were learning React in this stage and found this project to really solidify our understanding of how state, props, and components were broken down.

## Intention
Pomodoro Timer is great for those who have a hard time focusing (especially students). You can set a focus timer for 25 (default) minutes, then take a 5 (default) min breather. It is recommended you focus on anything else other than what you were doing, such as going for a quick walk to clear your mind or getting some quick snacks. 

## Functionality
* Focus Duration
  * Default is set to 25 minutes. Goes up or down by intervals of 5
  * Minus button decreases by 5 (can't go lower than 5 min)
  * Plus button increases by 5 (can't go above 60 min)
  
* Break Duration
  * Default is set to 5 minutes. Goes up or down by intervals of 1
  * Minus button decreases by 5 (can't go lower than 1 min)
  * Plus button increases by 1 (can't go above 15 min)
  
* Play Button
  * Clicking button starts counting down from focus duration
  * Progress bar fills up
  * Pausing stops the timer, displays a "Paused" text, stops the progress
  * If timer reaches the end on focus, will sound an alarm, then automatically jump to break and vice versa
  
* Stop button
  * Disabled at the start
  * On click, will refresh timer, but will keep your focus duration and break duration settings.
 
## Discoveries
There were some pre-built functions included. Our group didn't know what each function was doing, so we debugged using VSCode and console.logged almost everywhere! It was great practice for working in the real world, because eventually we will work with a codebase that already exists, and researching was a crucial part for our success.

## Future Goals
I am thinking about adding more styles to this React app, as it looks pretty basic right now.

## Stack
HTML, CSS, JavaScript, ReactJS (hooks), NodeJS, Jest.





