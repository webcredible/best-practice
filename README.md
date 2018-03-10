This site has been put together using [Jekyll](https://jekyllrb.com/) for ease of hosting, maintainability and portability. We have only used plugins [supported by Github Pages][plugins], to keep dependencies to a minimum.

Developing locally
------------------

You'll want to be at least a little familiar with the command line. Jekyll uses Ruby, you'll need that to be installed as well as RubyGems and Bundler.

The Ruby website has a guide on [install Ruby and RubGems][install-ruby]. Once you've got them set up, install Bundler like so:

```
$ gem install bundler
```

You'll need to have a local copy of the project. Clone the latest version using git:

```
$ git clone git@github.com:webcredible/best-practice.git
```

Then install the dependencies using Bundler:

```
$ bundle install
```

You can now develop locally. To preview the site during development, at [localhost:400](http://localhost:400):

```
$ bundle exec jekyll serve
```


[install-ruby]: https://www.ruby-lang.org/en/documentation/installation/
[jekyll]: https://jekyllrb.com/
[plugins]: https://pages.github.com/versions/


&copy; Webcredible, 2018. All rights reserved.
