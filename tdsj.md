### 土地数据

##### 简要描述:

- 土地数据接口

##### 请求URL:

- api/datashow/gettdsj

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
        tdsyqmj: 10000,
        ldzjzmj: 10000,
        fjzsymj: 10000
    }
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| tdsyqmj | int | 土地使用权面积 |
| ldzjzmj | int | 楼栋总建筑面积 |
| fjzsymj | int | 房间总使用面积 |