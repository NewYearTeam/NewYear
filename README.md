# NewYear

三个页面均在一个仓库，请在各自所属文件夹内更新。
不会写 Vue 没关系，来不及学的话可以用 HTML 和 CSS 硬造，后面想办法拼

```
NewYear
│  .gitignore
│  package-lock.json
│  package.json
│  README.md
│  vue.config.js
├─public 这里放页面小和Index，不用管
├─src
│  ├─assets 这里放用到的图片和数据(最好以json形式，图片使用png或者svg)
│  ├─components
│  │  ├─Tourism 旅游界面代码放下面
│  │  ├─Gastronomy 美食
│  │  ├─Clothes 衣服
```

## 安装与运行

项目脚手架基于 vue-cli

```
npm install  安装
npm run serve  运行
npm run build  打包(大多数情况不需要)
npm run lint  修复(大多数情况不需要)
```

## Commit 时备注

- 增加从未有过的**功能**，即新增**功能性**提交：`<feat>: +提交说明`
- 不改变**功能**，即新增**非功能性**提交： `<refactor>: +提交说明`
- 优化之前的代码，即更新**功能性**提交： `<update>: +提交说明`
- 提交说明可以使用**中文**

## 分支规范

所有代码请提交到 dev 分支

## GIT 提交规范

- 如果害怕全局配置中的邮箱或姓名泄露个人信息，可以修改全局 Git 配置或在具体项目根目录下使用以下命令修改 Git 提交信息
- `git config user.name "xxxx"` ` git config user.email "xxxxx@xx.xx"`

## 代码规范

- 变量命名尽量使用驼峰命名法(camelCase)
- **请不要随意格式化他人的文件**
- 在引入非官方依赖前请在群内进行说明
