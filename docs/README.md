# Start Server
bundle exec jekyll serve
## Start Server with Live Reload
bundle exec jekyll serve --incremental

# Build
bundle exec jekyll build

# SCSS
scss assets/scss/custom.scss assets/css/main.css
## Live Update SCSS
sass --watch assets/scss/custom.scss:assets/css/main.css