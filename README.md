# proscene-javadocs

After *proscene* api is compiled run:

```sh
#n below is the prescene release
$ cd proscene/distribution/proscene-n/reference
$ git init
$ git remote add origin https://github.com/remixlab/proscene-javadocs.git
$ git pull origin gh-pages -Xours
$ git add *
$ git commit -am'docs updated'
$ git push origin master:gh-pages
```