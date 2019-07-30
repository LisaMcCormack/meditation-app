# Meditation app
Meditation app <a href="https://www.youtube.com/watch?v=oMBXdZzYqEk&list=PLDyQo7g0_nsXlSfuoBpG5Fgz0Qe3IvWnA&index=10">tutorial</a> using vanilla JavaScript

It is an app that required a lot of css styling.  The app went from looking like this:

![alt text](./images/styling.png)


To this:

![alt text](./images/nicestyling.png)


Meditation has proven scientific benefits.

The app plays the sound of rain of the beach while you meditate.  You can choose to meditate for two, five or 10minutes.  

I have finished the tutorial but the app has some bugs:

- Selecting the two, five or 10minute buttons does not work
- Hitting the rain button - there is no sound, the timer stays at 10:0 and the play button shows the pause image as above image.

However, if I hit refresh the default is the rain video and the sound, timer and video work.

## My approach to fixing the bugs
I will look at the code and write comments over each function to fully understand what it is doing.
For this problem:
- Hitting the rain button - there is no sound, the timer stays at 10:0 and the play button shows the pause image as above image.
This was easy to solve, I had mistyped 3 as s on line 40 of index.html!!
