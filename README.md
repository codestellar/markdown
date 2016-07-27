# pandoc-bootstrap-template

=========================

Bootstrap template for Pandoc - Converts markdown files into Twitter Bootstrap styled HTML

## Usage example

 pandoc in.md -o out.html --template template.html --css template.css --self-contained --toc --toc-depth 2

 pandoc interview-questions.md -o interview-questions.html --template template.html --css template.css --self-contained --toc --toc-depth 2

 pandoc interview-questions.md  -o interview-questions.docx

 Source: [https://github.com/tonyblundell/pandoc-bootstrap-template](http://link)

 The template from the source is modified and includes:

 *Sticky Side bar
 *Nice Scrolling effects for the side menu
 *Bootstrap skin is changed.

Recommendation: Use [VSCode](https://code.visualstudio.com) to generate markdown files and use vscode extensions.

*[markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
*[vscode-pandoc](https://marketplace.visualstudio.com/items?itemName=DougFinke.vscode-pandoc)
*[download pandoc](https://github.com/jgm/pandoc/releases/tag/1.17.2)

*To preview a markdown file Ctrl+K, V
*To generate html, docx, pdf use Ctrl+K, P