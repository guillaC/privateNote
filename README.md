# privateNote
Simple, clean self destructing note site!

# Screenshots
![image](https://github.com/guillaC/privateNote/assets/6315083/c91cd7aa-3954-4e82-a875-983fd553f379)

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

# Demo
This version is not hosted and translated by myself, and I don't know the author : https://blog.qcmoe.com/note/
