# Your Location

## Set up
This website was created with [Jekyll](https://jekyllrb.com/docs/). I already have Jekyll site ready, you just need to run it locally.After you fork this repo, do the following to get set up:

1. Install a [Ruby environment](https://jekyllrb.com/docs/installation/) per Jekyll's documentation. 
2. Run `gem install jekyll bundler` in your terminal to install Jekyll
3. Run `bundle` in your to terminal to install all dependencies. 
4. Run `bundle exec jekyll serve --livereload`. See the documentation for [command line usage](https://jekyllrb.com/docs/usage/) if you have any questions. 
5. Check http://localhost:4000 to see if you're in business. 

## How Jekyll Works
Now that you have Jekyll running locally, you'll notice a new directory has appeared: `_site`. This directory is the complete site output that gets generated by Jekyll. You'll notice there's all of the pages, CSS, and JS compiled and ready for the world. This is what you need to host. You'll notice The homepage (`index.html`) is served from the root, but the privacy policy is served from the `privacy-policy` directory. I used [Jekyll's Collections feature](https://jekyllrb.com/docs/collections/) to keep my content organized and adding a custom [permalink](https://jekyllrb.com/docs/permalinks/) means it will be served from a named directory with an `index.html` file. So the path is `/privacy-policy/index.html` but we want the user to access it via `/privacy-policy/`.

Jekyll has [additional documentation](https://jekyllrb.com/docs/deployment/) on deployments if you need further guidance. 

