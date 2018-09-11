# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](http://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).


## Tutorials

Follow the tutorial found on [Rails Tutorial](https://www.railstutorial.org/book/static_pages)

## Heroku

Guide to set up [Heroku](http://sourabhbajaj.com/mac-setup/Heroku/README.html)

## Chapter 3

- The rails script generates a new controller with rails generate controller ControllerName <optional action names>.

- New routes are defined in the file config/routes.rb.

- Rails views can contain static HTML or embedded Ruby (ERb).

- Automated testing allows us to write test suites that drive the development of new features, allow for confident refactoring, and catch regressions.

- Test-driven development uses a “Red, Green, Refactor” cycle.

- Rails layouts allow the use of a common template for pages in our application, thereby eliminating duplication.


## Chapter 4

- Ruby has a large number of methods for manipulating strings of characters.

- Everything in Ruby is an object.

- Ruby supports method definition via the def keyword.

- Ruby supports class definition via the class keyword.

- Rails views can contain static HTML or embedded Ruby (ERb).

- Built-in Ruby data structures include arrays, ranges, and hashes.

- Ruby blocks are a flexible construct that (among other things) allow natural iteration over enumerable data structures.

- Symbols are labels, like strings without any additional structure.

- Ruby supports object inheritance.

- It is possible to open up and modify built-in Ruby classes.


## Chapter 5

- Use HTML5 to define a site layout with logo, header, footer, and main body content.

- Rails partials are used to place markup in a separate file for convenience.

- CSS allows us to style the site layout based on CSS classes and ids.

- The Bootstrap framework makes it easy to make a nicely designed site quickly.

- Sass and the asset pipeline allow us to eliminate duplication in our CSS while packaging up the results efficiently for production.

- Rails allows us to define custom routing rules, thereby providing named routes.

- Integration tests effectively simulate a browser clicking from page to page.

## Chapter 6

- Migrations allow us to modify our application’s data model.

- Active Record comes with a large number of methods for creating and manipulating data models.

- Active Record validations allow us to place constraints on the
data in our models.

- Common validations include presence, length, and format.

- Regular expressions are cryptic but powerful.

- Defining a database index improves lookup efficiency while allowing enforcement of uniqueness at the database level.

- We can add a secure password to a model using the built-in has_secure_password method.

## License

All source code in the [Ruby on Rails Tutorial](http://railstutorial.org/)
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

For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).



# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
