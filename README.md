# Common Regular Expression

![Regex](http://cdoco.com/images/regex.png)

## Table of Contents

- [Email](#email)
- [Phone](#phone)

## Email

example: gaozihang-001@gmail.com

```regex
^[a-zA-Z0-9_-]+@[a-zA-Z0-9_-]+(\.[a-zA-Z0-9_-]+)+$
```

## Phone

example: 13012345678

```regex
^(13[0-9]|14[5|7]|15[0|1|2|3|5|6|7|8|9]|18[0|1|2|3|5|6|7|8|9])\d{8}$
```