# typora-2-html
typora编写的markdown文档转为带大纲的html单文件



# 使用说明

将项目clone到本地

```sh
git clone git@github.com:suliyea/typora-2-html.git
```



在typora编写的md文档, 正文头部引入js和css, 然后在typora中文件->导出html即可

```html
<script type="text/javascript" src="你本地目录/2html/jquery-3.3.1.min.js"></script>
<script type="text/javascript" src="你本地目录/2html/2html.js"></script>
<link rel="stylesheet" type="text/css" href="你本地目录/2html/style.css">
```

