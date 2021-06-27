`docker-compose run --rm composer composer create-project laravel/laravel .`

`docker-compose run --rm composer composer require laravel/ui`

`docker-compose run --rm artisan ui vue --auth`

`docker-compose run --rm npm /bin/bash`

`docker-compose run --rm npm npm install`

### In the container

`npm install vue-loader@^15.9.5 --save-dev --legacy-peer-deps`

`exit`

### On host

`docker-compose run --rm npm npm run dev`