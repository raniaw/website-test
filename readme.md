... 
sh
1. npm init -y
... 
... 
sh
2. npm install --save-dev gh-pages
or 
...
sh
   npm i gh-pages 
...
... 
sh
3. in package.json 
"homepage":"https://user.github.io/website-test.git",
in 
"script" : {
    ...
    "deploy":"gh-pages -d dist"
} 
...
... 
sh
4. erstellen
...
sh
.gitgnore
da einfügen 
... 
sh
node_modules
...
... 
sh
5. git init 
...
... 
sh
6. git add .
...
... 
sh
7. git commit -a
...
... 
sh
8. git remote add origin git@github.com:user/website-test.git
...
... 
sh
9. git push -u origin master
...
... 
sh
10. npm run deploy