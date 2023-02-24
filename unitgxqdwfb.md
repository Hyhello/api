### 各校区单位分布

##### 简要描述:

- 各校区单位分布接口

##### 请求URL:

- api/units/getunitgxqdwfb

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
        { value: 35, name: '马区东院', unit: '家' },
        { value: 34, name: '马区东院', unit: '家' },
        { value: 16, name: '马区西院', unit: '家' },
        { value: 19, name: '南湖北院', unit: '家' },
        { value: 27, name: '南湖南院', unit: '家' }
    ]
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| name | string | 名称 |
| value | int | 值 |
| unit | string | 单位 |
