# Reveal.js
### The HTML (+.MD) Presentation Framework

<small> Created by [Hakim El Hattab](http://hakim.se) and collaborators (then forked by MCV for bottom bar and markdown demo file)</small> 
Notes: Examples notes

---

## Hello There 

reveal.js enables you to create beautiful interactive slide decks using HTML. This presentation will show you examples of what it can do
 

---

## Vertical Slides

Slides can be nested inside of each other.

Use the <em>Space</em> key to navigate through all slides.

<a href="#" class="navigate-down">![Down arrow](https://s3.amazonaws.com/hakim-static/reveal-js/arrow.png)</a>

----

## Basement Level 1

Nested slides are useful for adding additional detail underneath a high level horizontal slide.

----

## Basement Level 2

That's it, time to go back up.

<a href="#/2">
							<img width="178" height="238" data-src="https://s3.amazonaws.com/hakim-static/reveal-js/arrow.png" alt="Up arrow" style="transform: rotate(180deg); -webkit-transform: rotate(180deg);">
						</a>

---

## Slides

Not a coder? Not a problem. There's a fully-featured visual editor for authoring these, try it out at <a href="https://slides.com" target="_blank">https://slides.com</a>.

---

## Point of View

Press <strong>ESC</strong> to enter the slide overview.

Hold down the <strong>alt</strong> key (<strong>ctrl</strong> in Linux) and click on any element to zoom towards it using [zoom.js](http://lab.hakim.se/zoom-js). Click again to zoom back out.

(NOTE: Use ctrl + click in Linux.)

---

## Touch Optimised

Presentations look great on touch devices, like mobile phones and tablets. Simply swipe through your slides.

---

## Markdown support

Write content using inline or external Markdown.
Instructions and more info available in the [readme](https://github.com/hakimel/reveal.js#markdown).

```
<section data-markdown>
  ## Markdown support
  Write content using inline or external Markdown.
  Instructions and more info available in the [readme](https://github.com/hakimel/reveal.js#markdown).
</section>
```

---

## Fragments

Hit the next arrow...

... to step through ... <!-- .element: class="fragment" data-fragment-index="1" --> 

<span class="fragment">... a</span> <span class="fragment">fragmented</span> <span class="fragment">slide.</span>

----

## Fragment Styles

There's different types of fragments, like:

<p class="fragment grow">grow</p>
<p class="fragment shrink">shrink</p>
<p class="fragment fade-out">fade-out</p>

<span style="display: inline-block;" class="fragment fade-right">fade-right, </span>
<span style="display: inline-block;" class="fragment fade-up">up, </span>
<span style="display: inline-block;" class="fragment fade-down">down, </span>
<span style="display: inline-block;" class="fragment fade-left">left</span>

<p class="fragment fade-in-then-out">fade-in-then-out</p>
<p class="fragment fade-in-then-semi-out">fade-in-then-semi-out</p>
Highlight <span class="fragment highlight-red">red</span> <span class="fragment highlight-blue">blue</span> <span class="fragment highlight-green">green</span>

---

## Transition Styles

You can select from different transitions, like: <br>
<a href="?transition=none#/transitions">None</a> -
<a href="?transition=fade#/transitions">Fade</a> -
<a href="?transition=slide#/transitions">Slide</a> -
<a href="?transition=convex#/transitions">Convex</a> -
<a href="?transition=concave#/transitions">Concave</a> -
<a href="?transition=zoom#/transitions">Zoom</a>

---

## Themes

reveal.js comes with a few themes built in: <br>

<!-- Hacks to swap themes after the page has loaded. Not flexible and only intended for the reveal.js demo deck. -->
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/black.css'); return false;">Black (default)</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/white.css'); return false;">White</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/league.css'); return false;">League</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/sky.css'); return false;">Sky</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/beige.css'); return false;">Beige</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/simple.css'); return false;">Simple</a> <br>
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/serif.css'); return false;">Serif</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/blood.css'); return false;">Blood</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/night.css'); return false;">Night</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/moon.css'); return false;">Moon</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/solarized.css'); return false;">Solarized</a>

---

<!-- section data-background="#ff000000" -->

## Slide Backgrounds
Set <code>data-background="#dddddd"</code> on a slide to change the background color. All CSS color formats are supported.

<a href="#" class="navigate-down">
<img width="178" height="238" data-src="https://s3.amazonaws.com/hakim-static/reveal-js/arrow.png" alt="Down arrow">
</a>

----

<!-- .slide: data-background="https://s3.amazonaws.com/hakim-static/reveal-js/image-placeholder.png" -->

<h2> Image Backgrounds </h2>

<pre><code class="hljs html">&lt;section data-background="image.png"&gt;</code></pre>

----

<!-- .slide: data-background="https://s3.amazonaws.com/hakim-static/reveal-js/image-placeholder.png" data-background-repeat="repeat" data-background-size="100px"-->

## Tiled Backgrounds 

<pre><code class="hljs html" style="word-wrap: break-word;">&lt;section data-background="image.png" data-background-repeat="repeat" data-background-size="100px"&gt;</code></pre>

----

