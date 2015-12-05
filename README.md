# www
www.golangbelgrade.org website
=============


Adding post
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
