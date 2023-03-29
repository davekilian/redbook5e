A full, complete copy of [Readings in Database Systems, 5th Edition](http://www.redbook.io) by Bailis, Hellerstein and Stonebraker.
Includes the editor's commentary and all referenced papers, as a single combined PDF with a nice table of contents.

To build from sources, you will need a copy of the [Coherent PDF](https://community.coherentpdf.com) command line tool.
Open `build`, point `$cpdf` to your copy of the command line binary, then run `./build`.

The table of contents is generated from `./toc`.
Each line consists of a heading level (where 0 is the top level), the title of the heading, a page number, and a hitbox within that page (for linking to individual subheadings or figures within a page).
For the hitbox, we always use `open`, which means the entry should link to the page as a whole.
For more details, see the bookmarks chapter in the [Coherent PDF user manual](https://www.coherentpdf.com/cpdfmanual.pdf).
