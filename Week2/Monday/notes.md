#Front End Engineering Notes
##October 12, 2015

####Responsive
 - Styling changes to fit the viewport.
 - **viewport**: what is visible within the browser
 - Don't want the user to have to scroll horizontally
 - Think about what you want the user to focus on as the screen shrinks
 - separate layout from content. one way is to use a div with class content around the content inside the layout div

####Media Queries
 - limit scope based on resolution and other media properties
 - don't set your breakpoints based on sizes of various devices
 - set breakpoints based on where the site becomes unusable as you resize
 - 320px wide is the smallest you need to worry about

####Font sizes
 - different ways to size fonts:
  - **px** - strict pixels
  - **em** - relative to parent unit - inherits font sizes of all parent classes
  - **rem** - relative to html(root) unit
