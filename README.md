# Moode实习生招聘家庭作业

## 需求描述：

这是一个行政人员订餐的小应用。具备两个功能1，帮订餐，2，显示订单。
帮订餐是行政帮助别人订餐时使用的
显示订单是行政查看总则的时候使用的。

## 界面参考图片

images/*.png

## 功能要求细则：

### 1.帮订餐

选人，人的数据来自于json文件data/users.json
选餐厅，餐厅的数据来自于json文件data/restaurants.json
选餐，餐的数据来自于json文件data/foods.json

数据是以js的变量方式提供的，不需要Ajax加载

全部选择完之后，点定餐，完成一笔定餐。
订餐完成后，除了餐厅，所有的都要清空。
当餐厅没选则时，无法选择选套餐

### 2.显示订单

多少人已定，明细
多少人未定，明细
显示总计

超越12元的显示红字，显示超了多少元。

## 基本要求：

用javascript和html完成本题
完成需求，代码可以工作。
界面参考“界面参考图片”
代码写在index.html和js文件里。
使用的类库为jquery.mobile-1.2.0，帮助文档在lib文件夹中，也可以可以上网查询。

## 高级要求：

代码可读性高加分
使用对象加分
代码结构清晰加分
有测试加分
重复代码少加分
大部分函数代码少于15行加分
用github提交作业加分
github上每次提交写出注释加分
github上每次提交写的注释清晰加分
github上每次提交只做了一件事加分

大量使用缩写减分
大量使用if else或switch减分
大量js代码没有放在js文件里减分