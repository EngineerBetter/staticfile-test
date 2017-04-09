# Demo of Staticfile Buildpack Auth Not Working?

Steps:

```
$ cd staticfile-test
$ cf push
```

Expected:

* visit reported URL
* expect HTTP basic auth

Actual:

* visit reported URL
* observe "you can see me"