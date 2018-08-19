## 首页
首页主要由三个界面组成,可以完成相应的跳转

## 轮播图
轮播图主要是用js里面的一个库函数做的.代码里面有相关注释.
```bash
    <script src="js/setHomeSetFav.js" type="text/javascript" charset="gb2312"></script>
    <script src="js/myfocus-2.0.1.min.js" type="text/javascript"></script>
    <script src="js/mf-pattern/mF_fancy.js" type="text/javascript"></script>
    <link rel="stylesheet" href="js/mf-pattern/mF_fancy.css" type="text/css">
    <script type="text/javascript">
       myFocus.set({
           id:'picBox'
           /*这段代码用于描述制作焦点图
           1.焦点图初始化的ID,与图片列表最外层的ID一直."picBox"
           2.图标列表的外面,包裹一个class为pic的div
           */
       })
```
## 样式
主要利用的就是浮动以及盒子模型,一些比较基础的前端知识.