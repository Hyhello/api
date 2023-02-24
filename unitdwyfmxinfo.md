### 单位用房明细-弹出（右上）

##### 简要描述:

- 单位用房明细-弹出（右上）接口

##### 请求URL:

- api/unit/getunitdwyfmxinfo

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
    data: {
        fj: 402,
        yrdf: 2,
        wbgsjs: 12,
        cbry: 2,
        zmj: 15523
    }
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| fj | int | 房间 |
| yrdf | int | 一人多房 |
| wbgsjs | int | 无办公室教师 |
| cbry | int | 超标人员 |
| zmj | int | 总面积 |
