# telegram-submission-bot

## 准备
* 安装Python并运行`pip install python-telegram-bot --upgrade`
* 创建1个Bot、1个Group和1个Public Channel

## 配置
打开`config.json`并配置
```
{
    "Admin": 0,                  //管理员用户ID（通常为8~9位数字）
    "Token": "",                 //Bot的Token
    "Group_ID": 0,               //无需填写
    "Publish_Channel_ID": ""     //频道ID（如：@channel）
}
```
在审稿群中输入`/setgroup`

## 运行
```
python main.py
```

## 使用
### 投稿
![Screenshot](https://github.com/Netrvin/telegram-submission-bot/raw/master/Readme_Img/Screenshot1.jpg)

将消息发送至机器人，选择是否保留消息来源后即可完成投稿（若转发他人的消息，则不可选择不保留消息来源）
可接收的投稿类型:
* 文字
* 图片
* 音频/语音
* 视频
* 文件

### 审稿
![Screenshot](https://github.com/Netrvin/telegram-submission-bot/raw/master/Readme_Img/Screenshot2.jpg)

所有在审稿群中的用户，点击采用即可完成审稿
在群中回复稿件本身（不是稿件详情），可在采用的同时对其进行评论

## Todo (Features)
- [x] 评论稿件
- [x] 转发他人的消息禁止匿名，避免版权问题
- [x] 采用稿件后通知投稿人
- [x] 稿件详情添加投稿/审稿人内链
- [x] 匿名发布稿件
- [ ] 投稿统计
- [ ] 多语言
