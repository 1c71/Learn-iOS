# 学 iOS 开发写的笔记和代码
#### 环境 
硬件:  Mac mini  
系统:  OS X EI Caption (10.11)  
Xcode 版本:  7.0.1  


### 学习来源

https://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/
http://blog.csdn.net/hherima/article/details/8620941
http://ios-blog.co.uk/tutorials/beginners-ios-development-objective-c/





<br/>
### 要学的东西
1. APP ICON + 名字
2. 发请求
3. 复杂的视觉效果
2. 打包上传Apple Store
5. 怎么适配不同版本？ iPhone 5, 5s



<br/>
<br/>
### 小备注
UIKit 是 iOS 开发的核心框架  必学  


<br/>
<br/>
## 学习资料
1. (OC) 传智播客的 iOS 视频
2. (Swift) Youtube -  channel: thenewboston - __iOS Development with Swift__



---



<br/>
<br/>
## 第 1 个 OC 程序

#### 1. 新建一个 1.m 文件

内容如下
```Objective-C

#import <Foundation/NSObjCRuntime.h>
// NSObjCRuntime have the NSLog..

int main()
{

    NSLog(@"hello");
    return 0;


}
```

#### 2. 运行

```Objective-C
cc -c 1.m
// 编译出 o

cc 1.o -framwork Foundation
// 编译出 out 文件

./a.out
// 运行
```





<br/>
<br/>
## 第 2 个 OC 程序
```Objective-C
#import <Foundation.h>

int main()
{

NSLog(@"hello");
return 0;

}
```














