# Web Section Fix

The Web Development area was appearing incorrectly because a second `#projects` section had been inserted inside the first project card.

I fixed it by:

- Keeping one `#projects` section.
- Placing School Portal, School Ecosystem, and Business Website in the same `.project-grid`.
- Removing the duplicated section opening tags.
- Correcting the School Ecosystem links by removing extra spaces and the duplicated `https://`.

This lets the CSS grid control all web project cards consistently on desktop and mobile.