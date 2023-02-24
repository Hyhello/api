### 单位总数、教学单位、科研单位、职能部门、直属单位、附属单位

##### 简要描述:

- 单位总数、教学单位、科研单位、职能部门、直属单位、附属单位接口

##### 请求URL:

- api/units/getunittop

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
        dwzs: 65,
        jxdw: 34,
        kydw: 24,
        znbm: 20,
        zsdw: 6,
        fsdw: 5
    }
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| dwzs | int | 单位总数 |
| jxdw | int | 教学单位 |
| kydw | int | 科研单位 |
| znbm | int | 职能部门 |
| zsdw | int | 直属单位 |
| fsdw | int | 附属单位 |
