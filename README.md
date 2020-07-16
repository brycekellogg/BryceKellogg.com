## Development

```shell
sudo dnf install hugo
hugo server
```

## Deployment
The website is hosted on github pages. To deploy
changes, we generate the static content, commit
everything (especially the docs/ directory) and
push:


```shell
hugo
git add --all
git commit
git push
```
