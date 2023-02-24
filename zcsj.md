### 资产数据

##### 简要描述:

- 资产数据接口

##### 请求URL:

- api/datashow/getzcsj

##### 请求方式

- GET

##### 参数

- 略

##### 返回示例

``` javascript
{
    code: 200,
    message: '请求成功',
    data: {
        zczs: 100,
        tysb: 41,
        zysb: 1,
        jj: 10
    }
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| zczs | int | 资产总数 |
| tysb | int | 通用设备 |
| zysb | int | 专用设备 |
| jj | int | 家具 |