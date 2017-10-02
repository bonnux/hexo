---
title: 如何在hexo博文中插入图片
date: 2017-10-02 10:24:25
tags:
---

# 如何在hexo博文中插入图片

代码如下：

```
{% asset_img 图片文件名 图片说明 %}
```

例子：

```
{% asset_img 01.jpg 这是一张测试图片 %}
```

{% asset_img 01.jpg 这是一张测试图片 %}

注：直接把上述代码放到需要插入图片的位置即可，图片在markdown编辑器中不会显示，因为这是属于hexo的标签插件（详见：[标签插件（Tag Plugins](https://hexo.io/zh-cn/docs/tag-plugins.html)），而不属于markdown语法。

如：

{% asset_img 02.jpg %}