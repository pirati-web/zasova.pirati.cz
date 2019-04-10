# example.pirati.cz

[![Build Status](https://api.travis-ci.org/pirati-web/praha.pirati.cz.svg?branch=gh-pages)](https://travis-ci.org/pirati-web/praha.pirati.cz)

[Návod](https://github.com/pirati-web/jekyll-theme-pirati/blob/master/USAGE.md) na nastavení a používaní jednoduchého webu nad `jekyll-theme-pirati`

Úpravy pro Zlínský kraj oproti originálu:
``` 
    Zrušení top menu
    přidán _layouts/default.html 
    v něm odebrán {% include header.html %}
```
```
   Pro vlastní css úpravy
   přidán _includes/head-custom.html <link rel="stylesheet" href="{% asset 'custom.css' @path !type %}">
   přidán assets/css/custom.scss - zde jsou vlastní css úpravy
```    
