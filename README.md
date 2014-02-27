This README would normally document whatever steps are necessary to get the
application up and running.

Summary
-------
TODO

Installation
------------

0.1. Install ruby
```shell
$ curl -sSL https://get.rvm.io | bash -s stable --ruby=2.0
```

0.2. bis. Install bundler
```shell
$ gem install bundler
```

1. Clone repo
```shell
$ git clone https://github.com/dbsima/resume2.0.git
$ cd resume2.0
```

2. Install gem dependencies	
```shell
$ bundle install
```
3. Migrate db
```shell
$ bundle exec rake db:migrate RAILS_ENV=development
```
4. Start server
```shell
$ bundle exec rails s
```

Usage
-----

In the browser go to http://localhost:3000

Testing
-------
TODO
