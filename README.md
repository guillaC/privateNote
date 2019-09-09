# privateNote

Simple, clean self destructing note site!

# Screenshots

![screenshot](https://image.noelshack.com/fichiers/2019/37/1/1568046466-privatenote.png)

# Demo

http://guillaume.xyz/privateNote/

# Features

- [x] Self destructing notes
- [x] AES256 encryption

# Credits

- [HackCSS](https://hackcss.egoist.moe)

# Usage

Create database

```SQL
CREATE DATABASE privatenote
```
Create table
```SQL
CREATE TABLE IF NOT EXISTS `note` (
  `id` text NOT NULL,
  `message` text NOT NULL
) 
```

edit 'sql.php'
