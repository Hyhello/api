### 学院用房规模

##### 简要描述:

- 学院用房规模接口

##### 请求URL:

- api/datashow/getxyyfgm

##### 请求方式

- GET

##### 参数

- 略

##### 返回示例

``` javascript
{
    code: 200,
    message: '请求成功',
    data: [
        {
            name: "南湖南院",
            value: 338285.22,
        },
        {
            name: "马区东院",
            value: 234666.81,
        },
        {
            name: "余家头校区",
            value: 222654.49,
        },
        {
            name: "马区西院",
            value: 186981.14,
        },
        {
            name: "南湖北院",
            value: 93442.91,
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| name | string | 名称 |
| value | int | 值 |
