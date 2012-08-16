# Thoughts from ThatConference 2012

## Day 1

### 


***

## Day 2

### 


***


## Day 3


### Talk 2: Javascript & Performance (1:00pm, Open Spaces)
##### Lead: Indu ???, Epic Systems

A conversation with 4 other folks about how Epic structures their proprietary JS arch
and how they tune and maintain it.

Takeaways
    * Chrome Heap Snapshots, learn how to interpret
        1. (https://developers.google.com/chrome-developer-tools/docs/heap-profiling)
        2. (https://developers.google.com/chrome-developer-tools/docs/heap-profiling-containment)
        3. [Helpful Google Group Thread](https://groups.google.com/forum/?fromgroups#!topic/google-chrome-developer-tools/pfhssg-h6es%5B1-25%5D)
    * Reminder: IE has finite css rendering limits per page
        1. Max CSS selectors = 4095 
            * [http://www.habdas.org/2010/05/30/msie-4095-selector-limit/]
        2. Max <link> elems = 32
            * [http://social.msdn.microsoft.com/Forums/en-US/iewebdevelopment/thread/ad1b6e88-bbfa-4cc4-9e95-3889b82a7c1d/]
            * [http://nirlevy.blogspot.com/2007/06/internet-explorer-css-limit.html]


### Talk 3: Best Practices for Enterprise JS Apps (2:30pm)
##### [Arthur Kay, Sencha Labs](http://speakerdeck.com/u/arthurakay)
##### Slides: [https://speakerdeck.com/u/arthurakay/p/your-code-sucks-best-practices-for-enterprise-javascript-development]

Takeaways
    * Google Memory Leak Finder
        1. [https://plus.google.com/115133653231679625609/posts/HfDXznyoxCU]
        2. [http://code.google.com/p/leak-finder-for-javascript/]
        3. [http://google-opensource.blogspot.de/2012/08/leak-finder-new-tool-for-javascript.html]

    * Phantom.js - a headless webkit UA, nice to write JS tests on

    * Book: [Specification by Example](http://specificationbyexample.com/)
        1. The anti-Test Driven Development concept

    * Useful further reading
        1. [Maintainable Javascript](http://shop.oreilly.com/product/0636920025245.do), Nicholas Zakas
        2. [Code Conventions for Javascript](http://javascript.crockford.com/code.html), Douglas Crockford
        3. [JavaScript Performance Tips & Tricks](http://moduscreate.com/javascript-performance-tips-tricks/), Grgur Grisogono

    * Would have had more notes but LESS compile issue on Vision World prod was major interruption...