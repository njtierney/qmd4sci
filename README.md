
# quarto for Scientists

[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip)  <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

This is a book on how to use quarto, with the target audience being for scientists. It was initially developed as a 3 hour workshop, focussed on rmarkdown, as the book ["rmarkdown for scientists"](https://github.com/njtierney/rmd4sci). It is now undergoing a transformation to change into a book about using quarto instead of rmarkdown. The general structure will be the same, and it will grow and change over time as a **living book**.

This book aims to teach the following:

- Getting started with your own quarto document
  - Using Rstudio
  - Visual Studio Code
- Improve workflow:
  - RStudio
    - Demonstrate rstudio projects
    - Using keyboard shortcuts
  - Quarto projects
- Export your quarto documents to PDF, HTML, and Microsoft Word
- Better manage figures and tables
    - Reference figures and tables in text so that they dynamically update
    - Create captions for figures and tables
    - Change the size and type of figures
    - Save the figures to disk when rendering a document
- Work with equations
    - Inline and display
    - Caption equations
    - Reference equations
- Manage bibliographies
  - Cite articles in text
  - Generate bibliographies
  - Change bibliography styles
- Debug and handle common errors with quarto
- Next steps in working with quarto:
  - How to extend yourself to other formats, such as slides, websites, books, and more

Tentatively, there will also be a new part to this book, which discusses how to use quarto in a [targets](https://github.com/ropensci/targets) pipeline. This is now my preferred way to work when starting new projects, and it draws heavily from [Miles McBain's](https://www.milesmcbain.com/) ergonomic workflow packages, [tflow](https://github.com/MilesMcBain/tflow), [fnmate](https://github.com/MilesMcBain/fnmate), [capsule](https://github.com/MilesMcBain/capsule), most of which are demonstrated in his blog post, ["Benefits of a function-based diet (The {drake} post)"](https://www.milesmcbain.com/posts/the-drake-post/).

# Abstract aka "why should you read this"

For a scientific report to be completely credible, it must be reproducible. The full computational environment used to derive the results, including the data and code used for statistical analysis should be available for others to reproduce.

Quarto is a tool that allows you integrate your code, text and figures in a single file in order to make high quality, reproducible reports. A paper published with an included quarto file and data sets can (in principle) be reproduced by anyone with a computer.

After completing this course, you will know how to:

- Create your own quarto document
- Create figures and tables that you can reference in text, and update with - your data
- Export your quarto document to PDF, HTML, and Microsoft Word
- Use keyboard shortcuts to improve workflow
- Cite research articles and generate a bibliography

We may, depending on time, also cover the following areas:
- Change the size and type of your figures
- Create captions for your figures, and reference them in text
- Cite research articles and generate a bibliography
- Debug and handle common errors

# License 

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
