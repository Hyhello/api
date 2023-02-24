### 楼栋使用状态

##### 简要描述:

- 楼栋使用状态接口

##### 请求URL:

- api/buildings/getldsyzt

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
            name: '在用',
            value: 307
        },
        {
            name: '在建',
            value: 1
        },
        {
            name: '正在维修',
            value: 3047
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| name | string | 名称 |
| value | int | 值 |