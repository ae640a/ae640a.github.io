# Autonomous Navigation

This repository holds the sources for the course homepage for Autonomous Navigation,
a course at the Indian Institute of Technology, Kanpur, India.

For more information, visit the course homepage: [https://ae640a.github.io](https://ae640a.github.io)

## Contributing

The site itself uses [GitHub Pages][] and [Jekyll][].

Before contributing, please check [open issues][] and create a [new issue][] if a one for your proposed contribution does not exist.

Content for the website is written in [Markdown][].

In order to build the site locally on your __Ubuntu__ computer, there are a
number of dependencies to resolve first:

```bash
$ sudo apt-get install ruby ruby-dev build-essential patch zlib1g-dev liblzma-dev nodejs
$ sudo gem install jekyll bundler
$ bundle install
$ bundle exec jekyll serve # serves site at http://127.0.0.1:4000
```

For more information on setting up, see [GitHub's guide][gh docs] or [Jekyll's documentation][jekyll docs].

After making a change and verifying that it works, please submit a [pull request][].

---------------------

[GitHub Pages]: https://pages.github.com/
[Jekyll]: https://jekyllrb.com/
[open issues]: https://github.com/ae640a/ae640a.github.io/issues
[new issue]: https://github.com/ae640a/ae640a.github.io/issues/new
[Markdown]: http://daringfireball.net/projects/markdown/
[ruby]: https://www.ruby-lang.org/en/
[bundler]: https://bundler.io/
[gh docs]:https://help.github.com/articles/using-jekyll-with-pages/
[jekyll docs]: https://jekyllrb.com/docs/home/
[pull request]: https://github.com/ae640a/ae640a.github.io/pulls
