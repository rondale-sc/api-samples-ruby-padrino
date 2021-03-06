# ESPN API Sample (Ruby/Padrino)

## Running on Heroku

Assumes your local environment is already [setup to deploy to Heroku](http://devcenter.heroku.com/articles/quickstart).

    $ git clone http://github.com/jaxzin/api-samples-ruby-padrino.git
    $ cd api-samples-ruby-padrino
    $ heroku create --stack bamboo-mri-1.9.2
    $ git push heroku master
    ... wait for it to push and launch ...
    $ heroku config:add espn_api_key=[your apikey from http://developer.espn.com]
    ... wait for it to add the config vars and restart ...
    $ heroku open

## Light Reading

* [The ESPN Developer Center](http://developer.espn.com)
* [Ruby](http://ruby-lang.org)
* [Padrino](http://padrinorb.com)