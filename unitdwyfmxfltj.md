### 单位用房明细-弹出（分楼栋分类统计）

##### 简要描述:

- 单位用房明细-弹出（分楼栋分类统计）接口

##### 请求URL:

- api/unit/getunitdwyfmxfltj

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
          builddingName: '东院-自动化学院专业综合实验教学中心',
          name: '实验实习用房',
          count: 6,
          area: 276
        },
        {
          builddingName: '南湖-理学院办公楼',
          name: '后勤及辅助用房',
          count: 1,
          area: 11.28
        },
        {
          builddingName: '南湖-理学院办公楼',
          name: '会堂',
          count: 5,
          area: 334.13
        },
        {
          builddingName: '南湖-理学院办公楼',
          name: '教室',
          count: 3,
          area: 130.25
        },
        {
          builddingName: '南湖-理学院办公楼',
          name: '师生活动用房',
          count: 8,
          area: 370.02
        }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| builddingName | string | 楼栋名称 |
| name | string | 分类名称 |
| count | int | 房间数量 |
| area | float | 房间面积 |
