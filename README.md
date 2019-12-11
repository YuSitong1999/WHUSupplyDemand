# 武汉大学供需撮合小程序
Wuhan University Supply and Demand WeChat Mini Program

# 分工
总体计划：两个人设计、写无关技术的文档；五个人写代码  
* 谭毓洁（负责人）	2017301500224
* 于斯同(教练)	2017301500199			
* 陈泽芳（团队成员）	2017301500284			
* 马萱（团队成员）	2017301500248			
* 胡星灿（团队成员）	2017301500006			
* 高晗（团队成员）	2017301500249			
* 别尔都新·木合塔（团队成员）	2017301500227	

# 工作总结
### 第一周
第一次课上全体成员讨论了小程序提供主要功能，初步的页面设计，陈泽芳和于斯同绘制了界面草图  
复习“网页设计与制作”中学习的内容，参考微信小程序文档学习制作小程序  

### 第二周
第二次课因运动会取消  
于斯同在陈泽芳绘制草图的基础上进一步设计，实现了“首页”“发布消息”“我的”三个界面的大体框架，初步实现发布、查看供需消息的功能。  
胡星灿完成了第三次课第一阶段展示的ppt，并进行了展示。  

### 第三周
马萱完成了发布消息界面的大部分代码，暂未实现上传图片和写数据库  
于斯同合并马萱的工作，初步实现了发布带图消息  

### 第五周
陈泽芳、马萱完成我的界面及首页的详细设计与美化，
我的：添加删除按钮、实现我的消息查询与删除功能、美化消息框
首页：添加了轮播图片、分类条的设计、消息框的美化、头像的添加、按钮样式的修改


# 工作计划

## 第四周结束前
### 必要

#### 首页
实现消息分类，其中一类开始时默认选中，名为“全部”  
消息框呈现多条消息，纵向有适当间隔，消息框有纵向滚动条，保证完整显示  
每条消息显示格式相同，有头像、网名、标题  
点击下方的首页或我的，改变参数，在同一页重新加载  

#### 我的 页面
右上显示登录用户的网名  
消息框呈现多条消息，纵向有适当间隔，消息框有纵向滚动条，保证完整显示  
每条消息显示格式相同，有标题、删除按钮，进行中消息有完成按钮  
点击下方的首页或我的，改变参数，在同一页重新加载  

#### 发布消息页
要求输入标题  
要求选择分类  
要求输入内容  
可以选择有限张图片（比如最多三张）  

#### 消息详情页 
展示消息发送者的头像、网名  
展示消息的标题、类别、内容、附图  
下滑显示评论，评论分若干栏  
每栏中第一条评论显示发送者头像、网名、评论内容，其余评论不显示头像  
可以发送评论到已有栏的最后或新的一栏


#### 可选的
界面美化，发布消息按钮替换为图片。  
提高消息现实的速度。  
调整页面间传递数据的方式。  
整理页面的css  

# 云开发 quickstart

这是云开发的快速启动指引，其中演示了如何上手使用云开发的三大基础能力：

- 数据库：一个既可在小程序前端操作，也能在云函数中读写的 JSON 文档型数据库
- 文件存储：在小程序前端直接上传/下载云端文件，在云开发控制台可视化管理
- 云函数：在云端运行的代码，微信私有协议天然鉴权，开发者只需编写业务逻辑代码

## 参考文档

- [云开发文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)

