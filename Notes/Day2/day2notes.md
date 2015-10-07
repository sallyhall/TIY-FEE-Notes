# Front End Engineering Day 2
## October 7, 2015

- Chrome Inspector
  - Ctrl Click an element
  - Choose inspect element
  - opens a window with html for the page that you can look through
  - also shows associated styles

- Box Model
  - **Padding**: space between content and border
  - **Border**: edge of the Box
  - **Margin**: space between the box and other things
  - Margin/padding act like a clock:
    `margin:10px 9px 8px 7px`: 10 is top, 9 is right, 8 is bottom, 7 is left
  - if you just do two, they are top/bottom, left/right
  - padding is inside the element, margin is outside the element
  - multiple classes on one div are applied in the order they appear in the stylesheet, not the order in which they are listed in the html

- Specificity: What takes priority over other elements. Takes precedence over cascading order.
  1. **ID**: `#square` takes precedence over classes
  2. **Class**: takes precedence over elements (class above div, for example)
  3. **Element**: last in line: div, p, etc. Overridden by class and ID

- Normalize
 - Download normalize.css from github
 - link it before your stylesheet to cancel out user agent stylesheet (browser specific styling)
 - https://github.com/necolas/normalize.css/blob/master/normalize.css

#### Positioning

- Display
  - **block**: Elements (div, p, etc) take up the entire width of the page, which means they stack on top of each other; this is the default
  - **inline-block**: only takes up as much space as the total of element+padding+border+margin. elements can be next to each other if there is enough space
  - **none**: don't display the element on the page (different that visibility:hidden where the element is there, you just can't see it)

- Float
  - **left**: start on the left, go left to right. fits elements next to each other if there is enough space.
  - **right**: start on the right, go right to left. fits elements next to each other if there is enough space. this ends up being reverse order of float left
  - set **clear** as a property on the element that you want to avoid the ones that have been floated.

- Position
  - **relative** positioned relative to parent container
  - **fixed** fixed relative to parent container
  - `top: 100px` move down 100px, same for left, right, bottom


#### Git
 - `git init`: initialize new repository inside the directory that you are in
 - `git status`: shows the status of files in your repository. red ones are untracked.
 - `git add --all`: adds the files in your directory to your repository. now status will show those files as green.
 - `git commit -m "this is the initial commit that has billmurray blog with a stylesheet and a normalize file"`: commits files that have been changed with the given message. now status will show nothing to commit.
 - `git diff <filename>`: will tell you the differences between your local file and the one that is committed.
 - `git log`: shows a log of commits
 - `git remote -v`: shows where the remote is set up
 - 'git push origin master': pushes the latest commit to the remote called origin and the branch called master (puts your changes on github)
