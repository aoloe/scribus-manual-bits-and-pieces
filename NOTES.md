# Notes

## Measurements, units and variables

In Scribus, most fields where you can define a measurement will allow you to do some calculation.

Those calculations can contain measurement units (cm, mm, in, ...) and a few variables.

A few examples:

- If you want to resize and move a frame to fill the right side of a page, you can set both its
width and x position to `pagewidth / 2` in the properties palette.
- If you're using "mm" as your measurement unit but want to set the height of an image frame to "24 pt" (matching the height of a text line) you can just type that value in the properties palette.
- Some of the "variables" that are available:
  - `pagewidth` and `pageheight`
  - `marginleft` and `marginright`
