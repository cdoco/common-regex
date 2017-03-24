# Common Regular Expression

![Regex](images/regex.png)

## Table of Contents

- [Email](#email)
- [Phone](#phone)
- [Domain-name](#domain-name)

## Email

`gaozihang-001@gmail.com`

```regex
^[a-zA-Z0-9_-]+@[a-zA-Z0-9_-]+(\.[a-zA-Z0-9_-]+)+$
```

![email](images/email.png)

## Phone

`13012345678`

```regex
^1(3|4|5|7|8)\d{9}$
```

![email](images/phone.png)

## Domain-name

`https://google.com`

```regex
/(?:https?:\/\/)?(?:item|detail)\.(?:taobao|tmall)\.com\/item.html?\?(?:[\&=\w\.-]*&)?id=(\d+)(?:$|&|#|,)/gim
```
![domain-name](images/domain-name.png)
