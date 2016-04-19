# LXAlertViewDemo
* 一款AlertView提示框，高度可根据内容自适应。

---
#####本控件[项目地址](https://github.com/xinge1/LXAlertViewDemo)，希望能给个start，欢迎大家交流指正。
<br>
---
######简单说明
有简单动画效果,高度可根据内容自适应，点击事件采用block回调。如果项目有强制更新的需求可以设置点击按钮AlertView不消失
<br>

效果图<br>
![](http://upload-images.jianshu.io/upload_images/292993-64876408eb4e9ad1.gif?imageMogr2/auto-orient/strip)

###使用方法
####1.导入<br>
```#import "LXAlertView.h"```
####2.初始化方法<br>
```
    LXAlertView *alert=[[LXAlertView alloc] initWithTitle:@"提示" message:@"自定义alertview,可以自动适应文字内容。" cancelBtnTitle:@"取消" otherBtnTitle:@"确定" clickIndexBlock:^(NSInteger clickIndex) {
        NSLog(@"点击index====%ld",clickIndex);
    }];
    [alert showLXAlertView];

```
---
[简书地址](http://www.jianshu.com/p/8706725bcc8a)
