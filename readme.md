1. 
npm init -y
2. 
npm install --save-dev gh-pages
or 
   npm i gh-pages 
3. 
in package.json 
"homepage":"https://user.github.io/website-test.git",
in 
"script" : {
    ...
    "deploy":"gh-pages -d dist"
} 
4. erstellen
.gitgnore
da einfügen 
node_modules

5. 
git init 
6. 
git add .
7. 
git commit -a
8. 
git remote add origin git@github.com:user/website-test.git
9. 
git push -u origin master
10. 
npm run deploy