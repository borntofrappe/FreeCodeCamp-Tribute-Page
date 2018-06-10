# FreeCodeCamp Tribute Page

Create a tribute page for the brand new curriculum @freeCodeCamp.

Link to the working pen right [here](https://codepen.io/borntofrappe/full/oyBJJO/).

## Preface 

In order to fully redeem the new certifications offered by freeCodeCamp, I need to re-build few of the projects I built as to pass the tests established by the new curriculum.

This project in particular is centered around the creation of a tribute page. The subject of the page, freeCodeCamp itself. This for several reasons:

- I found by accident the freeCodeCamp [style guide][1] and found it both interesting and useful. Useful in terms of inspiration for a design system and practically in terms of source material for the tribute page itself;
- I wanted to implement a tribute page rapidly and couldn't immediately think of another subject.

## Plan

- start by fulfilling the user stories described by the challenge itself
- include fonts, colors and patterns as described in the cited [style guide][1]
- design the page to be responsive and pleasing to the eyes

### User Stories

The page ought to have:

- [x] an element with `id="main"`, nesting the contents of the page;

- [x] an element with `id="title"` with text describing the subject of the page;

- [x] a `div` with `id="img-div"`, nesting an `img` with `id="image"` and an element with `id="img-caption"`, with text describing the image element;

- [x] an element with `id="tribute-info"` containing a description of the subject of the page;

- [x] an anchor link `a` element with `id="tribute-link"` redirecting toward a source with additional information on the subject. 

**Additional Notes**:

- the anchor link element ought to redirect to a source in a new tab, by modifying the `target` attribute with a value of `target_blank`.

- the `img` element ought to resize itself with the window

[1]: https://design-style-guide.freecodecamp.org/
