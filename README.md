# Build locally
First install Jekyll according to [these instructions](https://jekyllrb.com/docs/installation/).
```bash
$ git clone https://github.com/castacks/website-dev
$ cd website-dev
$ bundle install
$ bundle exec jekyll serve --watch --incremental
```
This should start the web server locally, and enables incremental build.

# Adding your profile
Adding your profile is very simple. First follow the instructions above and launch the site. Then add a markdown page in the `_team` folder with your first name. Edit that file accordingly following the template of the other files in that folder. Also add your picture (resized to `640x480`) in the `img/team` folder. Then push those two files to the master branch of this repository and you're done!
