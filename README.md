# devotionals


An advent devotional by [Jeff Beard](http://www.jeffbeardbooks.com/) for [Muddy Creek Baptist Church](https://www.muddycreekbaptist.org/) of Powhatan, VA.


## Tasks

### build

```sh
pandoc src/easter.md --toc --toc-depth 1 --template src/template.html -o docs/he-is-risen.html

pandoc src/index.md --template src/no-toc-template.html -o docs/index.html
```

### push
```sh
git add --all
git commit -m "$@"
git push
```

