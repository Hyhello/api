### 单位用房明细-弹出（单位分布）

##### 简要描述:

- 单位用房明细-弹出（单位分布）接口

##### 请求URL:

- api/unit/getunitdwyfmxdwfb

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
            ldmc: '南湖-理学院办公楼',
            fjsl: 30,
            fjmj: 30
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| ldmc | string | 楼栋名称 |
| fjsl | int | 房间数量 |
| fjmj | float | 房间面积 |
