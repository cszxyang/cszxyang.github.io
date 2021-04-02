## Introduction

Personal blog built with `hugo`, decorated with `hugo-theme-casper`, reconstruct some htmls, import `highlight.js `and some css files. It is such an enjoyable thing to run test cases locally and deploy pages to github server as hugo which created by `GO` has the ability of running in a fascinating and remarkable speed, which makes me abandon `hexo` and get to know `hugo` without hesitation.

## Deploy

use following cmd to generate `public` folder

```
hugo --theme=hugo-theme-casper --baseUrl="http://golb.cc/" 
```

use following cmds for first commit

```
cd public
git init
git add -A
git commit -m "first commit"
git remote add origin https://github.com/cszxyang/cszxyang.github.io.git
git push -u origin master
```