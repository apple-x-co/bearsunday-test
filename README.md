# bearsunday-test

## Create Project

```bash
composer create-project -n bear/skeleton MyVendor.MyProject
```

## Create Controller

`MyVendor.MyProject/src/Resource/Page/Hello.php`

ref:`MyVendor.MyProject/src/Resource/Page/Index.php`

## Run

```bash
php MyVendor.MyProject/bootstrap/web.php get /hello
php MyVendor.MyProject/bootstrap/web.php get '/hello?name=World'
```

OR

```bash
php -S 127.0.0.1:8080 -t MyVendor.MyProject/var/www
```