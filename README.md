# nuxt_django_start
this is nuxtjs Django quick migration commands.

I dont use nuxtjs nor django anymore because they are slow. I use sveltejs and golang. But these commands may help you.

cd /usr/local/lsws/server


RESTART PYTHON
killall lswsgi

NODEJS INSTALL FOR WIN and TEST VERSION
node -v



YARN VERSION NOT SHOWN: GO TO POWERSHEEL
Get-ExecutionPolicy -List
Set-ExecutionPolicy Unrestricted
Set-ExecutionPolicy Unrestricted -Force

ADD YARN LINUX
curl -o- -L https://yarnpkg.com/install.sh | bash
curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update && sudo apt install yarn

ADD PYTHON FOR WIN
https://www.python.org/downloads/windows/

SSL
sudo apt-get install snapd

DEPENDENCIES
pip list --outdated
pip freeze



UPTODATE ALL FOR WIN & LINUX
pip freeze | %{$_.split('==')[0]} | %{pip install --upgrade $_}
pip3 list --outdated --format=freeze | grep -v '^\-e' | cut -d = -f 1 | xargs -n1 pip3 install -U
pip install -U -r requirements.txt

psycopg2 psycopg2-binary psycopg2-pool allauth

pip setuptools wheel

UNINSTALL
pip uninstall mysql-connector-python

CLIENT
git config --global user.email "bitdom8@gmail.com"

Remove-Item ".git" -Recurse -Force
git init
git add .
git commit -m “Test132”
git remote add github https://github.com/bitdom8/nuxtjs_typescript.git
git remote -v
git push -f github master
Remove-Item ".git" -Recurse -Force

SERVER (Delete previous .git file also)
Remove-Item ".git" -Recurse -Force
git init
git add .
git commit -m “Testik”
git remote add github https://github.com/bitdom8/restdj.git
git remote -v
git push -f github master
Remove-Item ".git" -Recurse -Force

PROJECT (MAIN Project)
django-admin startproject server

CREATING WEB APP (PROJECT'S MODULE)
python manage.py startapp youtubeapi

python manage.py createsuperuser --email bitdom8@gmail.com --username bitdom8


ENV.
deactivate

python manage.py createsuperuser --email bitdom8@gmail.com --username bitdom8

cd /usr/local/lsws/Example/server
cd server
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
a
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
a

i18n language
python manage.py makemessages --all
python manage.py compilemessages

MIGRATIONS
python3 manage.py migrate --fake youtubeapi
python manage.py migrate --run-syncdb

python manage.py makemigrations youtubeapi
python manage.py makemigrations youtubeapi --empty
python manage.py migrate youtubeapi zero
python manage.py makemigrations youtubeapi
python manage.py squashmigrations youtubeapi 0001_initial
python manage.py squashmigrations youtubeapi 0001
python manage.py squashmigrations youtubeapi 0001_squashed_0001_initial

DELETE ALL MIGRATİON  AND RECR ALL MIGRATİON
python -m manage makemigrations
python -m manage migrate

NUXT
yarn upgrade
yarn add nuxt@2.15.2
yarn add nuxt-i18n
yarn add --dev @nuxt/image
yarn add -D pug pug-plain-loader
yarn add -D sass sass-loader@10 fibers
yarn add --dev @nuxtjs/moment
yarn add @babel/preset-env --dev
yarn add nuxt-precompress
yarn add @nuxtjs/sitemap
yarn add -D nuxt-compress
yarn add -D sass-loader node-sass
yarn add sass-loader sass
yarn add -D @nuxtjs/style-resources
yarn add -D @nuxtjs/color-mode
yarn add --dev @nuxtjs/svg
yarn add vue-infinite-loading
yarn add compress.js
yarn add @nuxtjs/auth
yarn add @nuxtjs/axios
yarn add core-js
sudo yarn global add pm2 --prefix /usr/local
yarn add @dansmaculotte/nuxt-security
yarn add feature-policy helmet helmet-csp referrer-policy hsts
yarn add vue-lazy-hydration
yarn add materialize-css

TWA ADD
yarn add nuxt-twa-module --save-dev

REMOVE
yarn remove @dansmaculotte/nuxt-security

Dev Dependencies:
yarn add --dev "@nuxt/types" 
yarn add --dev "nodemon"
pnpm add -D nodemon
