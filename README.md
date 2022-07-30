Para deploy no Heroku

Fazer login

## cria app
$heroku create <nome do app>
## cria banco
$heroku addons:create heroku-postgresql:hobby-dev --app <nome do app>
## ver config do app
$heroku config --app blog-python-ocean
## manda pro heroku
$git push heroku main

## para atualizar
$git push heroku main