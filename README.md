# To-Do List

A to-do list with a progress bar that judges you. Add tasks, check them off, watch the bar fill up. It even cheers you on with a "Keep it up!" when you're on a roll.

![To-Do List screenshot](screenshot.jpg)

The hardest part was the progress bar math. Every add, delete, check, and uncheck has to recount completed vs total and redraw the bar, or it starts lying to you. Simple division, but it has to run at exactly the right moments.

Built with HTML, CSS, and vanilla JavaScript. My code is on the `answer` branch.
