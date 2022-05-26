pre-commit hook:

```
rm -r docs/
bundle exec jekyll build
npx tailwindcss -i ./src/style.css -o _site/assets/css/style.css
cp -R _site/. docs/
rm -r _site/
git add docs
git restore .
git clean -f
```