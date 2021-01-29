# Git Precommit Hook
```bash
#!/bin/sh
cp -R _site/. docs/
git add docs
```

# Install
See [here](https://jekyllrb.com/docs/installation/macos/), then  
  
`bundle`

# Run
`bundle exec jekyll serve`  
  
then see [http://localhost:4000](http://localhost:4000)

# Technical TODOs
[ ] Integrate emailing subscriptions (again). Consider: https://tinyletter.com/
[ ] Use a theme instead of custom css. Consider: https://github.com/pages-themes/slate