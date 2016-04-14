# PHP-FPM Docker image

This is an PHP-FPM docker base image using [Alpine](http://alpinelinux.org/) Linux and based on the [docker-library/php](https://github.com/docker-library/php) docker image with just few modifications to make smaller and to have `pgsql` support out-of-the-box.

## Getting Started

This image have been build for being used as a base image and extend it, so you'll need to extending the base image like:

```
FROM zot24/php-fpm
...
```

## Resources

Some util resources about docker + images + alpine + being smart :)

* [Tips & Tricks with Alpine + Docker](http://blog.zot24.com/tips-tricks-with-alpine-docker/)
* [Tips & Tricks with Docker & Docker compose](http://blog.zot24.com/tips-tricks-docker/)

## Authors

* **Israel Sotomayor** - *Initial work* - [zot24](https://github.com/zot24)

See also the list of [contributors](https://github.com/zot24/docker-php-fpm/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/zot24/docker-php-fpm/blob/master/LICENSE) file for details
