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
