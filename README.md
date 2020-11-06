# Heroku + Flask + Repl.it

Desplegaremos una aplicación web en Heroku utilizando Flask y Repl.it

## Comandos Usados

```bash
wget https://cli-assets.heroku.com/heroku-linux-x64.tar.gz

tar -zxf heroku-linux-x64.tar.gz

./heroku login

./../heroku/bin/heroku create SUDOMINIO  --buildpack heroku/python

./../heroku/bin/heroku login -i

./../heroku/bin/heroku git:remote -a SUDOMINIO

git remote add origin https://git.heroku.com/SUDOMINIO.git

git push --set-upstream origin master

```
