### 按房间大类统计面积

##### 简要描述:

- 按房间大类统计面积接口

##### 请求URL:

- api/buildings/getafjdltjmj

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
            name: "自动化学院",
            value: 28865.59,
        },
        {
            name: "材料学院",
            value: 70589.44,
        },
        {
            name: "交通物流学院",
            value: 76567.2,
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| name | string | 名称 |
| value | int | 值 |
