# War and Piece

War & Piece is a Ruby Rails chess application developed as part of The Firehose Project software engineering program.

During the project, <a href="https://github.com/cldambrosio">cldambrosio</a>, <a href="https://github.com/garyravago">garyravago</a>, <a href="https://github.com/RajSannidhi">RajSannidhi</a>, <a href="https://github.com/reneesandefur">reneesandefur</a> and <a href="https://github.com/hereismyusername">hereismyusername</a> worked as a remote Agile web development team under the guidance of an experienced software engineer <a href="https://github.com/rosalinekarr">rosalinekarr</a>.

Programming langauges and tools utilized include:

- Ruby on Rails
- JavaScript
- jQuery
- Ajax
- HTML
- CSS
- Bootstrap
- PostgreSQL
- RSpec
- Heroku
- Trello

The live application is viewable [here](https://war-and-piece.herokuapp.com)

## Getting Started

## Software requirements

- Rails 5.0.0 or higher

- Ruby 2.3.1 or higher

- PostgreSQL 9.6.8 or higher

## Navigate to the Rails application

```
$ cd /WarAndPiece
```

## Set configuration files

```
$ cp config/database.yml.template config/database.yml
```


## Create the database

 ```
 $ pgstart
 $ rake db:create
 ```

## Migrating and seeding the database

```
$ rake db:migrate
$ rake db:seed
```

## Starting the local server

```
$ rails server

   or

$ rails s
```

## Production Deployment

  ```
  $ git push heroku master
  $ heroku run rake db:migrate
  ```

## Performing Unit Testing

```
  $ bundle exec rspec
```

## Support

Bug reports and feature requests can be filed with the rest for the Ruby on Rails project here:

* [File Bug Reports and Features](https://github.com/garyravago/WarAndPiece/issues)

## License

WarAndPiece is released under the [MIT license](https://mit-license.org).

## Copyright

copyright:: (c) Copyright 2017. All Rights Reserved.
