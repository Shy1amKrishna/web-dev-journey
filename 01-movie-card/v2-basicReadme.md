# Movie Card - v2 (Improved)

An upgraded version of the movie card, focused on making it look modern 
and more like a real app UI, instead of a plain boxed layout.

## What changed from v1

- Replaced the deprecated `<center>` tag with **Flexbox** (`display: flex`) 
  for centering
- Used a **class** (`.movie-card`) instead of styling the `<div>` tag 
  directly, so different elements can be styled independently
- Added `box-sizing: border-box` so padding no longer distorts element width
- Added `border-radius` for rounded corners on the card and rating badge
- Added `box-shadow` to give the card a sense of depth/elevation
- Added a `:hover` state with `transition` so the card lifts slightly on 
  mouse-over
- Used `object-fit: cover` on the image so it fills its box cleanly
- Imported a Google Font (Poppins) instead of the default browser font
- Moved the red color from the entire card background to just the button, 
  so it acts as a single accent color instead of overwhelming the design

## Screenshot

![v2 improved movie card](screenshot.png)

## Next steps

Planning to add more interactivity next (e.g. button click behavior with 
JavaScript) as I move further into the course.
