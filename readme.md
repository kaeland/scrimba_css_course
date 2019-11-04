# Scrimba CSS Course

## Absolute Units: 
  - Pixels (px)
  - pt, cm, mm, in, etc...

## Percentage Units:
  - Percentages are mainly used for widths
  - Relative to their parent (except on height, where things get weird)

## Relative Units: 
  There are two types of relative units: 
  - Relative to font-size
    - em and rem (and many other less common ones)
    - which font-size these units are relative to is a little complicated
    - **em are relative to their partent's font-size**
    - font-size is an inherited property, so if you don't declare it anywhere, it's getting it from the body (or the default, which is normally 16px)
    - The rem unit is short for **Root Em**
      - That means it is always relative to the root of our document.
      - **The root of an HTML page is always the HTML element.**
  - Relative to viewport
    - vw, vh, vmin, vmax
  - General Rule of Thumb: 
    - font-size: rem 
    - padding & margin: em
    - widths: em or percentage