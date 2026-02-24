# Markdown to HTML compiler

![](https://github.com/yyuan29/project001/actions/workflows/doctests.yaml/badge.svg)&nbsp;
![](https://github.com/yyuan29/project001/actions/workflows/flake8.yaml/badge.svg)&nbsp;
![](https://github.com/yyuan29/project001/actions/workflows/command_line.yaml/badge.svg)&nbsp;

A simple project for converting markdown files to HTML.

Basic usage:
```
$ markdown-compiler example/README.md
```

<img src='examples/example.png' width=300px>

Fancy CSS formatting can be included with the flag `--add_css`:
```
$ markdown-compiler example/README.md --add_css
```

<img src='examples/example-css.png' width=300px>
