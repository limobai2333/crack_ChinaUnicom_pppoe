# 联通网络拨号软件破解
 *山东财经大学明水校区测试通过*
## 简介
- **一个简单的脚本能转换你的账号密码，不要借助拨号软件就能登录**
- **不再依赖联通提供的拨号软件，使用系统原生的拨号功能，更加稳定**  
- **解除拨号软件的限制终端设备数量，多台设备可以共用一个账号**  

## 使用方法

### 转换账号名称
```
这是最重要的一步，从原理上来说，为什么你直接拨号不行，反而用人家给的拨号器却可以拨号？  
真正的原因是你输入的账号密码是"错误"的.
联通给的拨号器，会在你输入的账号密码后面添加一些字符，因为是固定的，所以这就给破解留下了机会，我们只要还原添加的字符串，就能使用原生拨号
```


**账号（一般为营业厅给你的手机号）后面加**
```
@zqjjxywo201
```

*example:*  
*你的账号为*  
**12345678**  
*那么实际的账号为*  
**12345678@zqjjxywo201**

**密码**
```
 
```
你看不到是对的:smile:   

原因：

![image](https://raw.githubusercontent.com/shawzh/crack_ChinaUnicom_pppoe/master/ascii1.gif) 

学过计算机的应该知道这是一张ascii表，这个看不到的字符就是start of heading，简称`SOH`，密码前面就是这个字符  
*我们看不见他，也无法用键盘输入，但是可以通过程序生成*


*Example:*  
*你的密码为*  
**12345678**  
*那么实际的密码为*  
**`SOH`12345678**




### **使用方法非常简单**

如果你懒得写程序转换，这里有现成写好的
- [点击此链接转换](http://101.200.58.171/chnge.html)  

在上图第一个框中输入账号名，
一般为联通营业厅给你的手机号

在第二个框中输入密码，然后点击转换

![image](https://raw.githubusercontent.com/shawzh/crack_ChinaUnicom_pppoe/master/Sketch.png)  
`完整复制下面两个框中的所有内容一定要完整复制！！！！`
- 电脑原生拨号方法：  
打开 **网络共享中心**，  
点击 **建立新的链接或网络**，  
选择 **链接到因特网**，  
选择 **PPPOE**  
