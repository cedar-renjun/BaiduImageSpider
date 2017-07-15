# BaiduImageSpider
百度图片爬虫，基于python3

**Note**
原工程地址：https://github.com/kong36088/BaiduImageSpider
感谢作者的辛苦努力和开源

## 特性
- 自动搜索指定关键词的百度图片
- 自动下载，并保存到本地文件夹
- 指定下载数量和搜索起始页

## 用法
1.  安装python3
2.  用以下3种方式自动下载图片
  1. 默认参数（从第1页开始下载，下载数量60，小黄图）
  `python index.py ‘小黄图’`
  2. 控制下载数量（从第1页开始下载，下载200张，小黄图）
  `python index.py ‘小黄图’ 200`
  3. 控制下载数量和起始页数（从第3页开始下载，下载200张，小黄图）
  `python index.py ‘小黄图’ 200， 3`

## 参考资料
1. [多线程下载百度图片](http://lovenight.github.io/2015/11/15/Python-3-%E5%A4%9A%E7%BA%BF%E7%A8%8B%E4%B8%8B%E8%BD%BD%E7%99%BE%E5%BA%A6%E5%9B%BE%E7%89%87%E6%90%9C%E7%B4%A2%E7%BB%93%E6%9E%9C/)
2. [python3 教程](http://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000)
