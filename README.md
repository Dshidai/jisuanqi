# jisuanqi
这是我看安豆的视频写的第一个APP，哈哈哈<br>顺便当天学了下Readme.md的语法，给需要的朋友们！！
=================================================================================


## 横线
空1行后，下面添加3个  - 或者  _ 或者  * 号，显示1条浅浅的横线

---

___

***


## 标题
一共有6个等级，文本前添加1个 # ，再加空格，表示一级标题，前面2个 # 表示二级坐标，以此类推...
# 这是一级标题（也是大标题）
## 这是2级标题（也是中标题）
### 这是3级标题
#### 这是4级标题
##### 这是5级标题
###### 这是6级标题
大标题（文本下面加 = ）
=
中标题（文本下面加 - ）
-

## 换行
文本要换行<br>记得在文本前面加上 \<br>
<br>(\为转义符号，将上面的\<br>显示出来时用)
<br>文本1
<br>文本2


## 排版样式(全部高亮)
    文本前面添加两个tab可以实现文本前留空格,添加tab也使文本高亮
    1 多行
     2 文本
      3 也是   
       4 这个
        5 道理


## 文本高亮
高亮部分用1对 \`（tab上方那个）包围起来<br>
这 是 一 个 `全 新` 的 `语 法` 结 构
<br>    `4`   8   `4`   3   <br>
高亮部分用3对 \`（tab上方那个）包围起来<br>
```
测试文本1<br>测试文本2<br>
测试文本3<br>测试文本4<br>
```
测试文本5<br>测试文本6<br>


## 插入符号
### 星号
*输入星号不加空格
### 实心圆点
*   前面1星号加空格
+   前面1加号加空格
-   前面1减号加空格
### 多级符号
共有3个等级的符号，实心圆形，空心圆形，实心方形
* 1个星号加空格（一级符号）<br>
  * 2个空格后加星号加空格（二级符号）<br>
    * 4个空格（即1个tab）后加星号加空格（三级符号）<br>


## 体、粗体、删除线
效果-->语法<br>
*斜体1*                    1对*<br>
**粗体1**	                 2对*<br>
***斜粗体1***	            3对*<br>

_斜体2_	                 1对_<br>
__粗体2__	                 2对_<br>
___斜粗体2___	            3对_<br>

~~删除线~~	                2对~<br>
***~~斜粗体删除线1~~***	  3对*加2对~<br>
~~***斜粗体删除线2***~~	  2对~加3对*<br>


## 缩进
每缩进1下就在前面添加1个\>
>数据结构<br>
此处添加数据结构的描述
>>树<br>
此处添加树的描述
>>>二叉树<br>
此处添加二叉树的描述  
>>>>平衡二叉树<br>
### 此处添加对平衡二叉树的描述  
>>>>>满二叉树<br>
此处添加满忙二叉树的描述



## 文本超链接
`格式:`\[文本内容](链接地址 "停留文本")<br>

[D时代的Github](https://github.com/Dshidai "haha")  
 

## 插入图片
`格式:`!\[标识内容](链接地址 "停留文本")<br>
<br>(前面添加了感叹号以后就直接显示出图片了)
### 网络（外部url）图片<br>
#### 方法1
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
#### 方法2
[![baidu][baidulogo] "原来没有图片直接显示"]
>使用URL标识符能达到复用的目的，一般把全文所有的URL标识符统一放在文章末尾，这样看起来比较干净。

### 仓库（github）图片<br>
![计算器里的图片](https://github.com/Dshidai/jisuanqi/blob/master/src/main/res/mipmap-hdpi/ic_launcher.png "什么鬼")












-----------------------------------------------------------------------------------------------
本文末尾：<br>
[baidulogo]:http://www.baidu.com/img/bdlogo.gif

