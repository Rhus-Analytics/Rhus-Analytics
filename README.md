
# About the Rhus Anaytics web site

This website is served with [Jekyll](https://jekyllrb.com/), which github pages supports.

To make changes, clone the repository, make the changes, and them make a pull-request back.
Simple changes can be made by editing existing files (summary to come). 

If you want to view your changes *before* pushing them back into the public website (and to makes ure you didn't break anything),
you need to install Jekyll - follow instructions at https://jekyllrb.com/docs/installation/.
Then run bundle install to install "gems" (i.e. packages used by the jekyll-site).
Running Jekyll locally will serve a website *locally*.

Finally, you can run Jekyll and have it update and refresh your local website whenever you modify one of the files.
Do so by running `jekyll serve`.
No more tedious save - recompile - refresh.

## Theme

The current theme is "minima" (https://github.com/jekyll/minima).
The files for layout etc. are not stored locally, but found in a "gem" - 
however, if we want to modify it, we simply bring it into this respository at with the same
relative path.
