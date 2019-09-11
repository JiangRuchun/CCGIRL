# CCGIRL

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


## angular官网
https://angular.cn/

## 图标库：
https://www.iconfont.cn/

## sass官网：
https://www.sass.hk/

## 安装angular cli
npm install -g @angular/cli

## 新建项目
ng new ProjectName

## 指向项目
cd ProjectName

## 运行项目
ng serve --open
或者
ng serve -o

## 浏览器本地运行
http://localhost:4200/




## 踩过的坑

### 1.无法使用hgroup

### 2.div元素高度撑满浏览器的内部容器
使用height：100%是没有效果的；
而应该是div{ position: absolute; width:  100%; height: 100%; }

### 3.注意图片大小占用过多内存，加载时一半一半的加载非常的卡顿
注意缩小图片大小，减少内存占用

### 4.需要使用top：100%；时必须是position：absolute； 为relative时只能用px

### 5.