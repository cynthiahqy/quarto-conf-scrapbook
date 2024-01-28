To get the template via the GitHub cli:
```zsh
gh repo create --template cynthiahqy/quarto-conf-scrapbook
```

The "scrapbook" renders like any other Quarto project
```zsh
quarto render
```

To version control the rendered site, remove the following line from `.gitignore`:
```
_site/*
```
