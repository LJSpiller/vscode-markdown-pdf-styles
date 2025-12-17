# vscode-markdown-pdf-styles
![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)
![Made with VS Code](https://img.shields.io/badge/Made%20with-VS%20Code-blue?logo=visual-studio-code)

Tutorial and assets to create styled PDFs from Markdown in Visual Studio Code.

## Export styled Markdown to PDF for technical writing

Using Visual Studio Code is great for working with code samples, but raw Markdown files aren't usually an acceptable file format for final portfolio samples or shareable work documents.

Visual Studio Code relies on Chromium for PDF support. Sometimes the renderer used for VS Code extensions that export PDF can't render colors, emojis, or formatting styles correctly, so a raw Markdown file that is directly exported to PDF may not meet professional formatting standards when using these extensions. For example, a green circle emoji used for a 200 HTTP status will appear as a black-and-white line emoji. Likewise, it is difficult to add a header to mark a code sample's language or create callouts and warnings that are easy to identify.

The workaround for successfully creating a PDF document from a Markdown file is to export the document as an HTML file using the **Markdown PDF** Visual Studio Code extension. The HTML format preserves the formatting in the Markdown file and allows you to save the file as a PDF with the same formatting intact by using the "print to PDF" printing command in a browser.

You can control the formatting for code samples, headings, lists, inline elements, table positioning, callouts, diagrams, and even emoji rendering by using a custom `markdown-pdf.css` with the Markdown PDF extension.

This tutorial explains how to use a custom CSS style sheet with the Markdown PDF extension to create professional technical documentation as PDFs.

---

## View the final output

This repository demonstrates the solution in action. The `tutorial.pdf` file showcases:

* **Custom code block labels** ("H4 header fix")
* **Styled inline code** (Gray background)
* **Styled callout boxes** (NOTE, CAUTION, and TIP)
* **Custom status codes** (Green/red circle emojis)
* **Manual page breaks**

**[View the final styled PDF](tutorial.pdf).**

*This PDF is the primary artifact of this repository and demonstrates all of the custom formatting.*

---

## Files in this repository

| File Name | Purpose |
| :--- | :--- |
| **`tutorial-source.md`** | The source Markdown file with all custom syntax and the style sheet. |
| **`markdown-pdf.css`** | The custom style sheet required to generate the styled output. |
| **`markdown-to-pdf-demo.md`** | A demonstration file showing all of the styles and code snippets for major languages in action. |
| **`tutorial.pdf`** | The final styled PDF. |


## License

This tutorial and its assets are licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

You may share this work with attribution for non-commercial purposes, but you may not remix or reuse it in derivative works.
