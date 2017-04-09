# Demo of Staticfile Buildpack Auth Not Working?

Steps:

```
$ cd staticfile-test
$ cf push
```

Expected:

* visit reported URL
* observe HTTP basic auth prompt
* enter `user` and `pass`
* observe "you can see me"


Actual:

* visit reported URL
* observe "you can see me"