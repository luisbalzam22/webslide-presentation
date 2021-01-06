# Web-Slide Presentation

This is a pretty old (from my early days as front-end dev), yet, neat slide presentation component made with just **HTML, CSS and jQuery**.

- Perfect for presentations where you need to display images and text without exaggerated animations.
- You only need a web browser to make it work
- You don't need to worry about being online to make it work: both, fontawesome (v5) and jQuery (v3.4.1) are included in the repo.
- Just a couple lines of code in reusable jQuery script (useful for other things, like smooth sliding through a website).

## How to use:

- Follow these steps (or, you can just copy and modify one of the example slides):
  - Add a new **&lt;section&gt;&lt;/section&gt;** element in the index.html file, then, include the new HTML content inside it.
  - Give that **&lt;section&gt;** an id attribute and a "page" class. E.g.: **&lt;section id="slide-5" class="page"&gt;&lt;/section&gt;**
  - Add **&lt;a&gt;&lt;/a&gt;** element(s) for navigation between slides (for previous and next slide). Such anchor(s) must link to the specific slide we want to scroll to (please, note the # symbol; necessary to "go" to the other slide). E.g.: **&lt;a href="#slide-4"&gt;** Previous slide **&lt;/a&gt;**
- Go to the style.css file and copy the commented slide color assignment boilerplate code, specify the color you want and save.
- Open the index.html file and you're good to go.

#### Note: Since this is a basic project from my early days as front-end dev, slides must be added manually, and it's pretty much targetted at developers, since there's no interface to, at least, manage creation, deletion and modification of slides; however, those features will likely be added in the future (whenever I find some time :D).
