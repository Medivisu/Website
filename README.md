# Website

## Instalation

```
$ sudo apt-get install python-pip python-virtualenv virtualenvwrapper
$ sudo apt-get install python-dev
```
```
$ pip install pelican markdown
```
## Github configuration

```
$ git clone https://github.com/Medivisu/Website.git
```

## Create an article

Writing an article in markdown (my-title.md).

```
Title: My title
Date: 2015-08-10
Category: Category
Tags: tag1, tag2

Hello World !!!
```

## Generate your site

```
$ pelican content/
```
## Publish

```
$ make github
```
