# www
www.golangbelgrade.org
=============


Initial setup
-----------
```git
git subtree add --prefix=public https://github.com/GolangBelgrade/www.git gh-pages --squash
git subtree pull --prefix=public https://github.com/GolangBelgrade/www.git gh-pages
hugo
git add -A
git commit -m "Updating site"
git push origin master
git subtree push --prefix=public https://github.com/GolangBelgrade/www.git gh-pages
```

Add post
-----------
```git
hugo
git commit -am "Addd new post"
git push origin master
git subtree push --prefix=public https://github.com/GolangBelgrade/www.git gh-pages
```

Add new theme
-----------
```git
cd themes
git clone <url_of_theme> ( git clone https://github.com/dim0627/hugo_theme_beg beg )
```
