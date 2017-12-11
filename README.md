
# debugCSS: HTML debugging tool built with CSS

debugCSS is meant to be loaded on an existing page to highlight potentially broken, malformed or legacy HTML.

Not all "errors" are created equally, so they are color coded to highlight severity.  Green is "probably not a big problem", yellow is "worth looking at" and red is "you really should fix this."

Each condition is specified in three areas:
- Setting up the :after area for display (trying to reset common styles like colors, font sizes, etc).
- Specifying the color severity (green, yellow, red) and content (which is the error or warning message to be displayed).
- Creating the outline around the offending element according to it's color severity.
