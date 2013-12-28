rails-development-tips
======================


`git clone ...` — клонируем проект с гитхаба

`cd каталог` - переходим в каталог проекта

`bundle install` — устанавливаются rubygems

если нет bundler'а — ставим его `gem install bundler`

если нет нужной версии руби — ставим её:

`rbenv install 2.0.0p-247` — с нужной версией

`rbenv rehash`

`gem install bundler`

`bundle install` - устанавливаем пакеты для текущего каталога

`cp config/database.yml.example config/database.yml` - комируем настройки базы из файла пирмера

`vim config/database.yml` - редактируем настройки базы (обычно user и password достаточно)

`bundle exec rake db:create` - создается база их схемы 

`bundle exec rake db:migrate` - в базу вносятся миграция (изменяется схема базы)

`bundle exec rails s` - запускаем веб-сервер на 3000-м порту


Дальше в браузере открываем `http://localhost:3000`
