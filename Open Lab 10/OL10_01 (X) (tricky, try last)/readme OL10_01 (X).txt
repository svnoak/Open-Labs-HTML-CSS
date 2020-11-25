
Check the video and make a webpage that looks like and works as the one there.

NOTE: This one is a bit complex

There are possibly other ways to solve it but for my solution I needed to use a new property: pointer-events.
https://developer.mozilla.org/en-US/docs/Web/CSS/pointer-events

Note that pointer-events is inherited so if an element has
pointer-events: none;
then none of its children will react to pointer events (click, hover).
Unless you change their property:
pointer-events: auto;

