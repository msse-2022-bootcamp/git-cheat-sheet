# Git Cheat Sheet

Feel free to use this cheat sheet for yourself or for teaching workshops. You can see it rendered
as an HTML page [here](https://msse-2022-bootcamp.github.io/git-cheat-sheet/) or download it as a PDF
file [here](git-cheat-sheet.pdf).

## Contributing
### Editing the Markdown file.
The cheat sheet is written as a single Markdown file and published as a Github page using the minimal theme. We recommend using [Typora](https://typora.io/) to edit the markdown file locally. 

### Previewing the rendered HTML page
If you want to preview the rendered web page, setup Jekyll using the instructions [on this page](https://help.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll). 

### Previewing the PDF file
The PDF version is automatically generated using [wkhtmltopdf](https://wkhtmltopdf.org/). I have not found an easy way to preview how the PDF will look after the changes when using Jekyll locally. As a workaround, you can always run it on your fork first, after you enable gh pages, with the following syntax:

```bash
wkhtmltopdf https://joaorodrigues.github.io/git-cheat-sheet/ git-cheat-sheet.pdf
```

## License
Licensed under CC BY-SA 4.0, for details see [LICENSE.md](LICENSE.md).
