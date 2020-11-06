# Heroku + Flask + Repl.it
Desplegaremos una aplicación web en Heroku utilizando Flask y Replit

## Recursos
- [Repl.it](https://repl.it) y [Heroku](https://heroku.com)
- Tutorial Youtube: https://youtu.be/im9A_Q5qOJg
- Demo aplicación desplegada: https://tutorial-heroku-flask.herokuapp.com/

## Comandos Usados

```bash
wget https://cli-assets.heroku.com/heroku-linux-x64.tar.gz

tar -zxf heroku-linux-x64.tar.gz

./../heroku/bin/heroku create NOMBREAPP  --buildpack heroku/python

./../heroku/bin/heroku login -i

./../heroku/bin/heroku git:remote -a NOMBREAPP

git remote add origin https://git.heroku.com/NOMBREAPP.git

git push --set-upstream origin master

```
