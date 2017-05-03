**OneExchange**
===================

![ruby](https://img.shields.io/badge/Ruby-2.4.1-red.svg)
![rails](https://img.shields.io/badge/Rails-5.1.0-red.svg)
![rails](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg)

## Sobre o projeto

Sistema incrivelmente simples para conversão de moedas.

## [Clique e veja online](http://onebitcode-cambio.herokuapp.com/)

![One Exchange](https://rawgit.com/engjoao/onebitcode_exchange/master/public/background-img.jpg)

# Stack
```
  * Application
```

# Dependencies
```
  * Fixer.io to consult currency rates
```

# Getting Started
```
  * docker-compose build
  * docker-compose run --rm website rake db:create db:migrate
  * docker-compose up
```

# Test
```
  * docker-compose run --rm website rspec
```
