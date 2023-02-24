### 数据查询

##### 简要描述:

- 数据查询接口

##### 请求URL:

- api/dataSearch/getsjcx

##### 请求方式

- GET

##### 参数

``` javascript
// 前端：params， 后端注解：@RequestParam
{
    type: 1,     // 分类，如：查楼栋、查单位，此处采用了魔鬼数字。
    keyword: '名称' // 输入关键字，如楼栋名称
}
```

##### 返回示例

``` javascript
{
    code: 200,
    message: '请求成功',
    data: []    // 不知
}
```

##### 返回参数说明

|  参数名   |  类型  | 说明  |
|  ----  | ----  | ----  |
