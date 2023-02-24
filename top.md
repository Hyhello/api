### 总楼栋、建筑面积、地上面积、地下面积

##### 简要描述:

- 总楼栋、建筑面积、地上面积、地下面积接口

##### 请求URL:

- api/buildings/gettop

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
        zld: 1000,
        jzmj: 1000,
        dsmj: 1000,
        dxmj: 1000
    }
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
| zld | int | 总楼栋 |
| jzmj | int | 建筑面积 |
| dsmj | int | 地上面积 |
| dxmj | int | 地下面积 |
