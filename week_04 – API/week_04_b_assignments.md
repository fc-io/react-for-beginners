# Week 4 – API: Assignments

## Show

* Fetch from an open API.
* Render with React in a decent way.
* Add routing.
* Add an about page.
* (Maybe: Add something that mutates.)

## Watch

### Fetching

**React Query Makes Writing React Code 200% Better**

https://www.youtube.com/watch?v=lVLz_ASqAio

* Notice that when he uses axios he could more or less have used fetch without
making any difference.
* Also notice, at the end, when he talks about mutation; that it's in general
  considered an anti-pattern to have stuff randomly jump in and change the
  layout. Its better to either:
    - Show a button that say that there is more content, and then the user can
      decide when to load new content.
    - Or to wait for the new data before loading the page in the first place.

### Routing

* Learn React Router v6 In 45 Minutes https://www.youtube.com/watch?v=Ul3y1LXxzdU
* Optional: RIP React Router? https://www.youtube.com/watch?v=LVzG3nncE4M
* Optional: What Is TanStack Router And Why I Love It https://www.youtube.com/watch?v=OwoZtv6u9p4

## Assignment – recreate and improve

* Recreate the code/steps of the presentation
* ...but use content, styling and shapes of your own choosing
* Find a new style from https://dribbble.com/tags/free
* Give credit on your about page towards the style you picked. Provide a link to
  where you found the style.
* Add another page/route
* ...and fetch data from the new page from another data source.
  * Examples of APIs that don't require authentication:
    https://github.com/cezary/simple-apis or find one of your own choosing
* BONUS: Make the site mobile as well as desktop friendly. Adapt design style as
  you see fit.
* BONUS: On the about page provide a few examples of screen sizes you've tested
  on.
