# DuckDuckGO Homepage

This project is part of The [Odin Project curriculum](https://www.theodinproject.com). The assignment was to make
Google homepage, which i already made a couple of years ago. Soon after that, I stopped with
web development learning because of my job at that time. Fast forward to now, I
started learning again (pandemic and everything).
This time, I wanted to challenge myself a bit more so i decided to build
DuckDuckGo homepage.
At first, this project vas scary for me, the page on first look was overwhelming.
But then I told myself to go one element at the time, and i have started building
block by block. When I hit the wall, I started to google around to find a solution.
This challenge vas very difficult, but with positive mindset I slowly build it up.
The whole experience of building this project was fun, even with with all the roadblocks.

View my fake [DuckDuckGo homepage](https://mojotron.github.io/duckduckgo-homepage/index.html) via GitHub pages!

### What have I learned

- Nesting divs - wrapping divs in more divs makes targeting for style much
  easier, especially box model and using display properties.
- Deeper understanding of ccs box model
- Better positioning of elements with absolute and relative values.
- Flexbox - with basic understanding of flexbox all position problems are not
  problems at all, giving elements a wrapper div and making it display: flex resolve
  most of positioning problems.
- Dom traversing - learning about parent, child and sibling methods in DOM its
  easy to apply JS magic and make your apps stand out.
- ::before and ::after pseudo elements - understanding this two pseudo elements
  it's a powerful tool for adding elements to the page without HTML. And it is a great way
  to nail down knowledge of positioning.
- Responsive design - started desktop first approach and then made one
  media query breakpoint for mobile friendly design. This is where i've seen greatness
  of flexbox with changing rows to columns.
- Readme file - making readme file at first looked easy but it a lot more challenging
  when you are making one. I rehearsed markdown syntax with this great [webpage](https://markdownlivepreview.com/).
- Importance of naming - naming classes and variables makes heaven or hell as
  the files and project grows.
- Planning project - going without plan makes coding much more difficult, from
  naming do display problems. Simple diagrams makes building project fun, and not
  searching your way out of a maze you built around you.

### Biggest Roadblocks and recourses

- Closing modal window - when you click outside a modal window it suppose
  to close it down. First I tried with body selector, but clicking on buttons was
  in same time adding and removing hidden class. After research, I found out that
  you need to make overlay window over whole screen with fixed position. How to
  make overlay window on w3Scool is [great tutorial](https://www.w3schools.com/howto/howto_css_overlay.asp).
- Animation - with settings modal window, animation was visible only on first
  click. After that animation was not applying. I found out that this is default
  behavior and that solution to work around this problem is making two same
  @keyfames and alternating between them using JS to add/remove class names.
  I found solution with this great article from [stackoverflow](https://stackoverflow.com/questions/39790438/css-animation-works-only-first-time).
- Showing only one element and hide others with click - DuckDuckGo homepage at the
  bottom has sections with questions, one answer is visible and other are hidden.
  When you click on one, other must be hidden. To make this effect you must loop
  over all elements and apply event handler to remove hidden class from target element
  and add hidden class to all other elements. Great resource that helped me solve
  this problem is article from [freecodecamp](https://dev.to/mohdhussein/how-to-show-the-clicked-element-only-and-hide-others-in-vanilla-javascript-1ip2).

For me this was a great project of learning how to make webpages, with lots of
challenges and opportunities to expand my knowledge, and lots of holes in
understanding some topics. At the begging, I was thinking this is too
hard for my level at the moment but i told myself that it is time to go deep and
have fun, there is no room for quitting anymore.

> One step at a time is all it takes to get you there.
>
> -Emily Dikinson
