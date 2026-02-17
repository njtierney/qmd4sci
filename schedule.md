
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
  - Download course materials: `usethis::use_course("njtierney/qmd4sci-materials")`
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

---

Notes:
- Each part is approximately 1 hour
- Follows the qmd4sci book structure
- Emphasizes hands-on practice throughout
- Includes time for converting personal documents
- Scaffolds from simple to complex topics