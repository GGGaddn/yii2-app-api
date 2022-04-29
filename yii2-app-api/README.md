# yii2-app-api


Having PHP and a database server installed on your machine, you can run the following commands:

    composer create-project cebe/yii2-app-api my-api
    cd my-api
    cp env.php.dist env.php
    cp config/components-ENV.local.php config/components-dev.local.php


> Note: If you don't have GNU make, you need to copy the configuration files as in the PHP directly section, then run:
> 
>     docker-compose up -d
>     docker-compose exec backend-php sh -c 'cd /app && composer install'


Then set up the database:

    ./yii migrate/up
    ./yii faker



    ./yii migrate/up
    ./yii faker

## Try it

    cd api
    make start


