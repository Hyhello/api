### 各单位用房分类

##### 简要描述:

- 各单位用房分类接口

##### 请求URL:

- api/units/getunitgdwyffl

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
        { name: "自动化学院", type: '实验室', value: 27190.89 },
        { name: "自动化学院", type: '办公用房', value: 7072.49 },
        { name: "自动化学院", type: '教室', value: 3472.49 },
        { name: "材料学院", type: '实验室', value: 7190.89 },
        { name: "材料学院", type: '办公用房', value: 17072.49 },
        { name: "材料学院", type: '教室', value: 5472.49 },
        { name: "交通物流学院", type: '实验室', value: 190.89 },
        { name: "交通物流学院", type: '办公用房', value: 12072.49 },
        { name: "交通物流学院", type: '教室', value: 4472.49 },
        { name: "汽车学院", type: '实验室', value: 1900.89 },
        { name: "汽车学院", type: '办公用房', value: 2072.49 },
        { name: "汽车学院", type: '教室', value: 442.49 },
        { name: "机电学院", type: '实验室', value: 1000.89 },
        { name: "机电学院", type: '办公用房', value: 472.49 },
        { name: "机电学院", type: '教室', value: 1442.49 }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| name | string | 名称 |
| type | string | 类型 |
| value | int | 值 |
