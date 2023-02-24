### 单位用房明细-弹出（分类情况）

##### 简要描述:

- 单位用房明细-弹出（分类情况）接口

##### 请求URL:

- api/unit/getunitdwyfmxflqk

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
          name: '会堂',
          count: 5,
          area: 334.13
        },
        {
          name: '后勤及辅助用房',
          count: 1,
          area: 11.28
        },
        {
          name: '教室',
          count: 5,
          area: 265.41
        },
        {
          name: '师生活动用房',
          count: 11,
          area: 482.22
        },
        {
          name: '实验实习用房',
          count: 211,
          area: 9518.87
        },
        {
          name: '图书馆',
          count: 3,
          area: 402.08
        },
        {
          name: '院系及教师用房',
          count: 164,
          area: 4483.34
        },
        {
          name: '专职科研机构用房',
          count: 1,
          area: 14
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| name | string | 分类名称 |
| count | int | 房间数量 |
| area | float | 房间面积 |
