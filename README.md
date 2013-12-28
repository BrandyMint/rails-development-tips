rails-development-tips
======================


`git clone ...` — клонируем проект с гитхаба

`bundle install` — устанавливаются rubygems

если нет bundler'а — ставим его `gem install bundler`

если нет нужной версии руби — ставим её:
`rbenv install 2.0.0p-247` — с нужной версией
`rbenv rehash`
`gem install bundler`
`bundle install`


`cp config/database.yml.example config/database.yml`
`vim config/database.yml`

`bundle exec rake db:create`

`bundle exec rake db:migrate`

`bundle exec rails s`
