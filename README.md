![PongNi Logo](https://raw.githubusercontent.com/xuedengheng/pongni/master/logo.png)

# PongNi
一个轻量级的初始化项目工具

<a href="https://www.npmjs.com/package/pongni"><img src="https://img.shields.io/npm/v/pongni.svg" alt="Version"></a>
<a href="https://www.npmjs.com/package/pongni"><img src="https://img.shields.io/npm/l/pongni.svg" alt="License"></a>

# Installation
```
npm install pongni -g
```

# Usage
打开终端输入`pongni` 或者 `pongni -h` , 展示pongni的`command`列表:
```
  Usage: pongni <command>


  Commands:

    list   List all the templates
    init   Generate a new project

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
```

### init
通过这个`command`可以去选择模版然后初始化项目
```

? Project name: projectName
? Select template: vue
? Project description: A description of project!
? Where to init the project: ./

  pongni ·  Generated "projectName".

# Project has been initialized successfully!
# ==========================================

To Get Started:

  cd projectName
  npm install
  npm run dev
  npm run build

```


### list
展示所有的模版列表.
```
$ pongni list

┌───────┬────────────────┬────────┐
│ Name  │ Template       │ Branch │
├───────┼────────────────┼────────┤
│ vue   │ vue-template   │ master │
├───────┼────────────────┼────────┤
│ mpvue │ mpvue-template │ master │
├───────┼────────────────┼────────┤
│ koa2  │ koa2-template  │ master │
└───────┴────────────────┴────────┘
```

# Template
```
vue-template    ->  vue模版
koa2-template   ->  koa2模版
mpvue-template  ->  mpvue模版
...
后期会慢慢更新
```

# License
MIT.









