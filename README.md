# Thoughts from ThatConference 2012

### Day 1
#### Keynote: Leon Gersing, "You" (archive video at: http://www.viddler.com/v/475571a7)
#### @rubybuhhda

Relationship = you + n^*

* Be nice (empathy)
  * Highlight positives
  * Not funny, don't laugh
  * Sarcasm is cancer. Remove it. Early.
* Avoid defensiveness at all costs
* Promote the positives in others
* Pair with others to better understand
* Don't be afraid to be proven wrong

Empowerment

* Change happens through understanding
* The path to self actualization is through failure

Cultivate a Culture of Failure

* The faster you fail, the quicker you get to what really matters most
  * Fail early
  * Fail often
  * Notice patterns
  * Experts fail too
  * Discover success, real success



### Talk 1: Hiking Your Way Through the Knockout.js Forest (1:00pm)
##### Ryan Neimeyer, Epic Systems
##### http://knockmeout.net

A framework for binding data to the DOM through:

* Declarative bindings
* Observable properties
* Computed observables

Takeaways
* While knockout.js has an easier syntax it's not directly comparable to backbone.js
* knockout.js is more for direct, on page form/DOM manipulation and data binding
* knockout.js seems to have more limited capability than backbone.js


### Talk 2: The Responsive Hangover - Life After The Buzz
##### Matthew Carver, Weber Shandwick
##### Slides: http://rwd.matthewcarver.com

Responsive toolkit:
* Best rapid prototyping library: (Foundation by Zurb)[http://foundation.zurb.com/]
* CSS preprocessor (LESS, SASS or Compass)
* 320 and up, responsive, mobile first framework
* Modernizr
* Font Awesome
* Codekit (HAML, Jade, etc. compiler kit) {not sure i agree with this}
* Off Canvas Navigation

Takeaways
* During prototyping, instead of building out a whole page, put together style tiles. Chunks of sitewide design elements presented outside the context of the content (b/c content always changes)


### Talk 3: jQuery Mobile
##### Steve Bodnar

Takeaways
* It's built on the concept of data-attributes to set behavior
* Browser grading indicates feature support
* Rapid mobile prototyping: http://www.codiqa.com



***

## Day 2

### http://thatconf.chrisjpowers.com/


***


## Day 3


### Talk 2: Javascript & Performance (1:00pm, Open Spaces)
##### Lead: Indu ???, Epic Systems

A conversation with 4 other folks about how Epic structures their proprietary JS arch
and how they tune and maintain it.

Takeaways
* Chrome Heap Snapshots, learn how to interpret
  1. https://developers.google.com/chrome-developer-tools/docs/heap-profiling
  2. https://developers.google.com/chrome-developer-tools/docs/heap-profiling-containment
  3. [Helpful Google Group Thread](https://groups.google.com/forum/?fromgroups#!topic/google-chrome-developer-tools/pfhssg-h6es%5B1-25%5D)
* Reminder: IE has finite css rendering limits per page
  1. Max CSS selectors = 4095 
      * http://www.habdas.org/2010/05/30/msie-4095-selector-limit/
  2. Max <link> elems = 32
      * http://social.msdn.microsoft.com/Forums/en-US/iewebdevelopment/thread/ad1b6e88-bbfa-4cc4-9e95-3889b82a7c1d/
      * http://nirlevy.blogspot.com/2007/06/internet-explorer-css-limit.html


### Talk 3: Best Practices for Enterprise JS Apps (2:30pm)
##### [Arthur Kay, Sencha Labs](http://speakerdeck.com/u/arthurakay)
##### Slides: https://speakerdeck.com/u/arthurakay/p/your-code-sucks-best-practices-for-enterprise-javascript-development

Takeaways
* Google Memory Leak Finder
  1. https://plus.google.com/115133653231679625609/posts/HfDXznyoxCU
  2. http://code.google.com/p/leak-finder-for-javascript/
  3. http://google-opensource.blogspot.de/2012/08/leak-finder-new-tool-for-javascript.html

* Phantom.js - a headless webkit UA, nice to write JS tests on

* Book: [Specification by Example](http://specificationbyexample.com/)
  1. The anti-Test Driven Development concept

* Useful further reading
  1. [Maintainable Javascript](http://shop.oreilly.com/product/0636920025245.do), Nicholas Zakas
  2. [Code Conventions for Javascript](http://javascript.crockford.com/code.html), Douglas Crockford
  3. [JavaScript Performance Tips & Tricks](http://moduscreate.com/javascript-performance-tips-tricks/), Grgur Grisogono

* Need to go back over slides again to further digest. Would have had more notes but LESS compile issue on Vision World prod was major interruption....