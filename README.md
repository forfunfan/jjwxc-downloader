# jjwxc downloader powered by PHP
![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg) [![Build Status](https://travis-ci.com/TsundokuApp/Tsundoku.svg?branch=develop)](https://travis-ci.com/TsundokuApp/Tsundoku) [![Maintainability](https://api.codeclimate.com/v1/badges/24df2547bd334d08558a/maintainability)](https://codeclimate.com/github/TsundokuApp/Tsundoku/maintainability)
## Usage

```
php downloader.php [url]||[id]

```

**Example**: download by book id

```
php downloader.php 3164148
```

**Example**: download by url

```
php downloader.php http://www.jjwxc.net/onebook.php?novelid=3164148
```

### TODO

- [ ] Get the book metadata including author name,book_id, number of chapters and introduction.
- [ ] Parsing book's cover url
- [ ] Download cover image as a separate file for each book
- [ ] Check whether or not the given login credential is valid 
- [ ] Access chapter content from beginning to ending
- [ ] Save all parsed content into a single txt file

### Authors

Wing kwan Li

### Licence

This project is licenced under the MIT licence.
