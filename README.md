# Landing

## Перед стартом пакета необходимо:

>node -v

если вы видите версию, тогда все ок,
иначе идем на сайт node и скачиваем и устанавливаем Node LTS

## для Linux:

>curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
>sudo apt-get install -y nodejs

>node -v

> v8.9.0

> npm -v

> 5.5.1

* Убедиться,что установлен Gulp 4 версии,так как, если меньше -
работать не будет

> gulp -v

> npm install gulpjs/gulp-cli#4.0 -g

# Uninstall previous Gulp installation and related packages, if any
> $ npm rm gulp -g

> $ npm rm gulp-cli -g

> $ npm rm gulp --save-dev

> $ npm rm gulp --save

> $ npm rm gulp --save-optional

> $ npm cache clean

# Install the latest Gulp CLI tools globally

> $ npm install gulpjs/gulp-cli -g

# Install Gulp 4 into your project from 4.0 GitHub branch as dev dependency

> $ npm install gulpjs/gulp#4.0 --save-dev

# Check the versions installed. Make sure your versions are not lower than shown.

> $ gulp -v


## Инструкция для старта проекта

* Склоноировать данный репозиторий:

> git clone https://github.com/lassarb/landing.git

* Запусить комманду:

> npm install

# Дополнительно
 
* для создания файла package.json: 

 > npm init


 > npm install -g browser-sync

 > npm install browser-sync --save-dev

 > npm install gulp-pug gulp-sass --save-dev

 > npm i gulp.spritesmith --save-dev

 > npm install rimraf --save-dev (для очистки)

 > npm install gulp-rename

