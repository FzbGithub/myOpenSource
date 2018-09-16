# 操作指令记录

对本项目所涉及到的操作指令记录

## 进入当前项目

``` git config user.name 'FzbGithub' ```
``` git config user.email '124100254@qq.com' ```
## 提交指令

``` git status git diff git add . git commit -m '第一次提交' git push origin master ```
``` npm -v  node -v npm init ```

## 开发环境指令

``` npm install webpack-cli --save-dev ```
``` npm install webpack --save-dev ```
``` npm install babel-core --save-dev ```
``` npm install babel-loader --save-dev ```
``` npm install babel-polyfill --save-dev ```
``` npm install babel-preset-es2015 --save-dev ```
``` npm install bebel-preset-latest --save-dev ```
##　package.json 生成npm run 指令

``` npm run release ```

## 初始化gitbook,然后创建SUMMARY.md
``` npm install gitbook-cli -g ```

## SUMMARY.md内容

``` # Summary ```
``` * [项目介绍](README.md) ```
``` * [使用文档](doc/use/README.md) ```
```    * [使用1](doc/use/use1.md) ```
```    * [使用文档](doc/use/use2.md) ```
``` * [二次开发](doc/dev/README.md) ```
```    * [开发1](doc/dev/dev1.md) ```
```    * [开发2](doc/dev/dev2.md) ```

## gitbook 指令

``` gitbook init ```
``` gitbook build ```

## 先在.gitignore文件上加上 _book

- git不用提交_book文件夹及其子文件的内容到github仓库

## 提交第一版版本，创建tag

``` git tag -a 'v0.0.1' -m 'first version' ```
``` git push origin v0.0.1 (需要用这个才行git push --tags)``` 

## 将代码提交的npm 

``` npm add user ```
``` npm add login ```
``` npm publish ```

## 发布代码到npm 问题记录

- 403 没权限，项目名称已经在npm存在，可在package.json修改name字段名字
- 版本问题 在npm已经发布过版本，不能发相同的版本，npm 上托管的代码不允许改版本，可在package.json修改version版本




