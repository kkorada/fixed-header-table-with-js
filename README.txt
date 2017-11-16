A Pen created at CodePen.io. You can find this one at https://codepen.io/paulobrien/pen/NvxNyY.

 Answer to question on Sitepoint forums:

https://www.sitepoint.com/community/t/flexible-html-table-with-fixed-header-and-footer-around-a-scrollable-body/271162

I've only just knocked this up a few minutes ago so needs testing.

It also assumes that you won't be having form fields or the like in the cells because the way this works is that the table is cloned and then positioned on top of the original table with absolute positioning. The original table is in a div that allows the table to scroll horizontally while the cloned div is placed out of that context and does not scroll.

The cells in the cloned table are hidden with css except for the first column. That allows the illusion of a fixed first column.