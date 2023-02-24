### 房间分类

##### 简要描述:

- 房间分类接口

##### 请求URL:

- api/datashow/getfjfl

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
            name: "其他用房面积",
            value: 34031.2,
        },
        {
            name: "公共设施用房面积",
            value: 28865.59,
        },
        {
            name: "教室面积",
            value: 70589.44,
        },
        {
            name: "院系及教师用房面积",
            value: 76567.2,
        },
        {
            name: "实验实习面积",
            value: 133116.97,
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| name | string | 名称 |
| value | int | 值 |
