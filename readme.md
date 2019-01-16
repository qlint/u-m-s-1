U-M-S
==========================================

# Description
  U-M-S web application. Plug and Play

# Installation and use
### U-M-S is built using Laravel 5.2
```
$ git clone https://github.com/qlint/u-m-s-1.git
```
```
$ cd u-m-s-1
```
```
$ mv .env.example .env
```
**Change configuration in .env according your need and create Database**
```
$ composer install
```
```
$ php artisan migrate
```
```
$ php artisan db:seed
```

**Give write permission to storage and bootstrap/cache directory**

```
$ php artisan serve
```
**  http://localhost:8000 **
USER: admin
PASS: demo123


# Screenshot
<img src="screenshots/1.png">
<img src="screenshots/2.png">
<img src="screenshots/3.png">
<img src="screenshots/4.png">
<img src="screenshots/6.png">
<img src="screenshots/7.png">
<img src="screenshots/8.png">
<img src="screenshots/9.png">
<img src="screenshots/10.png">
<img src="screenshots/11.png">
<img src="screenshots/12.png">
<img src="screenshots/13.png">
<img src="screenshots/14.png">
<img src="screenshots/15.png">
<img src="screenshots/16.png">



# License
U-M-S is open-sourced software licensed under the AGPL-3.0 license. Frameworks and libraries has it own licensed
