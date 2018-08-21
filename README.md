# Eat Better Lifestyle

GitHub Pages Website

## Developing

### Adding Content

* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 
* This site is built using [mkdocs](https://www.mkdocs.org/)
* At the shell, run `mkdocs -h` for instructions

```shell
▶ mkdocs -h
Usage: mkdocs [OPTIONS] COMMAND [ARGS]...

  MkDocs - Project documentation with Markdown.

Options:
  -V, --version  Show the version and exit.
  -q, --quiet    Silence warnings
  -v, --verbose  Enable verbose output
  -h, --help     Show this message and exit.

Commands:
  build      Build the MkDocs documentation
  gh-deploy  Deploy your documentation to GitHub Pages
  new        Create a new MkDocs project
  serve      Run the builtin development server
```

* Run locally to see your changes as you make them: `mkdocs serve`
* Navigate to http://127.0.0.1 in your browser

### Saving, Pushing

```shell
git add <name of files you changed>
git commit -m "Message about what you changed"
git push
```

```shell
mkdocs gh-deploy
```