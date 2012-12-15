# atmosphere-compat #

## Build & run ##

```sh
$ cd atmosphere-compat
$ ./sbt
> container:start
> browse
```

If `browse` doesn't launch your browser, manually open [http://localhost:8080/](http://localhost:8080/) in your browser.

## Deploy to Jelastic ##

```sh
$ cd atmosphere-compat
$ ./sbt
> compile
> deploy
```