<!-- .slide: data-background-video="https://s3.amazonaws.com/static.slid.es/site/homepage/v1/homepage-video-editor.mp4,https://s3.amazonaws.com/static.slid.es/site/homepage/v1/homepage-video-editor.webm" -->

## Video Backgrounds

for html pages
<pre><code class="hljs html" style="word-wrap: break-word;">&lt;section data-background-video="video.mp4,video.webm"&gt;</code></pre>

or for markdown slide
``` html
    <!-- .slide: data-background-video="video.mp4,video.webm"-->
````

----

<!-- .slide: data-background="http://i.giphy.com/90F8aUepslB84.gif"-->

## ... and GIFs!

---

<!-- .slide: data-transition="slide" data-background="#4d7e65" data-background-transition="zoom"-->

## Background Transitions

Different background transitions are available via the backgroundTransition option. This one's called "zoom".

<pre><code class="hljs javascript">Reveal.configure({ backgroundTransition: 'zoom' })</code></pre>

---

<!-- .slide: data-transition="slide" data-background="#b5533c" data-background-transition="zoom"-->

## Background Transitions

You can override background transitions per-slide.

<pre><code class="hljs html" style="word-wrap: break-word;">&lt;section data-background-transition="zoom"&gt;</code></pre>

---

<!-- .slide: data-background-iframe="https://hakim.se" data-background-interactive-->

<div style="position: absolute; width: 40%; right: 0; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 20px; text-align: left;">
    <h2>Iframe Backgrounds</h2>
<p>Since reveal.js runs on the web, you can easily embed other web content. Try interacting with the page in the background.</p>
</div>

---

<!-- .slide: data-background-iframe="https://matt-chv.github.io/embedded-analog-intelligence/reveal/demo_level2.htm#/" data-background-interactive-->

<div style="position: absolute; width: 40%; right: 0; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 20px; text-align: left;">
    <h2>Reveal level 2 in iframe</h2>
<p>Since reveal.js runs on the web, you can easily embed other web content. Try interacting with the page in the background.</p>
</div>

---

## Pretty code

```javascript
    import React, { useState } from 'react';

    function Example() {
      const [count, setCount] = useState(0);

      return (
        &lt;div&gt;
          &lt;p&gt;You clicked {count} times&lt;/p&gt;
          &lt;button onClick={() =&gt; setCount(count + 1)}&gt;
            Click me
          &lt;/button&gt;
        &lt;/div&gt;
      );
    }
```

Code syntax highlighting courtesy of [highlight.js](http://softwaremaniacs.org/soft/highlight/en/description/)

---

## Marvelous List

* No order here
* Or here
* Or here
* Or here

---

## Fantastic Ordered List

1. One is smaller than...
2. Two is smaller than...
3. Three!

---

## Tabular tables

| Item   | Value | Quantity |
|--------|-------|--------- |
|Apples  | $1    |     7    |
|Lemonade| $2  | 18       |
|Bread   | $3    | 2        |

---

## Clever quotes

These guys come in two forms, inline: <q cite="http://searchservervirtualization.techtarget.com/definition/Our-Favorite-Technology-Quotations">The nice thing about standards is that there are so many to choose from</q> and block:

> For years there has been a theory that millions of monkeys typing at random on millions of typewriters would
> reproduce the entire works of Shakespeare. The Internet has proven this theory to be untrue.
> -- <cite>[techtarget](http://searchservervirtualization.techtarget.com/definition/Our-Favorite-Technology-Quotations)</cite>

---

## Intergalactic Interconnections

You can link between slides internally,
[like this](#/2/3>)

---

## Speaker View

There's a [speaker view](https://github.com/hakimel/reveal.js#speaker-notes). It includes a timer, preview of the upcoming slide as well as your speaker notes.

Press the **S** key to try it out.

Notes: Oh hey, these are some notes. They'll be hidden in your presentation, but you can see them if you open the speaker notes window (hit 's' on your keyboard).

---

## Export to PDF

Presentations can be [exported to PDF](https://github.com/hakimel/reveal.js#pdf-export), here's an example:

<iframe data-src="https://www.slideshare.net/slideshow/embed_code/42840540" width="445" height="355" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:3px solid #666; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>

---

## Global State

Set <code>data-state="something"</code> on a slide and <code>"something"</code>
will be added as a class to the document element when the slide is open. This lets you
apply broader style changes, like switching the page background.

---

## State Events

Additionally custom events can be triggered on a per slide basis by binding to the <code>data-state</code> name.

```
    Reveal.addEventListener( 'customevent', function() {
	    console.log( '"customevent" has fired' );
    } );
```

---

## Take a Moment

Press B or . on your keyboard to pause the presentation. This is helpful when you're on stage and want to take distracting slides off the screen.

---

## Much more

* Right-to-left support
* [Extensive JavaScript API](https://github.com/hakimel/reveal.js#api)
* [Auto-progression](https://github.com/hakimel/reveal.js#auto-sliding)
* [Parallax backgrounds](https://github.com/hakimel/reveal.js#parallax-background)
* [Custom keyboard bindings](https://github.com/hakimel/reveal.js#keyboard-bindings)

---

# THE END

* <a href="https://slides.com">Try the online editor</a>
* <a href="https://github.com/hakimel/reveal.js">Source code &amp; documentation</a>
