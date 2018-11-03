# jjwxc downloader powered by PHP

## Usage

```
php downloader.php [url]||[id]

```

##Example one: download by book id

```
php downloader.php 3164148
```

##Example two: download by url

```
php downloader.php http://www.jjwxc.net/onebook.php?novelid=3164148
```

### TODO

- [ ] Get the book metadata including author name,book_id, number of chapters and introduction
- [ ] Check whether or not the given login credential is valid 
- [ ] Access chapter content from beginning to ending
- [ ] Save all parsed content into a single txt file

