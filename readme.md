# ZJU场馆预约脚本
## Pre-processing

1. 执行脚本前需要安装需要的包
2. 在`main.py`所在目录下创建`config.json`，内容为统一身份验证的用户名和密码：
```json
{
    "configs":[
        {
            "username":"123456", 
            "password":"qwert", 
            "phone":"123456",
            "buddies":[
                {
                    "username": "12345",
                    "password": "12345"
                  }
            ],
            "buddyname":["xxx"]
            },
        {
        "username":"12345", 
        "password":"qqqq", 
        "phone":"12345",
        "buddies":[
            {
                "username": "12345",
                "password": "asdfg"
              }
        ],
        "buddyname":["xxx"]

        }
    ],
    "place_id":39,
    "n_site":1,
    "date":"2022-06-24",
    "candidate_time":["19:30", "20:30", "21:30"]
}
4. 运行脚本：main_new.py