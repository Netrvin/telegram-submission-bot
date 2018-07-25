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
