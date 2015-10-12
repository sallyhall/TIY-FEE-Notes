#Front End Engineering Day 3
## October 8, 2015

- Following along as he builds a blog layout
  - Try to style things with the fewest selectors possible:
    - not: `body header nav ul li`
    - better: `nav li`
  - an element inside another element is a child of that element.
    - `<body>
        <nav>
          <ul>
          </ul>
        </nav>
      </body`
    - `nav` and `ul` are both children of `body`. `nav` is an **immediate child** of `body`. `ul` is not.
  - How we made columns:
    - create container class div
    - create cols class divs.
    - put a bunch of cols inside a container
    - different container for each row of cols
