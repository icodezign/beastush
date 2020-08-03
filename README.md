# 野醺 - 专注新手零失败的调酒教程
## 写在前面
疫情期间，在家办公时间比较灵活，一方面折腾下调酒，以平衡日常禁足的烦躁。另一方面想全方位升级一下自己的技术栈。毕竟移动端的技术方向已经明确，目测不会有革命性的洗东西出来。

整个项目服务器是基于tornado开发，囊括社区类业务的完整REST API，缓存系统以及图片基本变换及存储服务。

iOS端采用swift5，除了基本的网络请求部分用了moya，其余组件也都是用最新的代码写的，毕竟swift5轮子比较少，虽说工作量比较大，但也在射程之内。由于没有用storyboary和swiftUI，采用纯swift构建出来，整个项目编译完也就10M(可能有3M还是微博的api)，在appsore上同类应用中应该是最小的。

android端采用kotlin开发，这个与我而言是萌新，不过用了之后很舒爽，再也不想写java了，这个项目采用组件式开发，支持 android x, 除了系统相册之外，所有的组件也都是自己封装比较独立（再也不想为第三方组件引发的兼容性问题做妥协了）。

web端采用vue2开发，主要是对移动端的维护系统，以及微信公众号的相关功能。

## 线上体验
iOS: https://apps.apple.com/cn/app/id1502658887  
android: https://sj.qq.com/myapp/detail.htm?apkName=com.icodezign.beastush  
官网: https://beastush.com/download  


## 项目概况
![00](https://github.com/icodezign/beastush/blob/master/00.jpg)
![01](https://github.com/icodezign/beastush/blob/master/01.jpg)
![02](https://github.com/icodezign/beastush/blob/master/02.jpg)
![03](https://github.com/icodezign/beastush/blob/master/03.jpg)
![04](https://github.com/icodezign/beastush/blob/master/04.jpg)
![05](https://github.com/icodezign/beastush/blob/master/05.jpg)
![06](https://github.com/icodezign/beastush/blob/master/06.jpg)
![07](https://github.com/icodezign/beastush/blob/master/07.jpg)
![08](https://github.com/icodezign/beastush/blob/master/08.jpg)
![09](https://github.com/icodezign/beastush/blob/master/09.jpg)
![10](https://github.com/icodezign/beastush/blob/master/10.jpg)
![11](https://github.com/icodezign/beastush/blob/master/11.jpg)
![12](https://github.com/icodezign/beastush/blob/master/12.jpg)
![13](https://github.com/icodezign/beastush/blob/master/13.jpg)
![14](https://github.com/icodezign/beastush/blob/master/14.jpg)
![15](https://github.com/icodezign/beastush/blob/master/15.jpg)
![16](https://github.com/icodezign/beastush/blob/master/16.jpg)
![17](https://github.com/icodezign/beastush/blob/master/17.jpg)
![18](https://github.com/icodezign/beastush/blob/master/18.jpg)
![19](https://github.com/icodezign/beastush/blob/master/19.jpg)
![20](https://github.com/icodezign/beastush/blob/master/20.jpg)
