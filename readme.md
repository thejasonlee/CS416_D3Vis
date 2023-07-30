This is a simple project I completed as part of an assignment for Data Visualization, CS416, at UIUC for the MCS program.

This project uses vanilla D3.js to generate a couple of charts, with some basic interactivity.

The data used is read in from a CSV stored in a github repo and is tiny in size (~150 records). 

While small, this project shows many features:
- async javascript to load data
- dynamic creation of svg objects and canvasses
- javascript to adjust the CSS and HTML of elements
- the chainability of d3
- use of D3 scales (linear, band, log)
- the selectAll(), data(), enter() pattern to create many objects quickly
- event-based programming, using event listeners
- many story-telling features (like scenes, parameter passing, consistency between scenes for user orientation, etc)
