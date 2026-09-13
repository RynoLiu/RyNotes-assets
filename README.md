# Pipeline

## Main

```bash
git add .
git commit -m "add XXX"
git push

git tag -a {date}_r{N} -m "add XXX"
git push origin {date}_r{N}
```

## Test

```bash
git ls-remote --tags origin
```
