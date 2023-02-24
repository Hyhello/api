### 楼栋折旧

##### 简要描述:

- 楼栋折旧接口

##### 请求URL:

- api/datashow/getldzj

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
        ljzj: 1000,
        jz: 1000
    }
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| ljzj | int | 累计折旧 |
| jz | int | 净值 |
