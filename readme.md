# ZJU场馆预约脚本
## Pre-processing

1. 执行脚本前需要安装需要的包
2. 在`main.py`所在目录下创建`config.json`，内容为统一身份验证的用户名和密码：
```json
{
  "username": "username",
  "password": "password",
  "buddies": [
    {
      "username": "username",
      "password": "password"
    },
    {
      "username": "username",
      "password": "password"
    }]
}
```
3. 输入的内容为此次脚本的预约内容：
```
39 （场地编号）
2021-08-31 （预约日期）
14:30 15:30 （预约场次的起始时间）
2 （连续场数 1/2)
伙伴名称（空格分隔）
电话号码
2021-08-29 07:59:05 （脚本执行时间）
```