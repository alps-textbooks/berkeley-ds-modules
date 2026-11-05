# About This Book

![2Sigma School](2sigma-school-logo.svg)

**UC Berkeley Data Science Modules** · *Data science modules from UC Berkeley courses across disciplines*

**2Sigma School** · Alps edition · Updated October 2026

These modules bring data science into UC Berkeley courses across disciplines: Python and Jupyter basics, then applied labs in legal studies, psychology, English and city planning. This Alps edition keeps the authors' words and runs the notebooks in the page, with nothing to install.

| At a glance | |
|---|---|
| **394 code cells** | Python that runs in the browser |
| **36 of them for reference** | Code that needs data or services a reader cannot reach from the page, shown as written |

## How to Use It

Each module is a notebook. Run a cell on its own, or choose **Run all cells** in the toolbar to run the page from the top. Cells shown for reference stay on the page, cannot be edited, and are stepped over by Run all. Some cells have a blank for you to fill in, and show an error until you do. To use your own data, choose **Upload File** in the toolbar.

> **Found a problem?** Teachers: choose Report Bug in the left menu, then select the bug icon on the item, or highlight the text. Students: tell your teacher. You can also email [support@alps.2sigma.us](mailto:support@alps.2sigma.us) with the book, chapter and page name.

## Credits

*The Data Science Modules Textbook* is by Alex Nakagawa and Chris Pyles.

Source: [https://github.com/ds-modules/modules-textbook](https://github.com/ds-modules/modules-textbook)

License: [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).

This edition has been adapted for Alps only as far as listed below, so that its notebooks run here. As with every book on Alps, its preparation draws on Alps's content-enhancement capabilities, which include the use of language models.

The authors and UC Berkeley are not affiliated with, and do not endorse, this edition.

## Alps Compatibility Changes

These are the only changes to the notebooks, and each one is there so they run in Alps. The numbering of the book's chapters is not affected: this page comes after them.

**Cells are marked.** A cell is shown for reference when its data or service cannot be reached from the page. A blank for the reader, and each of the two cells that show an error on purpose, are marked as expected to fail.

| Notebook | Cells for reference | Expected to fail | Other changes |
|---|---|---|---|
| Intro to Python and Jupyter | | 7 | |
| Legal Studies: Intro to Python | 13 | 3 | The NCVS incident data is shared through the course only |
| Legal Studies: Problem Set 1 | 3 | | The retired SF open-data endpoint is left for reference, and the notebook keeps its bundled sample. A stray `os.path.` line is corrected to `os.path`. |
| Correlation & Regression | | | The two tables are read from `data/`, where they are |
| My Project | | 4 | The instructions say to choose **Upload File**, in place of a file browser that does not exist here, and to give the second dataset a different name |
| Chinatowns | | | spaCy is imported last in the setup cell |
| Lab 7 | | 3 | |
| Lab 8 | 20 | | Calls to the Twitter API, and the cells that read their results |
| Lab 9 | | 3 | `pwd()` is written as the `%pwd` magic |
| Lab 10 | | 22 | |
