### 单位用房明细

##### 简要描述:

- 单位用房明细接口

##### 请求URL:

- api/units/getunitdwyfmx

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
            id: 1,
            dwdm: '0000',
            dwmc: "其他",
            ldsl: "31",
            fjsl: "563",
            fjmj: "20918.26",
            demj: "0",
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| id | int/string | 主键（用于查询详情） |
| dwdm | string | 单位代码 |
| dwmc | string | 单位名称 |
| ldsl | string | 楼栋数量 |
| fjsl | string | 房间数量 |
| fjmj | string | 房间面积 |
| demj | string | 定额面积 |
