# Working on meexle.com site:

The HUGO is used to generate static files for www.meexle.com site. 
To start working on the web site, make sure you have [HUGO](https://github.com/spf13/hugo/releases) installed and accessible from on your *PATH*

1. Checkout or fork [meexle-web](https://github.com/syemialy/meexle-web) repository
2. Create folder */themes/* within checked out project
3. Checkout [hugo-agency-theme](https://github.com/digitalcraftsman/hugo-agency-theme) into */themes/hugo-agency-theme/* 


_A tip on how to push to `gh-pages` branch_
```sh
git add public/ && git commit -m "initial public folder commit"
git subtree push --prefix public/ origin gh-pages
```
