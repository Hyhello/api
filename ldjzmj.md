### 楼栋建筑面积

##### 简要描述:

- 楼栋建筑面积接口

##### 请求URL:

- api/datashow/getldjzmj

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
            assetsname: "南湖-图书馆",
            buildingarea: 51238.7,
        },
        {
            assetsname: "余区-航海楼",
            buildingarea: 38888.3,
        },
        {
            assetsname: "鉴湖-爱特楼",
            buildingarea: 28726.8,
        },
        {
            assetsname: "鉴湖-学海楼",
            buildingarea: 27062.8,
        },
        {
            assetsname: "南湖-博学主楼",
            buildingarea: 20434.9,
        },
        {
            assetsname: "南湖-体育中心体育馆",
            buildingarea: 18284,
        },
        {
            assetsname: "南湖-体育中心体育场",
            buildingarea: 15192,
        },
        {
            assetsname: "东院-泓毅楼（主楼）",
            buildingarea: 14682.7,
        },
        {
            assetsname: "南湖-博学西楼",
            buildingarea: 14295.1,
        },
        {
            assetsname: "西院-德生楼",
            buildingarea: 13783.2,
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| assetsname | string | 名称 |
| buildingarea | int | 值 |
