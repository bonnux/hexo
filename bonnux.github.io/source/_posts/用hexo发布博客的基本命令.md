---
 title: 用hexo发布博客的基本命令
---
## 1.文章的标题

把下列代码放在md文件的最开头：

```
---
 title: 用hexo发布博客的基本命令
---
```

注：title前面要有一个空格。

## 2.博客的本地测试(其实这步可以跳过)

命令如下：

```
hexo s
```

启动服务器。默认情况下，访问网址为： 
[http://localhost:4000/](http://localhost:4000/)

注：要用cd命令跳转到博客的文件目录下执行上述命令行。

如：

```
cd /xxx/hexo/bonnux.github.io
```

## 3.生成静态网页文件并发布

命令如下：

```
hexo clean && hexo g && hexo d
```

命令解释：

```
hexo clean
```

清除缓存文件 (`db.json`) 和已生成的静态文件 (`public`)。

```
hexo g
```

生成静态文件。

```
hexo d
```

部署网站。