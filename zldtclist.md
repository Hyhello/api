### 总楼栋-弹出（集合）

##### 简要描述:

- 总楼栋-弹出（集合）接口

##### 请求URL:

- api/building/getzldtclist

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
          id: 0,
          title: "西院-西品二",
          img: one,
          checked: false,
          jzmj: "1568.88㎡",
          jznd: "2020年1月",
          lcs: "5层",
          fjs: "125",
          fjmj: "3568.65㎡",
          dwfb: "研究生院、国资处",
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| id | int/string | 主键 |
| title | string | 标题 |
| img | string | cover 封面地址 |
| jzmj | float | 建筑面积 |
| jznd | string | 建筑年代 |
| lcs | int | 楼层数 |
| fjs | int | 房间数 |
| fjmj | float | 房间面积 |
| dwfb | string | 单位分布 |