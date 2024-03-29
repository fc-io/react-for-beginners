# Week 2 – Node, npm, Git, GitHub, DateTime: Assignments

Many tought this assignment was one of the hardest. It was supposed to be one of the easier ones. Bu I can understand now that it's too much javascript. I would pretty much remove everything in this assignment and just make something easier.

## Show – Node and npm basics

* Show "Repl"-mode.
* Create an, index.js file that prints your name in the terminal.
* Init npm. Explain package.json, lock files and npm run.
* Install chalk (https://www.npmjs.com/package/chalk). Add some fancy coloring.
* Create a function that can print out your version of Git, npm och Node.
* Create a function that creates a index.md file with the above print outs.
* Add an argument parser.
* Do something with the argument parser.

## Show – Git and GitHub (they are maybe familiar with git, but if needed)

* Local init
* Greate remote GitHub repo
* Commit, Log, Push
* Add an ssh key!!!
* Edit on GitHub.
* Pull
* Show rebase use-case
* Show creating branches
* .gitignore
* diff
* status
* clone
* github: issues, pull requests (save until another lecture)
* show how to diff between commits. Use react-for-beginners as an example.

### Watch:

**Optional: Git It? How to use Git and GitHub**

https://www.youtube.com/watch?v=HkdAHXoRtos

Another good video. When you know the basics and want to know more about
branches, pull requests, stashing

**Optional: Git Tip: Committing with Vim**

https://www.youtube.com/watch?v=ebZzVAZC7tc

For when you accidentally forget `-m` in `github commit -m 'add new commit'`.

(In the video he talks about 2 modes, there are more modes, but those modes are
only needed if you want to get really good about using vi/vim.)

## Show – Date and Time (if we have time)

* Working with dates and time.
    - UTC (GMT)
    - Local time
* Dealing with dates is a major problem. (List some problems.)
* How to avoid many of the problems. Tests, tests and a declarative approach.

## Show – Unit Testing

* Talk about different forms of testing.
* Refactor into testable code.

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
* Allow for sending in a date as an argument
    - Write the argument-date to your file
    - Add a function that figures out if date sent in as a argument is before or
      after the date when you run the file.
* Make sure all the dates and times has a nice formatting that "everyone" can
  understand.
* Add a function that also creates a plain, runnable html-file (index.html) in
  addition to the index.md file. Include relevant markup, styling and the dates/info as required above.
* Create a public GitHub repo (if you haven't already, or a private repo but by
  also inviting me as a contributor) and "upload" your code. For your own
  convenience, make sure to setup you GitHub account with an ssh-key if you
  haven't already done so.
* ~~BONUS: Add a unit test for some part of the assignment (in addition to the example I
  showed during class).~~ Me showing testing was a bit of a mess so we skip this part of the assignment :).

Watch:
* Optional: Learn Temporal API In 17 Minutes https://www.youtube.com/watch?v=oOK3UzLJ_Cs

## For next week

Get a head start by watching the videos below. Or save them for next week, up to
you.

Watch:

* Module Bundlers Explained... – https://www.youtube.com/watch?v=5IG4UmULyoA
* Build tools – Vite https://www.youtube.com/watch?v=KCrXgy8qtjM
* Optional: Should You Use Tailwind CSS?  https://www.youtube.com/watch?v=hdGsFpZ0J2E
* Optional: Tailwind CSS is the worst https://www.youtube.com/watch?v=lHZwlzOUOZ4
* Extra Optional: Ultimate Tailwind CSS Tutorial https://www.youtube.com/watch?v=pfaSUYaSgRo
* Extra Optional: Build tools – Turbopack https://www.youtube.com/watch?v=6ZwnBI4Rb1w
* Extra Optional: I didn't realize THIS about Tailwind... https://www.youtube.com/watch?v=ZuLn42merAg
