# Week 2 – Node, npm, Git, GitHub, DateTime: Assignments

## Show – Node and npm basics

* Show "Repl"-mode.
* Create a .js file that prints your name in the terminal. Explain different
  print outputs.
* Init npm. Explain package.json and lock files.
* Install chalk (https://www.npmjs.com/package/chalk). Add some fancy coloring.
* Create a function that can print out your version of Git, npm och Node.
* Create a function that creates a stuff.md file with the above print outs.
* Add an argument parser.
* Do something with the argument parser.

## Show – Git and GitHub (they are maybe familiar with git, but if needed)

* Local init
* Greate remote GitHub repo
* Commit, Log, Push
* (add an ssh key)
* Edit on Github.
* Pull
* Show rebase use-case
* Show creating branches
* .gitignore
* diff
* status
* clone
* pull requests (save until another lecture)

Watch:
**Optional: Git It? How to use Git and Github**

https://www.youtube.com/watch?v=HkdAHXoRtos

Another good video. When you know the basics and want to know more about
branches, pull requests, stashing

**Optional: Git Tip: Commiting with Vim**

https://www.youtube.com/watch?v=ebZzVAZC7tc

In the video he talks about 2 modes, there are more modes.

## Show – Date and Time (if we have time)

* Working with dates and time.
* Dealing with dates is a major problem. List problems.
* How to avoid many of the problems. Tests, tests and a declarative approach.

## Assignment – recreate and improve

* Recreate the code/steps of the presentation (Node and npm).
* Add a date library of your choice from npm
    * Examples at https://2022.stateofjs.com/en-US/other-tools/#date_management
    * Note that Moment.js is deprecated. Still good and often used, but the
      newer libraries are often a better choice.
    * or use the temporal api polyfill, see video below
* Add a function that writes current date and time to your file when you run
  your script.
* Add a function that writes how long it was since you started this course.
* Allow for sending in a date as an argument and writes the date to file as well
  as if the argument date was before, after or on the current date.
* Make sure all the dates and times has a nice formatting that "everyone" can
  understand.
* Add a function that also creates a runnable html-file (stuff.html) in addition
  to the stuff.md file. Include relevant markup and styling.
* Create a public GitHub repo and "upload" you code. For your own convenience,
  make sure to setup you GitHub account with an ssh-key.

Watch:
* Optional: Learn Temporal API In 17 Minutes https://www.youtube.com/watch?v=oOK3UzLJ_Cs

## Assignment – First idea

* Add a mention of the idea, from last week, that you've decided on, to your
  github project's Readme.md.

## Assignment – Find a style

* Add the style that you've decided on to your github project. Add both a link
  and an image (for you to figure out how) to your Readme.md file.

## For next week

Get a head start by watching the videos below. Or save them for next week, up to
you.

Watch:

* Module Bundlers Explained... – https://www.youtube.com/watch?v=5IG4UmULyoA
* Build tools – Vite https://www.youtube.com/watch?v=KCrXgy8qtjM
* Should You Use Tailwind CSS?  https://www.youtube.com/watch?v=hdGsFpZ0J2E
* Tailwind CSS is the worst https://www.youtube.com/watch?v=lHZwlzOUOZ4
* Optional: Build tools – Turbopack https://www.youtube.com/watch?v=6ZwnBI4Rb1w
* Optional: I didn't realize THIS about Tailwind... https://www.youtube.com/watch?v=ZuLn42merAg
