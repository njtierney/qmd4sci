# Quarto for Scientists


<!-- README.md is generated from README.qmd. Please edit that file -->

<!-- badges: start -->

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This
work is licensed under a
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative
Commons Attribution-NonCommercial 4.0 International License</a>.
<!-- badges: end -->

This is a course on how to use Quarto, with the target audience being
for scientists. This was first developed as a short workshop on
rmarkdown, as the book [“rmarkdown for
scientists”](https://github.com/njtierney/rmd4sci). The general
structure will be the same, and it will grow and change over time as a
**living book**.

## Prerequisites

- Basic familiarity with R or Python
- Experience writing scripts or data analysis code
- No prior experience with Quarto or R Markdown required

## Learning outcomes

- Write your own Quarto document from scratch
- Best practices for project workflow with Quarto
- Rendering Quarto to HTML, PDF, and Word
- Managing dynamic referencing and creating captions for figures and
  tables
- Managing bibliographies, reference systems
- Handling common errors in Quarto
- Using Quarto to render slides, websites, and books

This course will also end with an (optional) capstone assessment, where
you submit a document you created with Quarto to Nick, and he will
review the writing, code, and project with you.

## Course website

<https://qmd4sci.njtierney.com>

## Details

For an analytic report to be completely credible, it must be
reproducible. The full computational environment used to derive the
results, including the data and code used for statistical analysis
should be available for others to reproduce.

Quarto is a tool that allows you integrate your code, text, and figures
into a single file. This allows you to create high quality, reproducible
reports. A paper published with an included Quarto file and data sets
can (in principle) be reproduced by anyone with a computer.

## Schedule

This course is structured into 6 parts, each approximately 1 hour long.

### Part 1: Introduction and Basic Documents

- Why Quarto?
  - Reproducible research and computational credibility
  - Integrating code, text, and figures
  - Benefits over traditional document workflows
- Installation and setup
  - Install Quarto and verify setup
  - RStudio integration
  - Download course materials:
    `usethis::use_course("njtierney/qmd4sci-materials")`
- Your first Quarto document
  - Create a .qmd file
  - Understand YAML headers
  - Basic markdown syntax
  - Code chunks and execution
- The Quarto workflow
  - Rendering documents
  - Using keyboard shortcuts (Cmd/Ctrl + Shift + K)
  - Visual mode vs source mode
  - Best practices for organization

### Part 2: Multiple Output Formats

- Rendering to different formats
  - HTML, PDF, and Word outputs
  - Format-specific YAML options
  - When to use each format
  - Troubleshooting PDF rendering
- Keyboard shortcuts for efficiency
  - Insert code chunks (Cmd/Ctrl + Option + I)
  - Run code: current chunk, all chunks
  - Navigation and editing shortcuts
  - Customizing your workflow
- Hands-on practice
  - Render the same document to HTML, PDF, and Word
  - Explore format-specific options
  - Compare outputs and discuss trade-offs

### Part 3: Figures and Tables

- Working with figures
  - Including figures from code
  - Adding figure captions with `#| fig-cap:`
  - Figure labels with `#| label: fig-name`
  - Cross-referencing figures with `@fig-name`
- Customizing figure appearance
  - Figure dimensions: `fig-width` and `fig-height`
  - Figure alignment and layout
  - Multiple figures in one chunk
  - Subfigures and complex layouts
- Creating and formatting tables
  - Basic tables with `knitr::kable()`
  - Table captions and labels
  - Cross-referencing tables with `@tbl-name`
  - Other table packages: {gt}, {flextable}
- Practical exercise
  - Create a document with multiple captioned figures
  - Add properly formatted tables
  - Practice cross-referencing in text

### Part 4: Mathematics and Cross-References

- Mathematical notation
  - Inline math with `$...$`
  - Display equations with `$$...$$`
  - LaTeX syntax essentials
  - Equation environments
- Labeling and referencing equations
  - Adding equation labels
  - Referencing equations in text
  - Numbered vs unnumbered equations
- Cross-referencing system
  - Figures: `@fig-label`
  - Tables: `@tbl-label`
  - Equations: `@eq-label`
  - Sections: `@sec-label`
- Hands-on exercise
  - Write a document with equations
  - Create a complete cross-referencing system
  - Practice mathematical typesetting

### Part 5: Citations and Bibliographies

- Setting up citations
  - Creating and using .bib files
  - Citation syntax: `@author2020` vs `[@author2020]`
  - Multiple citations and page numbers
  - Citation management tools (Zotero, etc.)
- Bibliography styles
  - Changing citation styles (CSL files)
  - Common styles: APA, Nature, Chicago
  - Where to find CSL style files
  - Customizing bibliography appearance
- Practical exercise
  - Add citations to your document
  - Create a bibliography
  - Try different citation styles
  - Combine citations with cross-references
- Common problems and debugging
  - YAML syntax errors
  - Missing packages and dependencies
  - File path issues
  - Using reproducible examples to get help

### Part 6: Advanced Topics and Personal Projects

- Alternative outputs and extensions
  - Creating presentations with {revealjs}
  - Websites and blogs
  - Books with Quarto
  - Journal article formats and templates
- Quick demonstrations
  - Build a simple presentation
  - Overview of Quarto websites
  - Extension ecosystem
- Converting your own documents
  - Bring your Word/LaTeX documents
  - Convert to Quarto format
  - Hands-on conversion with instructor help
  - Troubleshoot individual challenges
- Next steps and resources
  - Quarto documentation and community
  - Advanced features to explore
  - Integrating Quarto into your workflow
  - Open Q&A

# Getting Started

See the [installation
chapter](https://qmd4sci.njtierney.com/installation) for details on
software to be installed.

Working materials will be made available at
[github.com/njtierney/qmd4sci-materials](https://github.com/njtierney/qmd4sci-materials).
<!-- 
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
  - How to extend yourself to other formats, such as slides, websites, books, and more -->

<!-- # Abstract aka "why should you read this"
&#10;For a scientific report to be completely credible, it must be reproducible. The full computational environment used to derive the results, including the data and code used for statistical analysis should be available for others to reproduce.
&#10;Quarto is a tool that allows you integrate your code, text and figures in a single file in order to make high quality, reproducible reports. A paper published with an included Quarto file and data sets can (in principle) be reproduced by anyone with a computer. -->

<!-- # Future / extensions
&#10;Tentatively, there will also be a new part to this book, which discusses how to use Quarto in a [targets](https://github.com/ropensci/targets) pipeline. This is now my preferred way to work when starting new projects, and it draws heavily from [Miles McBain's](https://www.milesmcbain.com/) ergonomic workflow packages, [tflow](https://github.com/MilesMcBain/tflow), [fnmate](https://github.com/MilesMcBain/fnmate), [capsule](https://github.com/MilesMcBain/capsule), most of which are demonstrated in his blog post, ["Benefits of a function-based diet (The {drake} post)"](https://www.milesmcbain.com/posts/the-drake-post/). -->

# License

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This
work is licensed under a
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative
Commons Attribution-NonCommercial 4.0 International License</a>.
