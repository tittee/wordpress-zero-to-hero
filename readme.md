# Wordpress Underscores Theme + Docker

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Hi evevybody. 
I make WordPress for guideline your integrate it to you theme. so this project explain you use follow this.

  - Docker Compose
  - Docker Image (Nginx Wordpress MariaDB phpmyadmin)
  - Underscores.me
  - WordPress custom field

# First notes

  - Start docker-compose in you environment (please check port or changes port not effects in docker-compose.yaml)
  - else clone this project .it's easy way to learn.


### Tech

Dillinger uses a number of open source projects to work properly:

* [AngularJS] - HTML enhanced for web apps!
* [Ace Editor] - awesome web-based text editor
* [markdown-it] - Markdown parser done right. Fast and easy to extend.
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework [@tjholowaychuk]
* [Gulp] - the streaming build system
* [Breakdance](http://breakdance.io) - HTML to Markdown converter
* [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

### Installation

Dillinger requires [Node.js](https://nodejs.org/) v4+ to run.

After that docker start you might setting hosts for url localhost (mywordpress.test)

```sh
$ docker-compose up -d
$ sudo nano /etc/hosts
```
