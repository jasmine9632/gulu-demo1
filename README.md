## gulu-demo1

## Vue UI 组件库

## by Jasmine



mkdir gulu-demo1


cd gulu-demo1

touch README.md

git init

git add .

git commit -m "init"

git remote add origin git@github.com:jasmine9632/gulu-demo1.git

git push -u origin master




creating a package.json file

npm init

package name: (gulu-demo1) gulu
version: (1.0.0) 0.0.1
description: 这是一个Vue UI组件库
entry point: (index.js)
test command:
git repository: (https://github.com/jasmine9632/gulu-demo1.git)
keywords: Vue, UI
author: Jasmine
license: (ISC) MIT

git add .

git commit -m "npm init"

git pull

git push




inatall Vue

npm install vue

touch .gitignore   

node_modules/


git status -sb

git add .

git commit -m "add .gitignore"

git pull

git push



git commit -m "完成按钮基本样式"




install parcel


npm i -D parcel-bundler

git add .

git commit -m "安装parcel"

git pull

git push

 打开vsCode终端，本地安装并启动测试服务器，自动检测sass并安装
 
 npx parcel index.html 或者
 
 npx parcel --no-cache
 
 
 又或者
 
 rm -rf .cache
 
 npx parcel index.html
 
 打包之前
 
 .gitignore 添加  .cache/    dist/    node_modules/
 
 git add .
 
 git commit -m ".gitignore 添加  .cache/    dist/    node_modules/"
 
 git pull
 
 git push
 
 
 
 
 打包
 
 npx parcel build index.html --public-url="./"
 


在每一次改动时都提交一下，实时保存记录，方便后期查询

github 自动打开页面（安装失败）

npm i -g git-open

git open




单元测试

nmp i -D chai

git add .
 
git commit -m "安装chai"

git pull

git push




