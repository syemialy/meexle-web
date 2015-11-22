# Working on meexle.com site:

The HUGO is used to generate static files for www.meexle.com site. 
To start working on the web site, make sure you have [HUGO](https://github.com/spf13/hugo/releases) installed and accessible from on your *PATH*

1. checkout or fork [meexle-web](https://github.com/syemialy/meexle-web) repository
2. create folder /themes/ within newly checked out repo.
3. inside themes/ folder checkout [hugo-agency-theme](https://github.com/digitalcraftsman/hugo-agency-theme) project

A tip on how to push to `gh-pages` branch
```sh
git add public/ && git commit -m "initial public folder commit"
git subtree push --prefix public/ origin gh-pages
```

That is it
