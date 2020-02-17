# VueStudy2019

## 新建一个git仓库

```
echo "# VueStudy2019" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/juedui0769/VueStudy2019.git
git push -u origin master
```

### 本地

- D:\wxgNodejs\VueStudy2019

### vue

- <https://cn.vuejs.org/> , vue官网
- <https://cn.vuejs.org/v2/api/> , API
- <https://cli.vuejs.org/zh/> , Vue CLI

### npm常用命令

- <https://npm.taobao.org/>

```
npm help config
npm config list

npm config set registry https://registry.npm.taobao.org/
npm config get registry
```

### Vue CLI

```
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```

```
vue create my-project
# OR
vue ui
```

### git

```
git remote add origin https://github.com/juedui0769/VueStudy2019.git
git remote add gitee https://gitee.com/his0769/VueStudy2019.git
```

**tag**

```
git tag 01init
```

**branch**

```
git checkout -b 01hello
git branch -av
git merge master
```

```
git push gitee 01hello
git push origin 01hello
```

- ![](./imgs/git_push_TortoiseGit.png)
- 使用"TortoiseGit"可以方便的向远程提交, 如上图


### 极客时间-vue

<https://github.com/geektime-geekbang/geektime-vue-1>

极客时间上的这个vue视频，有点垃圾




