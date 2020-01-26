# hello

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### 默认使用的是yarn

```
vue create hello
```

- 之前使用`yarn global add @vue/cli`安装的吧？使用上面的命令创建一个vue工程，内部是使用yarn来安装组件的。
- 复习下yarn的命令

```
yarn config list
yarn config get registry
yarn config get cache-folder
```

### 使用npm

```
npm run serve
```

- 使用npm也是可以的

### 官网-起步

- <https://cn.vuejs.org/v2/guide/>
- 介绍 | 声明式渲染

#### 报错

```
error: `data` property in component must be a function (vue/no-shared-component-data) at src\App.vue:14:3:
```

- 使用`vue create hello`创建出来的工程和“介绍 | 声明式渲染”中的有些微的不同，如果完全安装官网文档编写，会出现上面的错误提示。

### Vue CLI | 快速原型开发

- <https://cli.vuejs.org/zh/guide/prototyping.html>
- 上面的报错没有解决，在vue create的工程中也不知道如何修改。无奈，只得从Vue CLI的文档中找解决方案。
- 还原`\hello\src\App.vue`文件，停掉当前启动的服务`Ctrl + C`
- 新建目录和文件`study\01VueStart.vue`,使用`vue serve ./study/01VueStart.vue`启动
    - `yarn global add @vue/cli-service-global`
    - 先安装
- 还是报错，`*.vue`的写法我没搞懂。要去补习下。

















