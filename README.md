# hexo-wiki


## 1. 介绍
想搞一个 blog 型的个人知识管理网页，找了半天，发现这个主题接近一些，jQuery 从零开始造轮子还是有点累，遂 fork 了一个前人的仓库～


## 2. 工程配置
安装关键依赖
```bash
npm install hexo-directory-category --save
```

修改工程配置
『_config.yml』其中必要修改的有以下

 ```yml
# 获取文件相对目录的图片
post_asset_folder: true

# 不需要高亮，使用了highlight.js
highlight:
    enable: false
    line_number: false
    auto_detect: false
    tab_replace:

# 修改主题
theme: hexo-wiki
 ```


## 3. 修改
+ 调整字体和样式
+ 修复模版解析 bug
