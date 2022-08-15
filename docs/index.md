# Welcome to use MkDocs Template

GitHub: [mmdjiji/mkdocs-template](https://github.com/mmdjiji/mkdocs-template)

A template of mkdocs by [JiJi](https://mmdjiji.com), for full documentation visit [mkdocs.org](https://www.mkdocs.org).

## CI/CD
This repository uses GitHub Actions for CI/CD. You don't need to build your documents manually. Just commit your documents (then run `git push`), and then turn on the GitHub Pages in the settings to access your online documents. (For this demo is [https://mmdjiji.github.io/mkdocs-template](https://mmdjiji.github.io/mkdocs-template))

## Commands

* `pip install -r requirements.txt` - Install requirements before use
* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout
```bash
mkdocs.yml     # The configuration file.
.github/
    workflows/ # For the GitHub Actions
docs/
    index.md   # The documentation homepage.
    ...        # Other markdown pages, images and other files.
```

## Themes
You can use the following code (add them to `mkdocs.yml`) to change your theme (default: `mkdocs`):
```yaml
theme:
  name: mkdocs
```

There are many choices for you:

|theme's name|
|-|
|mkdocs|
|readthedocs|
|material|

Of course, I would like to use `material` theme because of its simple and elegant.

## License
Follows [mkdocs/mkdocs](https://github.com/mkdocs/mkdocs), use [BSD-2-Clause](LICENSE).