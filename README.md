##### 简要描述

- 申报要素规范化接口

##### 请求URL
- ` http:// `
  
##### 请求方式
- POST 

##### 参数

|参数名|必选|类型|说明|
|:----       |:---|:----- |-----   |
|hs_code     |是  |string | 商品编码  |
|declaration_elements |是  |string | 申报要素 |
|in_out_type    |否  |string | 进出口类型 |

##### 返回示例 

```
  {
    "error_code": 0,
    "data": {
      "uid": "1",
      "username": "12154545",
      "name": "吴系挂",
      "groupid": 2 ,
      "reg_time": "1436864169",
      "last_login_time": "0",
    }
  }
```

##### 返回参数说明 

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|groupid |int   |用户组id，1：超级管理员；2：普通用户  |

##### 备注 

- 更多返回错误代码请看首页的错误代码描述



