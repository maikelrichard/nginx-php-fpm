## Shoutouts
Based on the nice repo from https://github.com/ngineered/nginx-php-fpm

## Building from source
To build from source you need to clone the git repo and run docker build:
```
git clone https://github.com/pasientskyhosting/nginx-php-fpm.git
cd nginx-php-fpm
git checkout <branch>
docker build -t pasientskyhosting/nginx-php-fpm:<tag> .
docker push pasientskyhosting/nginx-php-fpm:<tag>
```