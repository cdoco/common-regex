# Common Regular Expression

![Regex](images/regex.png)

## Table of Contents

- [Email](#email)
- [Phone](#phone)

## Email

`gaozihang-001@gmail.com`

```regex
^[a-zA-Z0-9_-]+@[a-zA-Z0-9_-]+(\.[a-zA-Z0-9_-]+)+$
```

![email](images/email-regex.svg)

## Phone

`13012345678`

```regex
^(13[0-9]|14[5|7]|15[0|1|2|3|5|6|7|8|9]|18[0|1|2|3|5|6|7|8|9])\d{8}$
```

![email](images/phone-regex.svg)