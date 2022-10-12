# learning-record
## 环境依赖
vue<br>
element ui
## 网页简介
本页是一个学习记录区，使用todolist的基本框架完成
## 功能说明
点击白色框并输入内容后，敲回车或者点击右侧的add按钮可将想要创建的学习记录添加到下方列表中。点击每条记录右侧的圆形按钮会删除该条记录。双击左下方白色按钮会更改主题色；双击右下方红色按钮会清空当前列表中的所有记录
## 代码实现
1、整个列表放入container中，其中input做输入框，当聚焦于input时，显示输入光标；失焦时回到“点击添加学习记录”
2、使用vue和element ui实现主题颜色切换和清空所有学习记录的功能
3、JS函数：<br>
addNew函数实现新增学习记录功能，同时里面使用了addNewButton函数，添加新增记录的删除按钮<br>
save函数使用localStorage保存学习记录<br>
reMove函数实现记录的删除功能<br>
getcurrenttime获取当前时间<br>
使用三个事件监听可以实现点击add添加、回车添加和点击删除功能
## 目录结构描述
├── Readme.md // help
├── index.html
├── vue.js
