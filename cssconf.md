# <https://2015.cssconf.com/>

10:00 - 10:40  
TIM HOLMAN  
FUN.CSS  
Tumblr's Tim Holman will remind us that CSS can be be a powerful means of expression, an outlet for creativity, and just plain fun to play with!

10:45 - 11:25  
ANDREY SITNIK  
POSTCSS: THE FUTURE AFTER SASS AND LESS  
We're living in a post-preprocessing world, and PostCSS project maintainer Andrey Sitnik will show you why!

- post css is... _evolution_
- 40% of es6 comes from coffeescript
- preprocessors mix with your css where postcss does not (mike doesn't understand, yet)
- postcss bem-linter
- doiuse
- rtlcss
- order of magnitude faster to parse
- what will save us from the dark side of preprocessors
- @postcss
- evl.ms
- <http://ai.github.io/about-postcss/en/>

11:30 - 12:15  
RACHAEL L. MOORE  
OPS TOOLING FOR UI  
New workflows promise productivity boons but bring a heavy intimidation factor; Rachael Moore will show you how to wield these new tools, and where they fit in your toolbelt.

- build tools
- visual diffs

12:15 - 1:15  
LUNCH

1:15 - 1:55  
LEA VEROU  
THE MISSING SLICE  
W3C invited expert Lea Verou will show us how to solve challenging problems with modern CSS and SVG as she builds an animated pie chart.

- > humans like curvy things

2:00 - 2:40  
DAVID NEWTON  
IMPROVING PERFORMANCE WITH RESPONSIVE (AND RESPONSIBLE!) IMAGES  
<picture> this: there's a new way to handle putting images on the web, and David Newton will show how there's a lot more to this than meets the eye.

- <https://www.npmjs.com/package/grunt-respimg>

2:45 - 3:25  
AURELIA MOSER  
STYLISH SLIPPY MAPS: CREATIVITY WITH CARTOCSS  
Aurelia Moser of CartoDB will show us how to use our experience with CSS not only to lay out websites, but to visualize the world around us!

3:30 - 4:00  
BREAK  

4:00 - 4:40  
HELEN HOU-SANDÍ  
DRAGGING WORDPRESS CORE CSS INTO THE 2000S  
WordPress lead developer Helen Hou-Sandí will describe how she and the WordPress team are keeping an on eye on the future while taking care of a massive community.

4:45 - 5:25  
MICHAEL MIFSUD  
IT'S ALL JUST FUNCTIONS AND VARIABLES, RIGHT?  
CSSConf Australia co-organizer Michael Mifsud will be on hand to share his experience as a frontend developer led him from CSS to C++ and to becoming a contributor to Libsass .

FRIDAY, JUNE 19

9:00 - 10:00  
BREAKFAST

10:00 - 10:40  
ESTELLE WEYL  
CSS? WTF!  
Web standards expert Estelle Weyl will showcase some brand new CSS3 WTFs: Wonderfully Terrific Features!

10:45 - 11:25  
ADEKUNLE ODUYE  
SASS: THE GATEWAY DRUG FOR DESIGNERS WHO WANT TO CODE  
SassConf co-organizer Adekunle Oduye will share how using Sass didn't just make him a better designer – it made him into a developer!

11:30 - 12:15  
MANUEL REGO  
CSS GRID LAYOUT IS JUST AROUND THE CORNER  
Grids are a fundamental tool for design and layout, and with the new CSS Grid Layout standard, they'll finally be first-class citizens in our workflows. Manuel Rego Casasnovas will guide us through this new spec and how to use it in current browsers.

- grid lines (between columns)
- grid tracks (between rows)
- `display: grid;`
- `grid-template-columns`, `grid-template-rows`
- `grid-template-columns: 100px 100px;` // makes two cols, each 100px wide
- `grid-template-rows: 100px 100px;` // makes two rows, each 100px high
- `grid-template-columns: 100px 1fr;` // `fr` means free space, kind of like `flex: 1;`
- `fr`
- dom order = visual order
- `grid-row` `grid-column` can break out of the dom order
- `grid-column: 1 / 3;` // / 3 means span 3 columns
- `grid-template-areas`
- `.header { grid-area: header }`
  `.nav { grid-area: nav }`
  `grid-template-areas: header nav`
- `grid-auto-flow: column` // converts to cols
- alignment
- `align-item`, `justify-items`, `justify-self`

12:15 - 1:15  
LUNCH

1:15 - 1:55  
CHRIS COYIER  
THE WONDERFUL WORLD OF SVG  
SVGs got you going 'SV-jeeze‽' CSS Tricks curator Chris Coyier will be on hand to show us all the possibilities of this flexible and powerful graphics format.

- svgo optimizer
- svg icon systems
  + needs `<symbol>`
  + icomoon does this for you

2:00 - 2:40  
COLIN MEGILL  
INLINE STYLES ARE ABOUT TO KILL CSS  
Who needs stylesheets when you can plop 'em in a perfectly good style attribute? Not you! Find out why in a very React-ionary talk from Colin Megill.

- @colinmegill
- lodash/underscore
- http://react.rocks/example/component-playground
- https://docs.google.com/presentation/d/1pL8e2OC8iDUWCvGkixYB18bRXjiVRmSgwiWoxiQN3vQ/edit#slide=id.gb45cedd10_0_4

2:45 - 3:25  
RYAN SEDDON  
PERFORMANCE BEYOND THE PAGE LOAD  
Find out how your CSS impacts page performance when folks do things like scroll and click, with Ryan Seddon, perhaps better known as The CSS Ninja .

- `transform` and `opacity` do not cause a reflow
- <csstriggers.com>
- requestanimationframe
- translate is faster to show a modal instead of display none/block
- `contain: strict;` <http://dev.w3.org/csswg/css-containment/>

3:25 - 4:00  
BREAK

4:00 - 4:40  
SARAH DRASNER  
COMPLEX RESPONSIVE ANIMATIONS  
Trying to perfect UI animations against the moving target of a responsive layout? Trulia's Sarah Drasner has got some tips on how to balance these complementary concerns.

- <http://www.smashingmagazine.com/2015/06/08/practical-techniques-on-designing-animation/>
- <http://codepen.io/sdras/pen/jPLgQM/>
- <http://www.slideshare.net/pixelass/exploring-fractals-in-css-fronttrends-warsaw-2015>
- importance of contact form (submit should give feedback)
- <http://observer.com/2015/06/the-2016-u-s-presidential-candidates-logos-ranked/>
- <http://codepen.io/pixelass/pen/gpRXGd>
- <https://jakearchibald.github.io/svgomg/>
- <http://blog.trackduck.com/2015/06/12/best-podcasts-for-web-and-uiux-designers>
- <http://www.cssdesignawards.com/articles/design-dev-feed-26/233/>

4:45 - 5:25  
JENN LUKAS  
BEING A GOOD COWORKER  
With everything technical that goes into building for the web, it's easy to forget about the <human> element. Jenn Lukas will wrap up the conference with some lessons that'll make you a better developer or designer, even when you're not at the keyboard.

- <https://en.wikipedia.org/wiki/Ascension_(miniseries)>
- be on time most of the time
- embrace just enough transparency
- use contraction, don't use "just", use "please"
- dress for the job
- speak for the job
- stop calling women "girls"
- stop calling interfaces "sexy"
- never "I" always "we"
- keep personal business out of the office
- grab coffee with coworkers
- don't talk smack about other people; we want to work with nice people
- own up to your mistakes to resolve conflicts wisely
- always meet deadlines
- know when to ask for help (15 minute rule)
- learn to appreciate feedback
- learn through personal projects
- expand horizons with collaboration
- respect is the best way to work together
- learning what your coworker does is the best way to gain respect
- sharing makes your coworkers and you make the best of yourselves
- lunch and learns (if you provide pizza, they will come)
- attend meetups together
- teach together at a meetup
- coworker volunteering session
- document all the things as a team
- try something completely new (can rejuvinate our current job and build patience)
- respect different work styles
- askers or guessers
- establish team norms
- don't microwave fish
- give credit say "thanks"
- stop looking for _wrong_, start high-fiving _right_

6:00 - 9:30  
BOCOUP PARTY AFTER  
GRAN MORSI  
We'll all head downtown to wrap up the conference in style (get it?) at with drinks and food sponsored by Bocoup at TriBeCa's Gran Morsi . We've rented out the private room downstairs so we all can eat and drink, mix and mingle, and relax once the talks are in the book.
