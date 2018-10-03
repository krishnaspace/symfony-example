**Setup parameters.yml**

First, make sure you have an `app/config/parameters.yml`
file (you should). If you don't, copy `app/config/parameters.yml.dist`
to get it.

Next, look at the configuration and make any adjustments you
need (like `database_password`).

**Download Composer dependencies**

Make sure you have [Composer installed](https://getcomposer.org/download/)
and then run:

```
composer install
```

You may alternatively need to run `php composer.phar install`, depending
on how you installed Composer.

