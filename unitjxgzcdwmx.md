### 国资处-教学单位明细

##### 简要描述:

- 国资处-教学单位明细接口

##### 请求URL:

- api/units/getunitjxgzcdwmx

##### 请求方式

- GET

##### 参数

``` javascript
// 前端：params， 后端注解：@RequestParam
{
    type: 1,     // 分类，如：学院、职能部门
}
```

##### 返回示例

``` javascript
{
    code: 200,
    message: '请求成功',
    data: {
        fjstotal: 14512,
        zwstotal: 8000,
        fjzmjtotal: 80000,
        zjzmjtotal: 1111111,
        list: [
            {
                dwmc: '化生学院',
                ldsl: 3,
                fjsl: 10,
                fjmj: 1,
                demj: 2
            }
        ]
    }
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| fjstotal | bigint | 房间数 |
| zwstotal | bigint | 座位数 |
| fjzmjtotal | bigint | 房间总面积 |
| zjzmjtotal | int | 总建筑面积 |
| list | array | 集合 |
| dwmc | string | 单位名称 |
| ldsl | int | 楼栋数量 |
| fjsl | int | 房间数量 |
| fjmj | int | 房间面积 |
| demj | int | 定额面积 |
