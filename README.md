# Blog

A blog application built using ruby on rails 6

### Instructions

----

* clone this repo
* and `cd` into it

```$ cd social_media```
* install ruby version manager (rvm)
* install postgresql database (version 12 or above)
* run postgresql
* install node.js (version 12 and above)
* install yarn package manager

* run the following commands

```
$ rvm use 2.7.1 --install
$ gem install bundler
$ bin/bundle install
$ yarn install --check-files
$ bin/bundle exec rails db:create db:migrate
```


* run the tests
```
$ bin/bundle exec rspec
```

* run development server
```
$ bin/rails server
```

-- enjoy the demo :)