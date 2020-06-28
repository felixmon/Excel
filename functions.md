
## TRANPOSE
使得一行的数值根据另外一列的数值的改变而改变，关键点是函数输入结尾是以数组形式（CTRL+SHIFT+ENTER），而不是直接ENTER
https://support.microsoft.com/zh-cn/office/transpose-%e5%87%bd%e6%95%b0-ed039415-ed8a-4a81-93e9-4b6dfac76027?ui=zh-cn&rs=zh-cn&ad=cn

## 多级下拉菜单
一级菜单决定下一级菜单的内容，举例：一级菜单选择江苏省，那么二级菜单只能出现南京市、苏州市，而不会出现西安市。功能实现的核心：
1. 定义名称
2. 下拉菜单（数据验证-序列）的值采用INDIRECT形式

https://zhuanlan.zhihu.com/p/74687468

## VLOOKUP 结果如果是空值则不显示0
在公式后面加一个 &""
=VLOOKUP(A16,Sheet1!A:B,2,0)&""
