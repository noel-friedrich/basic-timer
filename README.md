# basic-timer
> a basic timer application on [my website](https://noel-friedrich.de/timer/)

## How to use
1. Go to [the website](https://noel-friedrich.de/timer/)
2. Press Start
3. Enjoy

## Intended Use
The Timer is intended to be used for games to control how
much time each player has to make their move.

## Features
- The Timer changes its background color based on the remaining time
  > Green: more than 5 seconds left  
  > Yellow: less than 6 seconds left  
  > Red: less than 4 seconds left  
- The Timer plays a sound when the time is up and warns you on seconds 5, 3, 2 and 1
- Include the GET parameter `seconds` to set the timer to a specific amount of seconds
  > Example: `https://noel-friedrich.de/timer/?seconds=60` will set the timer to 60 seconds
- Include the GET parameter `silent` to mute the timer
  > Example: `https://noel-friedrich.de/timer/?silent` will mute the timer

## Code Structure
Everything is contained in a single HTML `index.html` file. It contains the pure Javscript and Styling.  
It's really not that big of a project. I just wanted to play some card games with my friends and needed a timer.
I spent more time on this README than on the actual project.