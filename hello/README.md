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

### 使用`anywhere`启动一个服务完成练习

- `anywhere`是我经常使用的一个nodejs小工具，我本地已经安装了，它可以启动一个web服务。
- 我现在改为使用最原始的方式来完成Vue的启蒙教程。
- 在`study`目录下继续新建文件，这回不再新建`*.vue`的文件，而是直接创建`*.html`的文件，vue的引用就使用cdn
- 使用我已知的 <https://www.bootcdn.cn/vue/> 。
- 创建文件`02VueStart.html`
- 在`study`目录下运行`anywhere`
- 然后访问 <http://localhost:8000/02VueStart.html>

### Vue实例

- <https://cn.vuejs.org/v2/guide/instance.html>
- 值得注意的是只有当实例被创建时就已经存在于`data`中的属性才是**响应式**的。
- 使用`Object.freeze()`会阻止修改现有的属性，导致响应系统无法再追踪变化。
- 选项/数据
    - <https://cn.vuejs.org/v2/api/#%E9%80%89%E9%A1%B9-%E6%95%B0%E6%8D%AE>
- 实例属性
    - <https://cn.vuejs.org/v2/api/#%E5%AE%9E%E4%BE%8B%E5%B1%9E%E6%80%A7>

### 模板语法

- <https://cn.vuejs.org/v2/guide/syntax.html>
- 插值
- 指令
- 缩写

### 计算属性和侦听器

- <https://cn.vuejs.org/v2/guide/computed.html>
- 计算属性缓存 vs 方法
- 计算属性 vs 侦听属性
































