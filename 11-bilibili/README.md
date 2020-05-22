# 哔哩哔哩项目 

## 1.项目初始化

`cnpm install -g @vue/cli` 

 `vue -V` 

 `cnpm install webpack -g` 

 `vue create bilibili` 

 **选择配置（自定义配置**） 

![2018101914002826](img/2018101914002826.png)

**选择css预编译，这里我选择less**

```
`Please pick a preset: Manually select features`` ``Check the features needed ``for` `your project: Router, Vuex, CSS Pre-processors, Linter, Unit`` ``Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by ``default``):`` ``SCSS/SASS`` ``> LESS`` ``Stylus`
```

**语法检测工具，这里我选择ESLint + Standard config**

```
`Please pick a preset: Manually select features`` ``Check the features needed ``for` `your project: Router, Vuex, CSS Pre-processors, Linter, Unit`` ``Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by ``default``): Stylus`` ``Pick a linter / formatter config: (Use arrow keys)`` ``ESLint ``with` `error prevention only`` ``ESLint + Airbnb config``> ESLint + Standard config`` ``ESLint + Prettier`
```

**选择语法检查方式，这里我选择保存就检测**

```
`Please pick a preset: Manually select features`` ``Check the features needed ``for` `your project: Router, Vuex, CSS Pre-processors, Linter, Unit`` ``Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by ``default``): Stylus`` ``Pick a linter / formatter config: Prettier`` ``Pick additional lint features: (Press  to select,  to toggle all,  to invert selection)``>( ) Lint on save ``// 保存就检测`` ``( ) Lint and fix on commit ``// fix和commit时候检查`
```

**接下来会问你把babel,postcss,eslint这些配置文件放哪，这里随便选，我选择放在独立文件夹**

```
`Please pick a preset: Manually select features`` ``Check the features needed ``for` `your project: Router, Vuex, CSS Pre-processors, Linter, Unit`` ``Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by ``default``): Stylus`` ``Pick a linter / formatter config: Prettier`` ``Pick additional lint features: Lint on save`` ``Pick a unit testing solution: Jest`` ``Where ``do` `you prefer placing config ``for` `Babel, PostCSS, ESLint, etc.? (Use arrow keys)``> In dedicated config files ``// 独立文件放置`` ``In package.json ``// 放package.json里`
```

**键入N不记录，如果键入Y需要输入保存名字，如第一步所看到的我保存的名字为my-default**

```
`Please pick a preset: Manually select features``Check the features needed ``for` `your project: Router, Vuex, CSS Pre-processors, Linter, Unit``Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by ``default``): Stylus``Pick a linter / formatter config: Prettier``Pick additional lint features: Lint on save``Pick a unit testing solution: Jest``Where ``do` `you prefer placing config ``for` `Babel, PostCSS, ESLint, etc.? In dedicated config files``Save ``this` `as a preset ``for` `future projects? (Y/n) ``// 是否记录一下以便下次继续使用这套配置。`
```

确定后，等待下载依赖模块

项目创建好后

```
`cd project-name ``// 进入项目根目录``run serve ``// 运行项目`
```

2.