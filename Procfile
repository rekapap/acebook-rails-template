build:
  languages:
    - ruby
run:
  rake: bundle exec rake
  rake: db:migrate
  web: bundle exec puma config.ru -p $PORT
