# 雨云自动续费

使用Github Action自动签到雨云，免费易用<br>

作者：**[XJHya](https://github.com/xjh2009)**<br>
B站，抖音，名字不一，转载请注明作者<br>

## 使用方式

### Fork本项目
Fork本项目<br>
#### 启动Action
进入您自己的项目，点击Action，启用Github Action功能<br>
#### 配置环境变量
进入Settings->Secret and variables->Actions->New Repository secret
将你的Name输入RAINYUN_APIKEYS<br>
将你的Secret输入APIKEY<br>
例子
```
APIKEY1,APIKEY2,APIKEY3
```
配置成环境变量

### 定时执行
修改/.github/workflows/renew.yaml文件 <br>
每日北京时间6点自动续费<br>

## 相关项目
[海绵联机自动签到](https://github.com/xjh2009/hmmc-renew)
[蓝天云自动续费](https://github.com/xjh2009/lty-renew)
