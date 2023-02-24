### 单位用房明细-弹出（单位历年定额情况）

##### 简要描述:

- 单位用房明细-弹出（单位历年定额情况）接口

##### 请求URL:

- api/unit/getunitdwyfmxdeqk

##### 请求方式

- GET

##### 参数

``` javascript
// 前端：params， 后端注解：@RequestParam
{
    id: 1     // 主键
}
```

##### 返回示例

``` javascript
{
    code: 200,
    message: '请求成功',
    data: [
        {
          year: '2020年',
          area: 15929.00,
          actualArea: 15000.13
        },
        {
          year: '2021年',
          area: 15000.00,
          actualArea: 15123.13
        },
        {
          year: '2022年',
          area: 14929.00,
          actualArea: 15223.13
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| year | string | 年度 |
| area | float | 定额面积 |
| actualArea | float | 实际面积 |
