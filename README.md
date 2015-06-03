# Jerome-Presentation #


Markdown files and images for presenting about the Jerome project

To build a slideshow, run these steps from a terminal in this directory:

    mdpress jerome.md
    cp imgs/*jpg jerome
    cp style.css jerome/css


You can also do that in a single line:

    mdpress jerome.md && cp imgs/*jpg jerome && cp style.css jerome/css

The slide show is in `jerome/index.html`

