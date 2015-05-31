# SwiftTips
各种Swift开发过程中遇到的小技巧


## 设置状态栏为不透明（设置状态栏不覆盖内容）

*Fig 1a. 透明的状态栏，内容被状态栏覆盖*

![](https://raw.githubusercontent.com/machinecc/SwiftTips/master/Images/1a.png)



*Fig 1b. 目标：不透明的状态栏，内容不被状态栏覆盖*

![](https://raw.githubusercontent.com/machinecc/SwiftTips/master/Images/1b.png)



解决方法：

Step 1. 添加Top Layout Guide和WebView的vertical constraint 
![](https://raw.githubusercontent.com/machinecc/SwiftTips/master/Images/1c.png)




Step 2. 设置constraint的值为9
![](https://raw.githubusercontent.com/machinecc/SwiftTips/master/Images/1d.png)






