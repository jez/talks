# talks

I've been lucky enough to have given a number of talks on subjects I care about.
This site acts as a repository of the talk descriptions and slides in the hopes
that they might be useful.

<https://jez.io/talks/>

Sources for many of my talks are here too:

- [slides/](slides)

## Theme

This site uses the [Tufte Pandoc Jekyll] theme, which combines tufte-css with
Pandoc Markdown (including support for tufte-css-style sidenotes!).

[Tufte Pandoc Jekyll]: https://github.com/jez/tufte-pandoc-jekyll


## Developing

### One-time Setup

I use `virtualenvwrapper` to manage my Ruby projects.
It's a bit of a hack, but it works.
Follow the setup here:

- <https://blog.jez.io/ruby-virtualenvs/>

Then:

```
mkvirtualenv talks
gem install bundler
bundle install
deactivate
```

### Using

```shell
# Start working on this project
workon talks

# Preview the site
jekyll serve

# Add a post (set the --date to when the talk was/will be given)
octopress new post --date YYYY-MM-DD foo-bar

# Publish changes to GitHub pages
octopress deploy

# To reset your PATH (i.e., to work on another project)
deactivate
```

## License

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://jez.io/MIT-LICENSE.txt)



