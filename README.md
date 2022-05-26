pre-commit hook:

```
#!/bin/sh
bundle exec jekyll build
rm -r docs/
rm -r _site/docs/
cp -R _site/. docs/
cp CNAME docs/
git add docs
git restore .
git clean -f
```