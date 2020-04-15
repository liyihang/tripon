## 1、下载Vue-cli

在这里我已经默认大家已经安装好`node`和`npm`。

下载Vue-cli可以直接使用`npm install -g @vue/cli`来下载。

```shell
npm install -g @vue/cli
#or
yarn install -g @vue/cli
```

安装完成后，我们就可以在命令行中使用`vue`了。

```shell
vue --version
```



## 2、项目创建

使用新版本的`Vue-cli`脚手架创建项目如下：

```shell
vue create app
```



![截屏2020-04-14 下午6.29.27](/Users/doudou/Desktop/tripon/Vue构建旅游网站.assets/截屏2020-04-14 下午6.29.27.png)



## 3、单页面应用和多页面应用

单页面应用：将所有的页面活动放在一个页面中，页面初始化就加载所有的HTM,JS和CSS。所有的页面跳转都是通过JS的替换页面渲染。

**单页面应用优缺点：**

优点：页面切换快，交互体验好；利于前后端分离开发等。

缺点：首屏慢，不利于SEO。

## 4、关联github

