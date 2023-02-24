### 首页

##### 简要描述:

- 首页接口

##### 请求URL:

- /api/home/info

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
        xq: 10,
        tdzmj: 300,
        zdws: 300,
        zfjs: 14580,
        zjss: 806,
        zld: 312,
        sysxyf: 2358,
        ssl: 84,
        kyyf: 723,
        zzc: 52
    }
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| xq | int | 校区 |
| tdzmj | int | 土地总面积 |
| zdws | int | 总单位数 |
| zfjs | int | 总房间数 |
| zjss | int | 总教室数 |
| zld | int | 总楼栋 |
| sysxyf | int | 实验实习用房 |
| ssl | int | 宿舍楼 |
| kyyf | int | 科研用房 |
| zzc | int | 总资产 |