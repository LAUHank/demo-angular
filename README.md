# 参考
https://www.angular.cn/guide/quickstart

# 创建并初始化项目
ng new demo-angular

y

使用方向键上下移动选择CSS

稍等

# 启动开发服务器
cd demo-angular

ng serve

Ctrl + C 可以停止服务器

# 浏览器访问
http://127.0.0.1:4200/

# 发布到 GitHub
ng build --prod --output-path docs --base-href

当构建完成时，把 docs/index.html 复制为 docs/404.html

提交你的更改，并推送

在 GitHub 的项目页中，把该项目配置为从 docs 目录下发布

你可以到 `https://<user_name>.github.io/<project_name>/` 中查看部署好的页面

如 https://LAUHank.github.io/demo-angular/

# DemoAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.0.6.

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
