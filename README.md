### Purpose

This repo holds highly scrutinised bits and bobs from the twitter bootstrap css framework.

### Components

#### Grid

A slightly modified version of the latest bootstrap (v3.2.0) grid:


1. Removed normalize.css as it's a dependency of the app anyway.
2. Added ``box-sizing: border-box`` to all the grid elements: container(-fluid), row, col-(..)-(..)
3. Added ``screen`` to all the @media queries (for it to play nice with css3-mediaqueries.js
