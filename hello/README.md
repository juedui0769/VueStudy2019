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













