# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

## Heroku Setup:

Firstly, check whether system install heroku:
$ heroku --version

If not, install it using following command:
$ source <(curl -sL https://cdn.learnenough.com/heroku_install)

Heroku Deploy:

Once heroku has been installed in your system, create a remote git repo in heroku:
$ heroku create

To Deploy changes to Heroku, simply push current changes to heroku:
$ git push heroku master

My heroku website is: https://dashboard.heroku.com/apps
Repo for this app: https://dashboard.heroku.com/apps/obscure-crag-65125

## Rails command shortcut table

Full command    |    Shortcut
$ rails server       $ rails s
$ rails console      $ rails c
$ rails generate     $ rails g
$ rails test         $ rails t
$ bundle install     bundle