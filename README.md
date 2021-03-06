# FFXIVBOT
[![Build Status](https://travis-ci.org/Bluefissure/FFXIVBOT.svg?branch=master)](https://travis-ci.org/Bluefissure/FFXIVBOT)
[![license](https://img.shields.io/badge/license-GPL-blue.svg)](https://github.com/Bluefissure/FFXIVBOT/blob/master/LICENSE)

A QQ bot of FFXIV

## Install
- python 3.5.3+
- redis-server 4.0+
- django, channels and so on (see [requeirements.txt](https://github.com/Bluefissure/FFXIVBOT/blob/master/requirements.txt) for details)
- [coolq-wine(docker)](https://hub.docker.com/r/coolq/wine-coolq/)
- [coolq-http-api](https://github.com/richardchien/coolq-http-api)

## Use
- /cat : require an image of cat (crawled from [pexels](https://www.pexels.com/search/cat))
- /search $item : search $item in [FFXIVWIKI](https://ff14.huijiwiki.com/)
- /anime $image : search the animation of $image ([whatanime](https://whatanime.ga/) API token required)
- /random $num : require $num true random numbers  ([random.org](https://www.random.org/) API token required)
- /gif : generate an shadiao gif via [sorry.xuty.tk](https://sorry.xuty.tk/) (/gif help : get help)
- /dps : get the dps rank from fflogs

## Examples
![/cat](https://i.loli.net/2018/04/11/5acd9cd833831.png)
![/search](https://i.loli.net/2018/04/11/5acd9c2eef267.png)
![/anime](https://i.loli.net/2018/04/11/5acd9c2f2ceea.png)
![/random](https://i.loli.net/2018/04/11/5acd9c2f0da51.png)

## Demo
Add the demo bot above with keyword "FFXIV" 

