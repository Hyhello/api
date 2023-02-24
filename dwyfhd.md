### 单位用房核定

##### 简要描述:

- 单位用房核定接口

##### 请求URL:

- api/datashow/getdwyfhd

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
        { name: "自动化学院", type: '定额面积', value: 27190.89 },
        { name: "自动化学院", type: '实际面积', value: 7072.49 },
        { name: "材料学院", type: '定额面积', value: 20033.03 },
        { name: "材料学院", type: '实际面积', value: 18296.26 },
        { name: "交通物流学院", type: '定额面积', value: 13845.84 },
        { name: "交通物流学院", type: '实际面积', value: 14425.29 },
        { name: "汽车学院", type: '定额面积', value: 13845.84 },
        { name: "汽车学院", type: '实际面积', value: 17529.44 },
        { name: "机电学院", type: '定额面积', value: 19479.85 },
        { name: "机电学院", type: '实际面积', value: 18944.28 }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| name | string | 名称 |
| type | string | 类型 |
| value | int | 值 |
