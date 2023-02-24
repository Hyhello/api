### 各校区楼栋分布

##### 简要描述:

- 各校区楼栋分布接口

##### 请求URL:

- api/buildings/getgxqldfb

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
        { value: 29, name: '马区东院' },
        { value: 56, name: '马区西院' },
        { value: 67, name: '南湖南院' },
        { value: 77, name: '南湖北院' },
        { value: 81, name: '余家头校区' }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| name | string | 名称 |
| value | int | 值 |