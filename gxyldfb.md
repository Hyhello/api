### 各学院楼栋分布

##### 简要描述:

- 各学院楼栋分布接口

##### 请求URL:

- api/buildings/getgxyldfb

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
            value: 10
        },
        {
            name: "材料学院",
            value: 20
        },
        {
            name: "交通物流学院",
            value: 30
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| name | string | 名称 |
| value | int | 值 |
