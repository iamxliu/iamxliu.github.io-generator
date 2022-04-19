
# Hugo操作流程
```
1. brew install hugo
2. hugo version
3. hugo new site iamxliu.github.io-generator
4. cd iamxliu.github.io-generator
5. git init 
6. git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
7. echo theme = \"ananke\" >> config.toml
8. hugo new posts/my-first-post.md
```
* draft: false
```
9. hugo server -D

10. Open up config.toml in a text editor
```
* zh-Hans
* http://initialdynamics.xyz/
* https://iamxliu.github.io/
```
11. hugo -D

12. 新建.gitignore文件 加入/public/

13. cd public
14. git add .
15. git comimit -m 
16. git remote add origin git@github.com:iamxliu/iamxliu.github.io.git
17. git branch -M main
18. git push -u origin main

```