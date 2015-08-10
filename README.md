# Website - Working

## Instalation (do only once)

```
$ sudo apt-get install python-pip python-virtualenv virtualenvwrapper
$ sudo apt-get install python-dev
```
```
$ sudo pip install pelican markdown ghp-import
```

### Github configuration

```
$ git clone https://github.com/Medivisu/Website.git
```

### Pelican configuration
Download the nest theme at <https://github.com/molivier/nest>, unzip it, rename to *nest* and put it in 
```
/usr/local/lib/python2.7/dist-packages/pelican/themes/
```

## Create an article

Writing an article in markdown (my-title.md) and put it in *~/Website/content/*

```
Title: My title
Date: 2015-08-10
Category: Category
Tags: tag1, tag2

Hello World !!!
```

### Generate your site

```
$ cd ~/Website
$ pelican content/
```
### Publish

```
$ cd ~/Website
$ git commit -m -a 'add article'
$ git push origin master
$ make github
```
