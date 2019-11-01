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
  - Relative to viewport
    - vw, vh, vmin, vmax