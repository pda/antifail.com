antifail.com
============

[antifail](http://antifail.com/) powered by http://gohugo.io/

```sh
# run local server, watching for changes.
hugo server --watch

# ... including draft posts
hugo server --watch --buildDrafts=true

# build site
rm -rf public
hugo

# upload site
./upload
```

Useful things:

* `brew install hugo`
* `brew install awscli`
* https://github.com/pda/aws-keychain
