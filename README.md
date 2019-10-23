## gulu-demo1

## Vue UI 组件库

## by Jasmine


```
//新建本地分支
git branch button-input
touch src/row.vue
touch src/col.vue
git status -sb
git add .
git commit -m "add row and col"
git pull
git push
//本地分支推送到远程分支
git push origin button-input:button-input


git checkout button-input
//Switched to branch 'button-input'

git checkout master
//Switched to branch 'master'
```


## 介绍

这是我在学习 Vue 过程中做的一个 UI 框架，希望对你有用。

##  开始使用

1. 添加 CSS 样式 使用本框架前，请在 CSS 中开启 border-box

```

 *,*::before,*::after{box-sizing: border-box;}
 ```

  IE 8 及以上浏览器都支持此样式。
    
 你还需要设置默认颜色等变量（后续会改为 SCSS 变量）
 ```
html {
  --button-height: 32px;
  --font-size: 14px;
  --button-bg: white;
  --button-active-bg: #eee;
  --border-radius: 4px;
  --color: #333;
  --border-color: #999;
  --border-color-hover: #666;
}
```

IE 15 及以上浏览器都支持此样式。

2. 安装 gulu
```
npm i --save xxx
```

3. 引入 gulu
```
import {Button, ButtonGroup, Icon} from 'xxx'
import 'frank-test-1-1/dist/index.css'

export default {
  name: 'app',
  components: {
    'g-button': Button,
    'g-icon': Icon
  }
}
```


```
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
```



