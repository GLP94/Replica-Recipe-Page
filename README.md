<h1>Recipe Page</h1>

![cop1](https://github.com/user-attachments/assets/5942fa54-c5c5-45c0-bd37-0c464b9ff99b)

This is an attempt at one of the tasks featured in the [FrontEnd Mentor](www.frontendmentor.io) site.
The task is to simply replicate an example of a recipe, with different assets and instructions already provided with the task.
The page was also made for smaller screen (420px ~ 320px).

Link to page: https://glp94.github.io/Replica-Recipe-Page/

<h2>Tools used</h2>

1. HTML
2. CSS

<h2>What Was Learned</h2>

* While `div` is often used as a container,  `section` has more semantic meaning for the document;
* Using "utility" classes like `bold` to apply the bolding to the `span` elements in the paragraphs gives more flexibility;
* `@font-face` had to be used, since the fonts were provided. It'll probably add more loading time to the page, because of the download requirements of the fonts;
* `display: flex` was used to distance the elements in the nutrients section.
* To make the image's width fully stretch to the sides of the screen, when below 420px, a combination of `margin-left` and `margin-right` were used with a negative value in px (i.e. -40px).

<h2>What Needs Work</h2>

* I still get stuck in the beginning, when defining the HTML of the page, boilerplate aside;
* Struggled with the positioning of the `li` items (resolved by applying `margin-left`);
* Also struggled with the positioning of the paragraphs at the end of the document (resolved by applying `padding` the the entire paragraph, then applying a `margin-right` of 40% to the span element, so that it would place itself correctly on smaller screens);
* There was not much usage of the `div` elements in the document. I'm still not sure were or when they are needed to be used, aside from wrapping elements for positioning/styling.

<h2>Notes</h2>

Any suggestions or criticisms are welcome
