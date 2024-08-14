This is a skeleton Quarto website with some example pages that could be used to capture notes from a conference or similar event. This template and the example in the [posit-conf-2023](https://github.com/cynthiahqy/quarto-conf-scrapbook/tree/posit-conf-2023) branch were prepared for the talk "Quarto for Knowledge Management" at posit::conf(2024).

To get copy the template to a new GitHub repo and clone it locally via the GitHub cli:
```zsh
gh repo create [new-repo-name] --template cynthiahqy/quarto-conf-scrapbook --private --clone
```

The "scrapbook" renders like any other Quarto project
```zsh
quarto render
```

To version control the rendered site, remove the following line from `.gitignore`:
```
_site/*
```

To add the template to an existing local directory or repo (with Quarto v1.2 or above installed):
```zsh
quarto use template cynthiahqy/quarto-conf-scrapbook
```
