pre-commit hook:

```
#!/bin/sh
rm -r docs/
bundle exec jekyll build
rm -r _site/docs/
cp -R _site/. docs/
cp CNAME docs/
cp -a src/. docs/ 
git add docs
git restore .
git clean -f
```