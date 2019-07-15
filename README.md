# 百度URL关键字采集器

安装源码所需python库

使用方法：

`python3 baidu.py inurl:php?id= 300`

inurl:php?id= 关键字

300 搜索页数(最好不要超过300，超过300后会导致页面重复会死循环，这是百度的问题，你们也可以自己解决一下)

源码中
`remove = ['http://baike.baidu.com','http://zhidao.baidu.com','http://baijiahao.baidu.com','http://wk.baidu.com']`

remove 列表存放的是去除网址，没有对域名进行匹配，只是单纯的字符串匹配。
