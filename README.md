# 河海大学自动健康打卡
本代码使用Github-Action定时运行，无需Clone到本地，使得水之子能够从繁琐的打卡事件中脱身，从而投身到伟大的社会主义建设活动中去！✨✨✨

# 如本项目对您有所帮助，请帮忙点一个⭐star支持一下作者。

# 步骤
## 1.Fork到自己的仓库
![QQ截图20211004075827](https://user-images.githubusercontent.com/72798603/135777837-9b308e08-44a1-4865-8201-fa114a4004e6.png)
### (Fork完成后应当注意到此时仓库的所有者已经变成了你自己)
![QQ截图20211004080244](https://user-images.githubusercontent.com/72798603/135777950-cddbc6b9-ac46-4369-a669-8842debc20db.png)

## 2.设置Secrets
### 在Setting的Secrets中添加两个repository Secret，名字分别为ACCOUNT和PASSWORD , value分别为学号和密码。
![QQ截图20211004080653](https://user-images.githubusercontent.com/72798603/135778308-58b2c07c-4b84-470b-8671-7c8da21cf0be.png)
![QQ截图20211004080819](https://user-images.githubusercontent.com/72798603/135778301-6f9d5ede-d2b6-476b-b308-775d9578ca1b.png)


## 3.启动 
### 每天早上8：15自动运行（可能需要几分钟,多次测试学校打卡系统好像8点后才开放，在此之前会无法提交） 或者 通过点击star启动（也就是自己给自己点star😏，已经star了取消重新点  PS：别忘了给我点star😝）
![QQ截图20211004081612](https://user-images.githubusercontent.com/72798603/135778510-be7ad586-8aa5-4f34-9d11-b16949dad1c5.png)

## 4.查看活动日志 
### 在Action里查看对应的workflows，黄色表示正在运行，绿色表示已完成，红色表示失败。点进去可以查看具体信息。（第一次执行需要创建工作流）
![QQ截图20211004083013](https://user-images.githubusercontent.com/72798603/135778887-24b2d967-04c9-4fa1-bfd4-1542f467fa7f.png)
![QQ截图20211004082826](https://user-images.githubusercontent.com/72798603/135778890-4875f033-72d8-4791-906b-9662c5eb0af7.png)

## 5.第一次执行时如何创建工作流
### 发现很多同学这一步卡住，如图所示两种情况，如果有工作流就Enable它，如果没有就New一个。
![QQ截图20220412155758](https://user-images.githubusercontent.com/72798603/162910694-9c4d0964-2302-4c5e-a5a8-196692641775.png)


# 参考开源仓库：

1. [浙江大学健康打卡](https://github.com/lgaheilongzi/ZJU-Clock-In)
2. [中南大学nCov健康打卡定时自动脚本](https://github.com/lxy764139720/Auto_Attendance)
3. [河海大学每日健康打卡](https://github.com/chloceg/hhu-daily-health-common)
