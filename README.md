
# Quarto for Scientists

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

This is a course on how to use Quarto, with the target audience being for scientists. This was first developed as a short workshop on rmarkdown, as the book ["rmarkdown for scientists"](https://github.com/njtierney/rmd4sci). The general structure will be the same, and it will grow and change over time as a **living book**.

# Structure of the workshop

This online book covers more content than the workshop. Here's an example course structure for a full day's course.

| duration| topic | time  | 
|---------|-------|-------|
|30 minutes|	installation | 930
|15 minutes|	Why use Quarto | 945
|20 minutes|	Workflow when using Quarto documents and projects | 1005
|20 minutes|	Exporting Quarto documents to PDF, HTML, and Microsoft Word | 1025
|30 minutes|	BREAK | 11:00
|10 minutes|  Workflow and using keyboard shortcuts | 11:10
|30 minutes|	Managing figures, tables, and captions | 11:40
|20 minutes|	Managing equations and bibliographies | 12:00
|30 minutes|	How to debug and handle common errors | 12:30
|60 minutes|	BREAK | 13:30 | 
|30 minutes|  Other quarto formats | 14:00
|30 minutes|  Free time to convert your own documents into Quarto | 14:30
|60 minutes|  The practice of 'getting unstuck', and reproducible examples | 15:30
|30 minutes|  BREAK | 16:00
|60 minutes|  Free time for discussion around other Quarto formats: websites, blogs, slides, and more!| 17:00

This online book covers more content than the workshop. Here's an example structure of a 6 hour course.

| time    | topic |
|---------|-------|
|15 mi|	Get started with your own Quarto document | 
|9:45-2:00|	Workflow when using Quarto documents and projects |
|2:00-2:20|	Exporting Quarto documents to PDF, HTML, and Microsoft Word |
|2:30-3:00|	BREAK|
|3:00-3:30|	Managing captions, figures, tables |
|3:30-3:45|	Managing equations and bibliographies |
|3:45-4:15|	How to debug and handle common errors |
|3:45-5:00|	Free time for discussion around aother Quarto formats: websites, blogs, slides, and more!|

# Learning outcomes

After completing this course, you will know how to:

- Create your own Quarto document
- Create figures and tables that you can reference in text, and update with - your data
- Export your Quarto document to PDF, HTML, and Microsoft Word
- Use keyboard shortcuts to improve workflow
- Cite research articles and generate a bibliography

We may, depending on time, also cover the following areas:
- Change the size and type of your figures
- Create captions for your figures, and reference them in text
- Cite research articles and generate a bibliography
- Debug and handle common errors

# Getting Started

See the [installation chapter](https://qmd4sci.njtierney.com/installation) for details on software to be installed.

Working materials will be made available at [github.com/njtierney/qmd4sci-materials](https://github.com/njtierney/qmd4sci-materials).

## Book 

# Book aims

This book aims to teach the following:

- Getting started with your own Quarto document
  - Using Rstudio
  - Visual Studio Code
- Improve workflow:
  - RStudio
    - Demonstrate rstudio projects
    - Using keyboard shortcuts
  - Quarto projects
- Export your Quarto documents to PDF, HTML, and Microsoft Word
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
- Debug and handle common errors with Quarto
- Next steps in working with Quarto:
  - How to extend yourself to other formats, such as slides, websites, books, and more


# Abstract aka "why should you read this"

For a scientific report to be completely credible, it must be reproducible. The full computational environment used to derive the results, including the data and code used for statistical analysis should be available for others to reproduce.

Quarto is a tool that allows you integrate your code, text and figures in a single file in order to make high quality, reproducible reports. A paper published with an included Quarto file and data sets can (in principle) be reproduced by anyone with a computer.

# Future / extensions

Tentatively, there will also be a new part to this book, which discusses how to use Quarto in a [targets](https://github.com/ropensci/targets) pipeline. This is now my preferred way to work when starting new projects, and it draws heavily from [Miles McBain's](https://www.milesmcbain.com/) ergonomic workflow packages, [tflow](https://github.com/MilesMcBain/tflow), [fnmate](https://github.com/MilesMcBain/fnmate), [capsule](https://github.com/MilesMcBain/capsule), most of which are demonstrated in his blog post, ["Benefits of a function-based diet (The {drake} post)"](https://www.milesmcbain.com/posts/the-drake-post/).

# License 

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
