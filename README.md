# nuxt_django_start
this is nuxtjs Django quick migration commands.

I dont use nuxtjs nor django anymore because they are slow. I use sveltejs and golang. But these commands may help you.

cd /usr/local/lsws/server


INSTALL PYTHON_MYSQL UBUNTU
sudo apt-get install libmysqlclient-dev python-dev mysqlclient
pip install django-mysql
sudo apt-get install default-libmysqlclient-dev

ADD PACKAGES PYTHON
python3 -m pip install django django-cors-headers djangorestframework drfpasswordless

PIP
pip install django-filter dj-rest-auth django-allauth django-rest-auth[with_social]
pip install python-gettext
pip install djangorestframework-simplejwt whitenoise django-mysql jsonfield
pip install psycopg2-binary mysqlclient
pip uninstall django-filter
y
apt-get update
sudo apt-get install libpq-dev python3-dev
pip install psycopg2



PIP LINUX or WIN
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py
py get-pip.py
pip install --upgrade pip utils

PIP
sudo apt install python3-pip
sudo pip3 install --upgrade pip
pip install django
pip install djangorestframework
pip install djongo
python3 manage.py runserver
cd /usr/local/lsws/server
python3 manage.py runserver

DJONGO
pip install --upgrade djongo
DJONGO NEEDS sqlparse==0.2.4



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












DISABLE ROOT
ADD NEWUSER BEFORE ROOT
adduser bitdom8here
echo 'bitdom8here ALL=(ALL) ALL' >> /etc/sudoers
ssh bitdom8here@91.226.221.182 -p 22

running scripts is disabled
Set-ExecutionPolicy RemoteSigned

OLS
bitdom8
KOKbok22-* * 3 + 99

YARN INSTALL WIN
npm install --global yarn
yarn --version

npm install --global pnpm

NODEJS
pnpm add -g pnpm

pnpm run generate:manifest
pnpm add sharp

npm init svelte@next client
cd client
npm install
npm run dev

NEW YARN
npm init svelte@next client
cd client
pnpm install
pnpm build
pnpm preview

"preview": "svelte-kit preview --host=91.226.221.182 --port=3000",

cd /usr/local/lsws/Example/server/
cd /usr/local/lsws/Example/client/
cd /usr/local/lsws/Example/
rm -rf client
trash-empty


# ssh root@91.226.221.182 -p 22
sudo ufw allow 2234/tcp
ssh root@91.226.221.182 -p 2234

/usr/local/lsws/bin/lswsctrl stop

cd /usr/local/lsws/Example/client
kill -9 $(pgrep -f 'lsnode')
killall node
pm2 kill
pm2 save

/usr/local/lsws/bin/lswsctrl start
cd /usr/local/lsws/Example/client



cd /usr/local/lsws/Example2/client
/usr/local/lsws/bin/lswsctrl start
pm2 start
a

pm2 ls


THEN OPEN su root
su -

Change SSH Port (22 becomes 9876)
su -
vi /etc/ssh/sshd_config

Add ssh key (RUN on WINDOWS)
ssh-keygen -t ed25519 -C "xxxx"

xxx means your password

Server Instance:7080  8088
ssh root@91.226.221.182

ssh-keygen -R 192.168.1.102
ssh sk@91.226.221.182

CHANGE VPS PASSWORD:
passwd

PERMISSION
sudo su

LINUX NODEJS INSTALL
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs

apt update

SSL  http to https 
sudo apt install ufw
sudo ufw allow 3306

sudo reboot

sudo ufw allow 22,53,80,
sudo ufw allow 443,7080,8088/tcp
sudo ufw default reject
sudo ufw enable




PYTHON UPGRADE
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
(then enter)
sudo apt update
sudo apt install python3.9
sudo apt install python-is-python3
sudo apt install python-dev-is-python3
sudo apt-get install openlitespeed
